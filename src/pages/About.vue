<template>
  <q-page>
    <div class="row justify-center">
      <h1>About Page</h1>
    </div>
    <div class="row justify-center">
      <about-content />
    </div>
  </q-page>
</template>

<script>
import AboutContent from "components/AboutContent";
export default {
  // name: 'PageName',
  components: {
    AboutContent
  }
};
</script>

<style>
</style>
