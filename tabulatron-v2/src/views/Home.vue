<template>
  <div>
    <v-col cols="auto">
      <v-row v-for="(i, index) in 6" :key="index" style="width: 60px; height: 60px;">
        <Chord numberOfStrings="6"/>
      </v-row>
    </v-col>
  </div>
</template>

<script setup>
  import Chord from "./../components/Chord.vue"
</script>
