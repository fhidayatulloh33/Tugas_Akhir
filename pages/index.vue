<template>
  <div>
    <Header />
    <main class="container">
        <div class="text-center">
        <img src="/icon.png" alt="" height="300" width="300">
        </div>
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
export default {
  components: {
    Header,
    Footer,
  },
};
</script>
