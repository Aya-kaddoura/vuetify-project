<template>
    <v-container class="text-center my-16">
        <div class="text-h2 my-9" style="font-family: 'Edu TAS Beginner', cursive !important;">OUR Team</div>
        <v-row class="justify-center">
            <v-col cols="12" sm="3" class="rounded-lg mx-3 py-9 px-3 text-center border">
                <v-img :width="160" :height="64" class="mx-auto my-4" src="../assets/ourTeam 1.svg"></v-img>
                <div class="text-h5 font-weight-medium main-color">Designer</div>
                <div>Creating bouquets with wonderful designs</div>
            </v-col>

            <v-col cols="12" sm="3" class="rounded-lg mx-3 py-9 px-3 border text-center">
                <v-img :width="147" :height="64" class="mx-auto my-4" src="../assets/ourTeam 2.svg"></v-img>
                <div class="text-h5 font-weight-medium main-color">Gardener</div>
                <div>Lorem ipsum dolor sit amet consectetur.</div>
            </v-col>

            <v-col cols="12" sm="3" class="rounded-lg mx-3 py-9 px-3 border text-center">
                <v-img :width="147" :height="64" class="mx-auto my-4" src="../assets/ourTeam 3.svg"></v-img>
                <div class="text-h5 font-weight-medium main-color">Marketer</div>
                <div>Lorem ipsum dolor sit amet consectetur.</div>
            </v-col>

        </v-row>
    </v-container>
</template>


<script>
//
</script>
<style>
.main-color{
    color: #E85C6A;
}</style>