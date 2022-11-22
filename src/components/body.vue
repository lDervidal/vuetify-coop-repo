<template>
    <div class="pa-16">
        <div class="d-flex mt-8 mb-8 align-start">
            <div class="flex-grow-1">
                <h1 class="text-h4 d-inline-flex w-50">Snap photos and share like never before</h1>
            </div>
        </div>
        <v-row no-gutters>
            <v-col :key="n" cols="12" sm="4">
                <v-sheet class="mr-6">
                    <div class="pb-6">
                        <v-avatar image="https://cdn.vuetifyjs.com/images/john-smirk.png" color="surface-variant" size="64"></v-avatar>
                    </div>
                    <div class="pb-4 font-weight-black">
                        <h3><b>Sed ut perspiciatis</b></h3>
                    </div>
                    <div class="">
                        <p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequunturmagni dolores eos qui ratione voluptatem.</p>
                    </div>
                    <div class="pt-4">
                        <a href="" style="color:aqua; text-decoration:none">Learn more</a>
                    </div>
                </v-sheet>
            </v-col>
            <v-col :key="n" cols="12" sm="4">
                <v-sheet class="mr-6">
                    <div class="pb-6">
                        <v-avatar image="https://cdn.vuetifyjs.com/images/john-smirk.png" color="surface-variant" size="64"></v-avatar>
                    </div>
                    <div class="pb-4 font-weight-black">
                        <h3><b>Lorem ipsum dolor</b></h3>
                    </div>
                    <div class="">
                        <p>Amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magnaaliqua. Ut enim ad minim veniam, quis.</p>
                    </div>
                    <div class="pt-4">
                        <a href="" style="color:aqua; text-decoration:none">Learn more</a>
                    </div>
                </v-sheet>
            </v-col>
            <v-col :key="n" cols="2" sm="4">
                <v-sheet class="mr-6">
                    <div class="pb-6">
                        <v-avatar image="https://cdn.vuetifyjs.com/images/john-smirk.png" color="surface-variant" size="64"></v-avatar>
                    </div>
                    <div class="pb-4 font-weight-black">
                        <h3><b>Nemo enim ipsam</b></h3>
                    </div>
                    <div class="">
                        <p>Consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est,qui dolorem ipsum quia dolor.</p>
                    </div>
                    <div class="pt-4">
                        <a href="" style="color:aqua; text-decoration:none">Learn more</a>
                    </div>
                </v-sheet>
            </v-col>
        </v-row>
    </div>
</template>
  
<script setup>
</script>
  