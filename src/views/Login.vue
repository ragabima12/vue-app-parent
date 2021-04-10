<template>
  <div>
    <v-container>
      <v-row>
        <v-col class="text-center mt-16 pt-16 pb-0" cols="12">
          <h1 class="app-text-heading-normal">Selamat Datang</h1>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="text-center pt-1" offset="1" cols="10">
          <p class="app-text-subheading-color app-text-subheading">
            Silahkan login untuk mengetahui kehadiran dari anak anda
          </p>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="pl-4 pr-4" cols="12">
          <p class="app-text-subheading mb-0">Username</p>
          <v-text-field
            color="#C5CA"
            solo
            placeholder="Masukan Username"
          ></v-text-field>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.v-text-field__slot {
  color: #e7e7e7;
}
</style>

