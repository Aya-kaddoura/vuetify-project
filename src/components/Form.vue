<template>
    <v-col cols="10" md="6" class="mx-auto my-12">
        <div class="text-h2 my-7 text-center" style="font-family: 'Edu TAS Beginner', cursive !important; color: #7F7C82;">Contact Us</div>
        <form max-width>
            <v-text-field bg-color="grey-lighten-4" variant="solo" prepend-inner-icon="mdi-account" label="Name"></v-text-field>
            <v-text-field bg-color="grey-lighten-4" variant="solo" prepend-inner-icon="mdi-phone" label="Phone"></v-text-field>
            <v-text-field bg-color="grey-lighten-4" variant="solo" prepend-inner-icon="mdi-email" label="Email"></v-text-field>
            <v-textarea class=" text-grey-darken-1" bg-color="grey-lighten-4" variant="solo" prepend-inner-icon="mdi-message" label="Message"></v-textarea>
            <v-btn class="rounded-lg text-h6 font-weight-medium gr-bg text-white py-7 mb-6 " block>Send Message</v-btn>
        </form>
    </v-col>
</template>

<script>

</script>