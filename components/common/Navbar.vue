<template>
    <UContainer>
        <nav class="flex justify-between items-center py-4 w-full max-w-7xl mx-auto">
            <div class="flex items-center space-x-4">
                <NuxtLink to="/" class="text-xl font-bold text-white">Logo</NuxtLink>
            </div>
            <div class="flex items-center space-x-4">
                <NuxtLink to="/" class="text-white hover:text-gray-300">首页</NuxtLink>
                <NuxtLink to="/about" class="text-white hover:text-gray-300">关于</NuxtLink>
                <NuxtLink to="/contact" class="text-white hover:text-gray-300">联系我们</NuxtLink>
                <UButton
                    color="white"
                    variant="outline"
                    class="ml-4"
                >
                    登录
                </UButton>
            </div>
        </nav>
    </UContainer>
</template>