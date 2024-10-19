<template>
    <div class="min-h-screen bg-gradient-to-br from-blue-100 via-sky-200 to-amber-100 bg-cover bg-fixed flex flex-col justify-between" style="background-image: url('/bg.jpg'); backdrop-filter: blur(5px);">
        <div class="flex justify-between items-center pt-8 px-8">
            <div class="flex items-center space-x-2 px-4 py-2 rounded-full bg-white bg-opacity-30 backdrop-filter backdrop-blur-md border border-white border-opacity-30">
                <UIcon name="i-heroicons-queue-list" class="w-5 h-5 text-gray-700"/>
                <span class="text-center text-lg text-gray-700">waitlist</span>
            </div>
            <div class="flex items-center space-x-2">
                <UInput placeholder="输入邮箱或手机号" class="w-48"/>
                <UButton
                    label="登录"
                    color="black"
                    variant="solid"
                    class="px-4 py-2 flex items-center justify-center"
                    @click="openNotionInNewTab"
                >
                    <span class="text-center">登录</span>
                </UButton>
            </div>
        </div>
        <div class="flex flex-col items-center justify-center flex-grow">
            <h1 class="text-center text-4xl font-bold text-black mt-4 opacity-30">Coming Soon</h1>
            <div class="container mx-auto flex flex-col items-center justify-center mt-8">
                <div class="bg-white bg-opacity-30 backdrop-filter backdrop-blur-md rounded-xl p-8 max-w-md w-full">
                    <h2 class="text-2xl font-bold mb-4 text-center text-gray-800">加入我们!</h2>
                    <p class="mb-6 text-center text-gray-700">一起学习web开发课程</p>
                </div>
            </div>
        </div>
        <div class="flex justify-center space-x-6 pb-6">
            <a href="https://x.com/fsganfcjdjxb" target="_blank" rel="noopener noreferrer" class="text-gray-700 hover:text-gray-900">
                <UIcon name="i-simple-icons-x" class="w-6 h-6"/>
            </a>
            <a href="https://www.instagram.com/fxy17710117315/" target="_blank" rel="noopener noreferrer" class="text-gray-700 hover:text-gray-900">
                <UIcon name="i-simple-icons-instagram" class="w-6 h-6"/>
            </a>
            <a href="https://github.com/fxy0224/" target="_blank" rel="noopener noreferrer" class="text-gray-700 hover:text-gray-900">
                <UIcon name="i-simple-icons-github" class="w-6 h-6"/>
            </a>
        </div>
    </div>
</template>


<script setup>
const openNotionInNewTab = () => {
    window.open('https://indie-startups.notion.site/', '_blank');
}
</script>