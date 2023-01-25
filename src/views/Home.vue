<template>
  <div class="home">
    <Header />
    <Card />
    <Footer />
  </div>
</template>

<script>
import Header from '../components/Header.vue';
import Card from '../components/Card.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Header, 
    Card, 
    Footer
  }
}
</script>

<style scoped>
  .home {
    max-width: 1244px;
    width: 100%;
    height: 100vh;

    margin: 0 auto;
    padding: 2rem 2rem 1rem 2rem;

    display: flex;
    flex-direction: column;
    justify-content: space-between;
    text-align: center;
  }

  @media (max-width: 1000px) {
    .home {
      height: 120vh;
      max-width: 353px;
      width: 100%;
    }
  }
</style>