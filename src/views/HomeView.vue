<script setup>
  // import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="container landing h-full d-flex flex-column align-items-center justify-content-center">
    <div class="row">
      <div class="col my-auto">
        <h1>Hi! I'm Kleinz!</h1>
        <p>15 year old high school student & web developer</p>
        <div class="d-flex flex-row gap-2">
          <button type="button" class="btn btn-info"><i class="bi bi-github"></i> Github</button>
          <button type="button" class="btn btn-success" disabled>Works</button>
        </div>
      </div>
      <div class="col my-auto"><img src="/kana.png" width="300" height="300" class="img-thumbnail"></div>
    </div>
  </div>
</template>