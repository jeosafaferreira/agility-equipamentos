<template>
  <v-app id="inspire">
    <topbar></topbar>
    <v-main class="bg-grey-darken-4">
      <v-container>
        <v-row>
          <v-col>
            <v-sheet min-height="70vh" rounded="lg">
              <!--  -->
            </v-sheet>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
  
<script>
import topbar from '@/components/topbar.vue'

export default {
  components:{'topbar':topbar},
  data: () => ({
    links: [
      'Dashboard',
      'Messages',
      'Profile',
      'Updates',
    ],
  }),
}
</script>