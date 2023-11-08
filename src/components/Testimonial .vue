<template>
    <v-container class="bp-bg text-center text-white pb-12" fluid>
        <div class="text-h2 my-7" style="font-family: 'Edu TAS Beginner', cursive !important;">Testimonial</div>
        <v-row class="justify-center">
            <v-col md="3" v-for="post in posts">
                <v-card class="rounded-lg mx-2 glass-bg text-left pa-2" theme="dark">
                    <template v-slot:prepend>
                        <img src="../assets/icons8-comma-100.png" width="30" alt="">
                        <img src="../assets/icons8-comma-100.png" width="30" alt="">
                    </template>
                    <v-card-text class="text-h5 py-2" style="line-height: 1.1em;">
                        {{ post.post }}
                    </v-card-text>
                    <v-card-actions>
                        <v-list-item class="w-100">
                            <template v-slot:prepend>
                                <v-avatar color="grey-darken-3"
                                    image="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"></v-avatar>
                            </template>
                            <v-list-item-title class="font-weight-bold">{{ post.user }}</v-list-item-title>
                            <v-list-item-subtitle>Vue Creator</v-list-item-subtitle>
                        </v-list-item>
                    </v-card-actions>
                </v-card>
        </v-col>
        </v-row>
    </v-container>
</template>


<script setup>
const posts = [{user : 'Aya kd' ,post : 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Modi illo provident quo in odio corporis exercitationem voluptate minus vero nisi!'},
    {user : 'Alaa Al' ,post : 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Modi illo provident quo in odio corporis exercitationem voluptate minus vero nisi!'},
    {user : 'Kalel KK' ,post : 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Modi illo provident quo in odio corporis exercitationem voluptate minus vero nisi!'},]




</script>




<style>
.bp-bg {
    background: rgb(118,56,28);
background: linear-gradient(130deg, rgb(207, 101, 52) 19%, rgb(243, 114, 127) 86%);}

.glass-bg {
    background: rgb(255,255,255,.3) !important;
    backdrop-filter: blur(5px);
    color: #F3F1F5;
}
</style>



