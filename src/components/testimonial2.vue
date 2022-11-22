<template>
    <v-container fluid class="pa-16 d-flex flex-column justify-center align-center">
        <p class="text-md-center mb-12 text-h3">You’re in good company</p>
        <p class="d-inline-flex text-h4 text-center font-weight-regular mb-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore</p>
        <div class="d-flex justify-center align-center flex-column">
            <v-row v-for="n in 2">
                <v-img class="mx-8 my-8" cover v-for="n in 4"
                    src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" width="175" height="75"></v-img>
            </v-row>
        </div>
    </v-container>
</template>
  
<script setup>
</script>
  