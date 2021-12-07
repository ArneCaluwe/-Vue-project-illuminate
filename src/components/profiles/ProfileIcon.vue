<template>
  <div class="profile-border">
    <div class="image-template"></div>
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
.profile-border {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 30px;
  height: 30px;
  border-radius: 15px;
  background-color: red;
}
.image-template {
  text-align: center;
  width: 25px;
  height: 25px;
  border-radius: 15px;
  background-color: white;
}
</style>
