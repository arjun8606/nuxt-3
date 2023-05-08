<template>
<div>
  <header class="shadow-sm bg-white">
    <nav class="container mx-auto p-4 flex justify-between">
      <NuxtLink to="/" class="font-bold">Nuxt Dojo</NuxtLink>
      <ul class="flex gap-4">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products/" class="btn">Products</NuxtLink></li>
      </ul>
      <p class="text-center text-2xl font-bold py-4">Home</p>
    </nav>
  </header>

  <div class="container mx-ato p-4">
    <slot/>
  </div>
</div>
</template>
