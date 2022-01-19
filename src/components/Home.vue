<template>
  <base-layout>
    <v-container>
      <!-- Start part1 -->
      <v-content class="container1">
        <v-row lg="12" cols="6" md="8">
          <v-col lg="6" cols="6">
            <h1>WHAT IS THE TOOLKIT?</h1>
            <br />
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dicta, quisquam
              reprehenderit ad vero tenetur fugit repellendus pariatur recusandae impedit
              delectus aliquam rerum, nemo tempore porro sunt. Omnis nulla officia
              doloribus.lorem
            </p>
             <v-btn class="btnsubmit" outlined><span>BUTTON</span></v-btn>
          </v-col>
          <v-col lg="6" cols="6">
            <a href="#">
              <img
                class="mr-3"
                :src="require('../assets/images/toolkit1.png')"
                height="100%"
                width="100%"
            /></a>
          </v-col>
        </v-row>
      </v-content>
      <!-- End part1 -->

      <!-- Start part 2 -->
      <v-content class="container1">
        <v-row lg="12" cols="6" md="8">
          <v-col lg="6" cols="6">
            <a href="#">
              <img
                class="mr-3"
                :src="require('../assets/images/toolkit1.png')"
                height="100%"
                width="100%"
            /></a>
          </v-col>
          <v-col lg="6" cols="6">
            <h1>WHAT IS THE TOOLKIT?</h1>
            <br />
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dicta, quisquam
              reprehenderit ad vero tenetur fugit repellendus pariatur recusandae impedit
              delectus aliquam rerum, nemo tempore porro sunt. Omnis nulla officia
              doloribus.lorem
            </p>
            <v-btn class="btnsubmit" outlined><span>BUTTON</span></v-btn>
          </v-col>
        </v-row>
      </v-content>
      <!-- End part 2 -->

      <!-- Start What is the toolkit -->
      <v-content class="container1">
        <v-row justify="center">
          <v-col lg="8" cols="8">
            <h1 class="text">What is the toolkit?</h1>
            <br />

            <p class="text">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Debitis quasi a
              nihil optio. Itaque, porro! Illo ab, quam quos veniam blanditiis eligendi
              sapiente doloremque cumque eos corporis aperiam placeat esse. Lorem ipsum
              dolor sit amet consectetur, adipisicing elit. Laboriosam eligendi similique,
              assumenda facilis labore excepturi atque cum numquam suscipit corporis
              perspiciatis velit nulla. Laboriosam, nihil numquam perferendis at corporis
              officia!
            </p>
          </v-col>
        </v-row>
      </v-content>
      <!-- End What is the toolkit -->

      <!-- start card -->

      <v-content class="container1">
        <v-card elevation="2" color="#F6FBFF" outlined>
          <v-row lg="12" cols="6" md="6">
            <!-- Part1  -->
            <v-row lg="12" cols="6" md="6" justify="center" class="logo">
              <v-col cols="2"
                ><a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card1.png')"
                    height="70px"
                    width="100%" /></a
              ></v-col>

              <v-col lg="2" cols="6">
                <v-row>
                  <v-row class="pa-2" lg="2" cols="6">
                    <a href="#">
                      <img
                        class="mr-3"
                        :src="require('../assets/images/card2.png')"
                        height="70px"
                        width="100%"
                    /></a>
                  </v-row>

                  <a href="#">
                    <img
                      class="mr-3"
                      :src="require('../assets/images/card3.png')"
                      height="70px"
                      width="100%"
                  /></a>
                </v-row>
              </v-col>

              <v-col cols="2"
                ><a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card4.png')"
                    height="70px"
                    width="100%" /></a
              ></v-col>
            </v-row>
            <!-- part1 end -->

            <!-- p tag -->
            <v-col lg="4" cols="6">
              <br />

              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dicta, quisquam
                reprehenderit ad vero tenetur fugit repellendus pariatur recusandae
                impedit delectus aliquam rerum, nemo tempore porro sunt. Omnis nulla
                officia doloribus.lorem
              </p>
            </v-col>
          </v-row>
          <!-- part2 -->
          <v-row lg="12" cols="6" md="6">
            <!-- p tag -->
            <v-col lg="4" cols="6">
              <br />
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dicta, quisquam
                reprehenderit ad vero tenetur fugit repellendus pariatur recusandae
                impedit delectus aliquam rerum, nemo tempore porro sunt. Omnis nulla
                officia doloribus.lorem
              </p>
            </v-col>
            <v-row lg="12" cols="6" md="8" justify="center" class="logo">
              <v-col cols="2"
                ><a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card1.png')"
                    height="70px"
                    width="100%" /></a
              ></v-col>

              <v-col lg="2" cols="4">
                <v-row>
                  <v-row class="pa-2" lg="2" cols="6">
                    <a href="#">
                      <img
                        class="mr-3"
                        :src="require('../assets/images/card2.png')"
                        height="70px"
                        width="100%"
                    /></a>
                  </v-row>

                  <a href="#">
                    <img
                      class="mr-3"
                      :src="require('../assets/images/card3.png')"
                      height="70px"
                      width="100%"
                  /></a>
                </v-row>
              </v-col>

              <v-col cols="2"
                ><a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card4.png')"
                    height="70px"
                    width="100%" /></a
              ></v-col>
            </v-row>
          </v-row>
          <!-- part2 end -->
        </v-card>
      </v-content>

      <!-- End card -->

      <!-- Start how to use the toolkit -->
      <v-content class="container1">
        <v-row lg="12" cols="6" md="8">
          <v-col lg="6" cols="6">
            <h1>HOW TO USE THE TOOLKIT</h1>
            <br />
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dicta, quisquam
              reprehenderit ad vero tenetur fugit repellendus pariatur recusandae impedit
              delectus aliquam rerum, nemo tempore porro sunt. Omnis nulla officia
              doloribus.lorem
            </p>
          </v-col>
          <v-col lg="6" cols="4">
            <v-row justify="center">
              <v-col lg="2" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card0.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>
              <v-col lg="2" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card1.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>
              <v-col lg="2" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card2.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>

             
            </v-row>

            <!-- 2nd -->
            <v-row justify="center">
              <v-col lg="2" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card3.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>
              <v-col lg="2" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/card4.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>
              <v-col lg="3" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images//Hicon6.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>

              
            </v-row>
            <!-- end 2nd -->

            <!-- 3rd -->

            <v-row justify="center">
              <v-col lg="3" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images//Hicon7.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>
              <v-col lg="3" cols="4">
                <a href="#">
                  <img
                    class="mr-3"
                    :src="require('../assets/images/Hicon8.png')"
                    height="100%"
                    width="100%"
                    alt="Avatar"
                /></a>
              </v-col>
              
            </v-row>
            <!-- end 3rd -->
          </v-col>
        </v-row>
      </v-content>

      <!-- End how to use the toolkit -->

      <!-- Start Countries  -->
      <v-content class="container1">
        <v-row lg="8" cols="6" md="8" justify="center">
          <v-col lg="6" cols="6">
            <a href="#">
              <img
                class="mr-3"
                :src="require('../assets/images/world.png')"
                height="100%"
                width="100%"
                alt="Avatar"
            /></a>
          </v-col>
        </v-row>
        <v-row lg="8" cols="8" md="8" justify="center">
          <v-col lg="8" cols="6">
            <p class="text">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dicta, quisquam
              reprehenderit ad vero tenetur fugit repellendus pariatur recusandae impedit
              delectus aliquam rerum, nemo tempore porro sunt. Omnis nulla officia
              doloribus.lorem
            </p>
          </v-col>
        </v-row>
      </v-content>

      <!-- End Countries  -->
    </v-container>
  </base-layout>
</template>

<script>
import BaseLayout from "../App.vue";
export default {
  name: "Home",
  components: {
    BaseLayout,
  },

  data: () => ({}),
};
</script>
