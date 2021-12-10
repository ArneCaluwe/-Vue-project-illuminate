<template>
  <div class="profile-icon__profile-border">
    <div class="profile-icon__image-template"></div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "ProfileIcon",
  props: {
    color: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
