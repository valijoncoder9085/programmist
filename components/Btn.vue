<template>
  <div>
    <v-btn
      @click="click"
      class="text-capitalize py-6 rounded-xl"
      width="100%"
      style="background: linear-gradient(139deg, #0677E1 0%, #8C1FE2 100%);"
      dark>
      Bepul konsultatsiya olish
    </v-btn>
    <v-dialog v-model="dialog" width="500">
      <v-card>
        <v-card-title>
          <h3>Bepul <span style="color: #8C1FE2"> konsultatsiya</span></h3>
          <v-spacer/>
          <v-btn @click="close" icon color="#0677E1" dark>
            <v-icon>
              mdi-close
            </v-icon>
          </v-btn>
        </v-card-title>
        <v-card-text>
          <v-form>
            <v-row>
              <v-col cols="12">
                <div class="mb-2">Ism</div>
                <v-text-field
                  outlined
                  dense
                  hide-details
                  placeholder="Ismingizni kiriting"
                  class="rounded-lg"
                />
              </v-col>
              <v-col cols="12">
                <div class="mb-2">Telefon raqamingiz</div>
                <v-text-field
                  outlined
                  hide-details
                  dense
                  placeholder="+998"
                  class="rounded-lg"
                />
              </v-col>
              <v-col cols="12">
                <div class="mb-2">Habaringiz</div>
                <v-textarea
                  outlined
                  dense
                  hide-details
                  placeholder="Habaringizni kiriting"
                  class="rounded-lg"
                />
              </v-col>
            </v-row>
          </v-form>
        </v-card-text>
        <v-card-actions class="pb-5">
          <v-spacer/>
          <v-btn @click="sendDialog" class="rounded-xl px-11 py-5" dark
                 style="background: linear-gradient(139deg, #0677E1 0%, #8C1FE2 100%);">
            Yuborish
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
    <v-dialog v-model="success_dialog" width="350">
      <v-card class="text-center">
        <v-card-title>
          <v-spacer/>
          <p>
            <v-img src="/feedback-message.svg" width="120"/>
          </p>
          <v-spacer/>
        </v-card-title>
        <v-card-text>
          <div>
            <p class="text-h5 font-weight-bold" style="color: black">Muvaffaqiyatli <br><span style="color: #8C1FE2"> yuborildi!</span>
            </p>
          </div>
          <div class="text-body-1">
            Operatorlar tez orada siz bilan aloqaga chiqishadi!
          </div>
        </v-card-text>
        <v-card-actions class="pb-5">
          <v-spacer/>
          <v-btn @click="successCLoseDialog" class="rounded-xl px-6 py-2" dark
                 style="background: linear-gradient(139deg, #0677E1 0%, #8C1FE2 100%);">
            Tushunarli
          </v-btn>
          <v-spacer/>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
</template>

<script>
export default {
  name: "BTNComponents",
  data() {
    return {
      dialog: false,
      success_dialog: false,
    }
  },
  methods: {
    click() {
      this.dialog = true
    },
    close() {
      this.dialog = false
    },
    sendDialog() {
      this.dialog = false;
      this.success_dialog = true;
    },
    successCLoseDialog() {
      this.success_dialog = false;
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
