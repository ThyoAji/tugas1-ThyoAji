<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/biodata.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="https://media.discordapp.net/attachments/1190324338684084355/1255558138854379653/apa.png?ex=667d9123&is=667c3fa3&hm=b2e44802f1a83b8bb341fa29c2542c47a6338ae26bbc31d7515bf1c11d8b29ae&=&format=webp&quality=lossless&width=222&height=350" width="400" height="s00" />

    <div class="wrapper">
      <HelloWorld msg="Hallo Nama Saya Thyo aji Dinata " />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
