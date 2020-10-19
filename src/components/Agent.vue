<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12"> Agent Name: {{this.agentName}} </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Agent",

  props: {
    agentName: {
      type: String,
      required: true
    },
  },

  data() {
    return {};
  },
};
</script>
