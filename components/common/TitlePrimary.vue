<template>
    <div class="flex items-center space-x-2">
        <UInput 
            placeholder="输入邮箱或手机号" 
            class="w-48"
        />
        <UButton
            label="登录"
            color="black"
            variant="solid"
            class="px-4 py-2"
            @click="openNotionInNewTab"
        />
    </div>
</template>

<script setup>

</script>