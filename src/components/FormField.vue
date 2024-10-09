<template>
    <v-form>
     <InputTextField
      :placeHolderText="EnterName"
     ></InputTextField>

      <InputTextField
      :placeHolderText="EnterEmail"
     ></InputTextField>
     {{ EnterName }}
    </v-form>
</template>

<script setup>
import { ref } from 'vue';
import InputTextField from './InputTextField.vue';

const EnterName = ref('enter name');
const EnterEmail = ref('enter email');

</script>