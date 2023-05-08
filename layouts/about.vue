<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/" class="font-bold">Nxt Dogo</NuxtLink>
      </nav>
    </header>
  
    <div class="container mx-ato p-4">
      <slot/>
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
  
  <style scoped>
   .router-link-exact-active{
    color: #12b488;
   }
  </style>
  