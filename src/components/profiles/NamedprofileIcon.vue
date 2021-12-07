<template>
  <div
    class="container--flex-horizontal container--fit container--align-center"
  >
    <ProfileIcon color="red" />
    <p class="profile__name">Arne Caluwe</p>
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import ProfileIcon from "./ProfileIcon.vue";

export default defineComponent({
  name: "NamedProfileIcon",
  components: { ProfileIcon },
  props: {
    color: String,
    name: String,
  },
});
</script>

<style scoped lang="scss">
</style>
