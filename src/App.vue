<template>
  <Layout>
    <template v-slot:calayxLogo>
      <img :src="logo" alt="Calayx Logo" />
    </template>
    <template v-slot:carousel>

    </template>
    <template v-slot:descriptions>
      <DescriptionText>
        
      </DescriptionText>

    </template>
    <template v-slot:button>

    </template>
    <template v-slot:walkThrough>

    </template>
  </Layout>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Layout from './components/Layout.vue';
import Logo from './assets/images/logo.png';
import DescriptionText from './components/shared/DescriptionText.vue';

export default defineComponent({
  data() {
    return {
      logo: Logo
    };
  }
});
</script>

<style scoped>
/* Your scoped styles here */
</style>
