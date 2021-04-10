<template>
  <div>
    <v-row>
      <v-col class="pl-10 pr-10 mt-5">
        <h4>LOGO</h4>
        <v-btn color="success">text</v-btn>
      </v-col>
      <v-col> </v-col>
    </v-row>
    <v-row>
      <v-col class="text-center mt-13 pt-13 pb-0" cols="12">
        <h3 style="font-size: 20px" class="font-weight-light">
          SABTU, 17 APRIL 2020
        </h3>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="text-center pt-0 pb-0" cols="12">
        <h1 style="font-size: 83px" class="font-weight-medium text-center">
          13:30
        </h1>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="pt-0 pb-0 pl-0 pr-0 text-center" cols="6">
        <v-row>
          <v-col cols="12" class="text-center pr-0 pl-0 pb-1">
            <p style="font-size: 14px" class="font-weight-light ml-12 mb-0">
              Hadir pada
            </p>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" class="text-center pr-0 pl-0 pt-0">
            <h2
              style="font-size: 28px color: #656970"
              class="font-weight-regular text-center ml-12"
            >
              --:--
            </h2>
          </v-col>
        </v-row>
      </v-col>
      <v-col class="pt-0 pb-0 pl-0 pr-0 text-center" cols="6">
        <v-row>
          <v-col cols="12" class="text-center pr-7 pl-0 pb-1">
            <p
              style="font-size: 14px"
              class="font-weight-light text-center mb-0 mr-4"
            >
              Pulang pada
            </p>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" class="text-center pr-7 pl-0 pt-0">
            <h2
              style="font-size: 28px color: #656970"
              class="font-weight-regular text-center mr-4"
            >
              --:--
            </h2>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="pl-10 pr-10 mt-9" cols="12">
        <div class="card card-profile" style="height: 105px">
          <v-row>
            <v-col class="my-auto ml-5" cols="1">
              <v-avatar size="60" color="red">
                <img src="src" alt="alt" />
              </v-avatar>
            </v-col>
            <v-col class="ml-12 my-auto" cols="8">
              <h4 style="font-size: 18px" class="text-roboto">
                Raga Bima Jati Raksa
              </h4>
              <p style="font-size: 11px" class="mb-0">
                Status kehadiran
                <span class="attendance ml-2 mr-1"></span> Hadir
              </p>
            </v-col>
          </v-row>
        </div>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="pl-10 pr-10 mt-5" cols="12">
        <v-btn
          width="100%"
          height="58px"
          class="border-radius"
          dark
          color="#197AEB"
          ><v-icon left>mdi-bag-personal</v-icon>
          <h4 class="button-text my-auto font-weight-bold">Tandai Pulang</h4>
        </v-btn>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.attendance {
  height: 7px;
  width: 7px;
  background-color: #1eec4c;
  border-radius: 50%;
  display: inline-block;
}
.card {
  border-radius: 11px;
  border-style: solid;
  border-color: rgba(0, 0, 0, 0.1);
  box-shadow: 0px 10px 30px -20px rgba(213, 213, 213, 1);
}
.border-radius {
  border-radius: 10px;
}
</style>