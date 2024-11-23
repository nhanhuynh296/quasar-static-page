<script lang="ts" setup>
import {useRouter} from "vue-router";

const router = useRouter()
function onClick() {
  router.push("letter")
}
</script>

<template>
  <q-page class="row content-center q-px-md text-center" @click="onClick">
    <div class="col-md-6 col-xs-12">
      <q-img src="~assets/love-envelope.jpg" />
      <div class=" text-h5">

        <q-btn color="black" label="💌 Nathan got you a love letter 💌"/>

      </div>

    </div>

  </q-page>

</template>

<style scoped>

</style>
