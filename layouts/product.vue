<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto flex py-4 justify-between">
        <NuxtLink to="/" class="font-bold">Nuxt Dojo</NuxtLink>
        <ul class="flex gap-4">
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products/" class="btn">Products</NuxtLink></li>
        </ul>
        <p class="text-center text-2xl font-bold py-4">Products</p>
      </nav>
      
    </header>

    <div class="container mx-ato p-4">
      <slot />
    </div>

    <footer class="constainer mx-auto p-4 flex justify-between border-t-2">
      <ul class="flex gap-4">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/">Products</NuxtLink></li>
      </ul>
    </footer>
  </div>
</template>

<style scoped></style>
