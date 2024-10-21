<template>
    <div class="min-h-screen bg-gradient-to-br from-blue-100 via-sky-200 to-amber-100 bg-cover bg-fixed flex flex-col justify-between" style="background-image: url('/bg.jpg'); backdrop-filter: blur(5px);">
        <div class="flex justify-between items-center pt-8 px-8">
            <div class="flex items-center space-x-2 px-4 py-2 rounded-full bg-white bg-opacity-30 backdrop-filter backdrop-blur-md border border-white border-opacity-30">
                <UIcon name="i-heroicons-queue-list" class="w-5 h-5 text-gray-700"/>
                <span class="text-center text-lg text-gray-700">waitlist</span>
            </div>
            <CommonTitlePrimary />
        </div>
        <FeaturesWaitlistLabelMini />
        <FeaturesWaitlistBoxContainer>
            <FeaturesWaitlistBoxHeader />
            <FeaturesWaitlistBoxDescription />
            <FeaturesWaitlistBoxJoinButton />
        </FeaturesWaitlistBoxContainer>
        <CommonSocialLinks />
    </div>
</template>


<script setup>
const openNotionInNewTab = () => {
    window.open('https://indie-startups.notion.site/', '_blank');
}
</script>