<template>
  <v-app>
    <loader-component />
    <v-content>
      <v-container>
        <router-view />
      </v-container>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import { LoaderComponent } from './common/components';
export default Vue.extend({
  name: 'App',
  components: {
    LoaderComponent,
  },
});
</script>