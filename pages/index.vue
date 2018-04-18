<template>
  <section class="container">
    <div>
      <picture>
        <source media="(min-width: 650px)" srcset="~/assets/images/miau-500x500.png">
        <source media="(max-width: 649px)" srcset="~/assets/images/miau-250x250.png">
        <img src="~/assets/images/miau.jpg" alt="miau" style="width:500;">
      </picture>
      <h1 class="title">
        Vue Static Practice
      </h1>
      <h2 class="subtitle">
        Nuxt.js project practice
      </h2>
      <div class="links">
        <a
          href="/about"
          target="_blank"
          class="button--green">About</a>
      </div>
    </div>
  </section>
</template>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
