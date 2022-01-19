<template>
  <div>
    <v-container>
      <v-card>
        <v-navigation-drawer app left color="#F7F7F7">
          <v-divider></v-divider>
          <v-list>
            <v-list-item link href="#">
              <a href="#">
                <img class="mr-3" :src="require('../assets/images/logo.png')" height="60"
              /></a>
            </v-list-item>
<!-- <template v-slot:activator> -->
            <v-list-item-content>
              <v-list-item v-for="link in links" :key="link.text" router :to="link.route">
                <v-list-item-title class="font-class-name"
                  >{{ link.text }}
                  
                  <v-list-item
                    v-for="children in link.links"
                    :key="children.text"
                    router
                    :to="children.route"
                  >
                    {{ children.text }}
                  </v-list-item>
                </v-list-item-title>
              </v-list-item>
            </v-list-item-content>
 <!-- </template> -->
            <a href="#">
              <img
                class="mr-3"
                :src="require('../assets/images/savelogo.png')"
                height="60"
            /></a>
          </v-list>
        </v-navigation-drawer>
      </v-card>
    </v-container>

    <v-app-bar app color="white" elevation="0">
      <v-btn class="navsearch" text
        ><v-text-field class="textunderline" hide-details></v-text-field
        ><v-icon> mdi-magnify</v-icon></v-btn
      >
      <v-btn><v-icon> mdi-camera</v-icon></v-btn>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  name: "Header",

  data: () => ({
    drawer: false,
    links: [
      { text: "Home", route: "/" },
      {
        text: "Access",
        route: "/",
         active: true,
        children: [
          { text: "Emotional&Psychosocial Protection", route: "/" },
          { text: "Emotional&Psychosocial Protection", route: "/" },
        ],
      },
      { text: "Emotional&Psychosocial Protection", route: "/" },
      { text: "Physical Protection", route: "/" },
      { text: "Teaching&Learning", route: "/" },

      { text: "Parents&Community", route: "/" },
      { text: "School leadership&management", route: "/" },
      { text: "Policy & System", route: "/" },
      { text: "Meal", route: "/" },
      { text: "Glossary", route: "/" },
      { text: "Help", route: "/" },
    ],
  }),
};
</script>
