<template>
  <div>
    <div class="row">
      <div class="col-12">
        <v-app :class="adaptBackground">
          <router-view />
        </v-app>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentPath: "",
    };
  },
  computed: {
    adaptBackground() {
      if (this.currentPath == "/login") return "app-bg-white";
      return "app-bg-grey";
    },
  },
};
</script>

<style scoped>
.app-bg-grey {
  background: #fbfbfb;
}
.app-bg-white {
  background: white;
}
</style>