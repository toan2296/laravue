<template>
    <v-card class="overflow-hidden rounded-0 overflow-hidden mx-auto"
    >
      <v-app-bar
      dark
      >

      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-spacer></v-spacer>

      <v-text-field
        placeholder="Search"
        prepend-inner-icon="mdi-magnify"
        class="expanding-search mt-3"
        filled
        dense
      ></v-text-field>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <template v-slot:extension>
        <v-tabs>
          <v-spacer></v-spacer>
          <v-tab>News</v-tab>
          <v-spacer></v-spacer>
          <v-tab>Home</v-tab>
          <v-spacer></v-spacer>
          <v-tab>Profile</v-tab>
          <v-spacer></v-spacer>
        </v-tabs>
      </template>

      </v-app-bar>
    </v-card>
</template>

<script>

</script>

