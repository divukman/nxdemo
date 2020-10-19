<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          NXDemo AGENTS
        </h1>

        <agent agentName="Agent1" />
        <agent agentName="Agent2" /> 
        <agent agentName="Agent3" /> 
        <agent agentName="Agent4" /> 
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >

      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
      </v-col>

    </v-row>
  </v-container>
</template>

<script>

import Agent from '../components/Agent';

  export default {
    name: 'Agents',

    components: {
      Agent
    },

    data: () => ({
    })
  }
</script>
