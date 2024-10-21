<template>
    <div class="pages-waitlist flex flex-col items-center justify-center min-h-screen">
        <FeaturesWaitlistLabelMini />
        <CommonTitlePrimary />
        <FeaturesWaitlistBoxContainer class="mb-8">
            <FeaturesWaitlistBoxHeader class="mb-4" />
            <FeaturesWaitlistBoxDescription class="mb-6" />
            <FeaturesWaitlistBoxJoinButton />
        </FeaturesWaitlistBoxContainer>
    </div>
</template>

<script setup>
const openNotionInNewTab = () => {
    window.open('https://indie-startups.notion.site/', '_blank');
};
</script>

<style>
.pages-waitlist {
    min-height: calc(100vh - 100px);
}
</style>