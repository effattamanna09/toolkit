<template>
   <v-app>
 
      <v-app-bar
          app
          color="yellow"
        >
          <v-toolbar-title>Navbar</v-toolbar-title>
          <v-spacer></v-spacer>
      </v-app-bar>
      <v-navigation-drawer
            app
            color="#09151E"
            >
            <v-divider></v-divider>
            <v-list nav dense>
                <v-list-item link href="#">
                    <v-list-item-icon>
                        <v-icon color="white" small>mdi-lightbulb</v-icon>
                    </v-list-item-icon>
                    <v-list-item-title class="title">Blue</v-list-item-title>
                </v-list-item>
            </v-list>
      </v-navigation-drawer>
      <v-content>
          <v-container
            fluid
            fill-height
          >
            <v-layout>
              <v-flex>
                Content..
              </v-flex>
            </v-layout>
          </v-container>
      </v-content>
   </v-app>
</template>

<script>
export default {
  name: "Header",

  data: () => ({
   
  }),
};
</script>