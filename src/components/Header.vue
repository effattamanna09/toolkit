<template>
 
<div>
    
    <v-navigation-drawer app color="#09151E">
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

    <v-app-bar app color="amber lighten-5" elevation="2">
     
<v-spacer></v-spacer>
      
    </v-app-bar>
  </div>
  
</template>

<script>
export default {
  name: "Header",

  data: () => ({ }),
};
</script>

<style></style>
