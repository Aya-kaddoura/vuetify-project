<template>
  <v-footer style="background-color: #d16b3cd5;">
    <v-row justify="center" no-gutters>
      <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        variant="text"
        class="mx-2"
        rounded="xl"
      >
        {{ link }}
      </v-btn>
      <v-col class="text-center mt-4" cols="12" style="color: #F3F1F5;">
        {{ new Date().getFullYear() }} — <strong>Rose</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>


<script>
  export default {
    data: () => ({
      links: [
        'Home',
        'Team',
        'Product',
        'Contact Us',
      ],
    }),
  }
</script>


