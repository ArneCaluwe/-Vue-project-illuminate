<template>
  <button class="button button--rounded">
    <NamedProfile color="red" />
  </button>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import NamedProfile from "./NamedProfile.vue";

export default defineComponent({
  name: "ProfileButton",
  components: { NamedProfile },
});
</script>

<style scoped lang="scss">
.button {
  //border: 1px solid lightgrey;
  margin: 2em;
}
</style>
