<template>
    <v-footer app color="primary" dark absolute :footer="footer">
      <v-col
        class="text-center"
        cols="12"
      >
      {{ new Date().getFullYear() + ' ' +footer }}
      </v-col>
    </v-footer>
</template>
<script>
export default {
  props: ['footer']
}
</script>
