<script>
import HeaderComponent from './components/HeaderComponent.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    HeaderComponent,
    AppHero
  }
}
</script>

<template>
  <div class="container">
    <header>
      <HeaderComponent></HeaderComponent>
    </header>
    <main>
      <AppHero></AppHero>
    </main>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: pink;
}

.container {
  max-width: 600px;
  margin: 20px auto;
  border-radius: 20px;
  border: 3px solid grey;
  background-color: burlywood;
  padding: 15px;

}

main {
  padding: 15px;
}
</style>
