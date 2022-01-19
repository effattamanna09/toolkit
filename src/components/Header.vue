<template>
  <v-container>
    <v-navigation-drawer app left>
    

      <v-list>
        <div class="pa-1 text-no-wrap rounded-xl c elevation-9">
          <v-list-item link href="#">
            <a href="#">
              <img class="mr-3" :src="require('../assets/images/logo.png')" height="70"
            /></a>
          </v-list-item>
          <!-- <template v-slot:activator> -->
          <v-list-item-content>
            <v-list-item v-for="link in links" :key="link.text" router :to="link.route">
              <v-list-item-title class="font-class-name"
                >{{ link.text }}

                <v-list-item
                  class="child"
                  v-for="children in link.children"
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
            <img class="mr-3" :src="require('../assets/images/savelogo.png')" height="60"
          /></a>
        </div>
      </v-list>
    </v-navigation-drawer>

    <v-app-bar app color="white" elevation="0">
      <v-btn class="navsearch" text
        ><v-text-field class="textunderline" hide-details></v-text-field
        ><v-icon> mdi-magnify</v-icon></v-btn
      >
      <v-btn><v-icon>mdi-filter</v-icon></v-btn>
    </v-app-bar>
  </v-container>
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
          { text: "What if..?", route: "/" },
          { text: "Intersectionality Tip", route: "/" },
          { text: "Relevant Indicators", route: "/" },
          { text: "Further Readings", route: "/" },
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
