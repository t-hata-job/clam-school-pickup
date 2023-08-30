<template>
  <v-app>
    <clanedar />
  </v-app>
</template>

<script>
import Clanedar from '~/components/Calendar.vue'
export default {
  components: { Clanedar },
  name: 'DefaultLayout',
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js',
    }
  },
}
</script>
