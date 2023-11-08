<template>
    <v-container class="mt-10" style="width: 75%;">
        <div class="text-h2 text-center mt-10 mb-2" style="font-family: 'Edu TAS Beginner', cursive !important;">OUR Serves</div>
        <div class="text-h5 text-center mb-12" style="color: #D94C57;font-family: 'Edu TAS Beginner'!important">Flowers for all kinds of occasions</div>
        <v-row class="justify-center justify-space-sm-between">
            <v-col cols="10" sm="4" class="text-center">
                <v-card height="90%">
                    <v-img height="100%" src="../assets/Graduation-Flowers.webp" cover>
                        <span class="my-span d-flex align-center justify-center font-weight-medium" style="font-size: 1.1em;color: #fff;">
                            Graduation event
                        </span>
                    </v-img>
                </v-card>
            </v-col>
            <v-col cols="10" sm="4" class="text-center">
                <v-card height="90%">
                    <v-img height="100%" src="../assets/Wedding hall.jpg" cover>
                        <span class="my-span d-flex align-center justify-center font-weight-medium" style="font-size: 1.1em;color: #fff;">
                            Wedding day
                        </span>
                    </v-img>
                </v-card>
            </v-col>
            <v-col cols="10" sm="4" class="text-center"> 
                <v-card height="90%">
                    <v-img height="100%" src="../assets/Birthday Cake.jpg" cover>
                        <span class="my-span d-flex align-center justify-center font-weight-medium" style="font-size: 1.1em;color: #fff;">
                            Birthday parties
                        </span>
                    </v-img>
                </v-card>
            </v-col>
        </v-row>
        <div class="d-flex justify-center justify-sm-end">
            <v-btn class="bp-bg text-white">Load More</v-btn>
        </div>
    </v-container>
</template>

<script setup>
</script>
<style>
.my-span {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #2e130f80 ;
       height: 100%;
}</style>