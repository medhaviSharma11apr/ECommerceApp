<template>
  <v-app>
    <v-main>
      <!-- <HelloWorld/> -->
      <FormField></FormField>
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import FormField from './components/FormField.vue';

export default {
  name: 'App',

  components: {
    // HelloWorld,
    FormField,
  },

  data: () => ({
    //
  }),
}
</script>
