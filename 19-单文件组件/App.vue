<template>
  <School></School>
  <hr>
  <Student></Student>
</template>

<script>
import {School} from './School.vue';
import Student from './Student.vue';

export default {
    name: 'App',
    components: {School, Student},
};
</script>
