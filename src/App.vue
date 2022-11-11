<template>
  <v-app>
    <v-main>
      <Header />
      <Hero />
      <Body />
      <SignUp />
      <Body2 />
      <Testimonial />
      <Testimonial2 />
      <Footer />
    </v-main>
  </v-app>
</template>

<script setup>
  import Header from '@/components/header.vue'
  import Hero from '@/components/hero.vue'
  import Body from '@/components/body.vue'
  import SignUp from '@/components/signup.vue'
  import Body2 from '@/components/body2.vue'
  import Testimonial from '@/components/testimonial.vue'
  import Testimonial2 from '@/components/testimonial2.vue'
  import Footer from '@/components/footer.vue'
</script>
