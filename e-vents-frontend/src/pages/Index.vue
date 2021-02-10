<template>
  <Layout>
    <v-container>
     <v-row>
       <v-col sm="6" offset-sm="4">
        <v-tabs v-model="tab" grow>
          <v-tab>Item One</v-tab>
          <v-tab>Item two</v-tab>
          <v-tab>Item Three</v-tab>
      </v-tabs>
      <v-card
      class="mx-auto"
      max-width="400"
    >
      <v-img
        class="white--text align-end"
        height="200px"
        src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
      >
        <v-card-title>Top 10 Australian beaches</v-card-title>v-img>

      <v-card-subtitle class="pb-0">
        Number 10
      </v-card-subtitle>

      <v-card-text class="text--primary">
        <div>Whitehaven Beach</div>

        <div>Whitsunday Island, Whitsunday Islands</div>
      </v-card-text>

      <v-card-actions>
        <v-btn
          color="orange"
          text
        >
          Share
        </v-btn>

        <v-btn
          color="orange"
          text
        >
          Explore
        </v-btn>
      </v-card-actions>
    </v-card>
    </v-col>
  </v-row>
   </v-container>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  },
  data(){
    return {
      tab: 0
    }
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
