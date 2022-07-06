<template>
<v-container
  fluid
>
<v-card
    fluid
    dark
    class="mx-auto rounded-0"
    outlined
    color="#424242"
  >

  <v-row justify="space-around">
  <v-avatar
    color="indigo"
    size="84"
    >
      <v-icon dark>
        mdi-account-circle-outline
      </v-icon>
  </v-avatar>

  <v-list-item-content >
  <v-list-item-title>
    r/ Lorem
  </v-list-item-title>
  <v-list-item-subtitle>
    u/ user12345
  </v-list-item-subtitle>
  </v-list-item-content>
  </v-row>

  <v-card-text class="text-truncate"
      style="max-width: 500px;">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. In mollitia alias similique, incidunt vel numquam quia consectetur itaque. Facere repellat aperiam natus accusamus dolorem vitae officiis dolor, id reiciendis enim hic odio delectus consequatur recusandae iure voluptates quam beatae sequi.
    </v-card-text>

    <v-card-actions>
      <v-btn icon>
        <v-icon>mdi-thumb-up-outline</v-icon>
      </v-btn>

      <span>Vote</span>
      <v-btn icon>
        <v-icon>mdi-thumb-down-outline</v-icon>
      </v-btn>
      
      <v-spacer></v-spacer>
      <v-btn icon>
        <v-icon>mdi-comment-plus-outline</v-icon>
      </v-btn>
      <v-spacer></v-spacer>

      <span>Share</span>
      <v-btn icon>
        <v-icon>mdi-share-outline</v-icon>
      </v-btn>
    </v-card-actions>
  </v-card>
  </v-container>
</template>

<script>

</script>
