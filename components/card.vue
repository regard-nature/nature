<template>
  <article class="card">
    <nuxt-link
      :to="{ name: 'blog-slug'}"
      class="wrapper"
    >
      <h1 class="card_title">記事１</h1>
      <p class="card_text">記事の内容。hogehogehogehogehoge</p>
      <p class="card_date">2018/8/2</p>
    </nuxt-link>
  </article>
</template>

<style>
</style>
