<template>
  <q-layout view="hhh lpR fff">

    <HeaderMain />
    <BodyMain />

    <q-page-container>
      <!-- <router-view /> -->
      
    </q-page-container>

  </q-layout>
</template>


<script>
import HeaderMain from 'components/HeaderMain.vue'
import BodyMain from 'components/BodyMain.vue'


export default {

  components: {
    HeaderMain, BodyMain
  }

}

</script>