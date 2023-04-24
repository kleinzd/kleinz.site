<script setup>
  import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="hero min-h-[calc(100vh-64px)]">
    <div class="hero-content flex-col lg:flex-row-reverse gap-16">
      <img src="/nijika.jpg" class="max-w-sm rounded-full shadow-2xl" />
      <div>
        <h1 class="text-5xl font-bold">Hi!</h1>
        <p class="py-6">I'm Miguel! Also known as "Kleinz" online. I'm a 15 year old, high school student based in the
          Philippines. <br />I do coding as a hobby!</p>
        <RouterLink class="btn btn-success" to="/links"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
            stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-2">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M13.19 8.688a4.5 4.5 0 011.242 7.244l-4.5 4.5a4.5 4.5 0 01-6.364-6.364l1.757-1.757m13.35-.622l1.757-1.757a4.5 4.5 0 00-6.364-6.364l-4.5 4.5a4.5 4.5 0 001.242 7.244" />
          </svg>
          Links/Contact</RouterLink>
      </div>
    </div>
</div></template>