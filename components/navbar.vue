<template>
  <!-- This example requires Tailwind CSS v2.0+ -->
  <nav class="bg-gray-800">
    <div class="px-2 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <div class="relative flex items-center justify-center h-16">
        <div class="flex items-center flex-1 sm:items-stretch sm:justify-start">
          <div class="flex items-center flex-shrink-0">
            <NuxtLink to="/">
              <img
                class="block rounded-lg"
                width="32px"
                height="32px"
                src="~/assets/logo.png"
                alt="Kemono logo"
                to="/"
              >
            </NuxtLink>
          </div>
          <div class="hidden sm:block sm:ml-6">
            <div class="flex space-x-4">
              <NuxtLink
                href="#"
                class="px-3 py-2 text-sm font-medium text-gray-300 rounded-md hover:bg-gray-700 hover:text-white"
                aria-current="page"
                to="/artists"
              >
                Artists
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
