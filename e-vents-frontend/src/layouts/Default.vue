<template>
  <v-app>
    <p>{{ $static.metadata.siteDescription }}</p>
  <v-main>
    <slot/>
  </v-main>
  </v-app>
</template>

<static-query>
query {
  metadata {
    siteName,
    siteDescription
  }
}
</static-query>
