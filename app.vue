<template>
  <div class="w-full min-h-screen bg-[url('/bg.jpg')] bg-cover bg-fixed bg-no-repeat bg-center">
    <div class="absolute inset-0 bg-black bg-opacity-30"></div>
    <div class="relative z-10">
      <NuxtRouteAnnouncer />
      <CommonNavbar />
      <NuxtPage />
      <CommonSocialLinks />
      <CommonFooter />
    </div>
  </div>
</template>
