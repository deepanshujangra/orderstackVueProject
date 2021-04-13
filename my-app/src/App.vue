<template>
  <v-app id="inspire">
    <v-app-bar app color="white" flat>
      <!-- <v-app-bar-nav-icon></v-app-bar-nav-icon> -->
      <v-toolbar-title>Scool</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn color="black" text>Become a Mentor</v-btn>

      <v-btn color="primary" elevation="0"> Join Us </v-btn>

      <v-menu left bottom>
        <template v-slot:activator="{ on, attrs }">
          <v-btn icon v-bind="attrs" v-on="on">
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>
        </template>

        <v-list>
          <v-list-item v-for="n in 5" :key="n" @click="() => {}">
            <v-list-item-title>Option {{ n }}</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>

    <v-main class="">
      <v-container>
        <v-row>
          <v-col cols="12" sm="9">
            <v-row>
              <v-col cols="12" sm="12">
                <v-sheet rounded="xl">
                  <v-card :loading="loading" rounded="xl" elevation="6">
                    <template slot="progress">
                      <v-progress-linear
                        color="deep-purple"
                        height="10"
                        indeterminate
                      ></v-progress-linear>
                    </template>

                    <v-img
                      height="200"
                      src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                    ></v-img>

                    <v-card-text class="headline font-weight-bold" >Iphone Videography For Product</v-card-text>

                    <v-card-actions>
                      <v-list-item class="grow">

                        
                      <v-icon > mdi-twitter </v-icon>
                      <span class="font-weight-light">Twitter</span>
                      <v-spacer></v-spacer>
                      <v-icon left> mdi-twitter </v-icon>
                      <span class="font-weight-light">Twitter</span>
                      <v-spacer></v-spacer>
                      <v-icon > mdi-twitter </v-icon>
                      <span class=" font-weight-light">Twitter</span>

                        <v-row align="center" justify="end">
                          <v-btn
                            color="primary" 
                          >
                            Buy Now
                          </v-btn>
                        </v-row>
                      </v-list-item>
                    </v-card-actions>
                  </v-card>
                </v-sheet>
              </v-col>
              <v-col cols="12" sm="12">
                <v-card elevation="6" rounded="xl">
                  <v-card-title
                    ><span style="border-bottom: 2px solid #f3164d"
                      >Card title</span
                    ></v-card-title
                  >

                  <v-card-text>
                    Phasellus magna. Quisque rutrum. Nunc egestas, augue at
                    pellentesque laoreet, felis eros vehicula leo, at malesuada
                    velit leo quis pede. Aliquam lobortis. Quisque libero metus,
                    condimentum nec, tempor a, commodo mollis, magna. In turpis.
                    In dui magna, posuere eget, vestibulum et, tempor auctor,
                    justo. In turpis. Pellentesque dapibus hendrerit tortor. Ut
                    varius tincidunt libero.
                  </v-card-text>
                </v-card>
              </v-col>
            </v-row>
          </v-col>

          <v-col cols="12" sm="3">
            <v-sheet rounded="xl">
              <v-card rounded="xl" class="text-center pa-5" elevation="6">
                <v-card rounded="xl">
                  <v-img
                    height="280"
                    src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                  ></v-img>
                </v-card>

                <v-card-text>
                  <!-- <v-card-title>Deepak Shapeti</v-card-title> -->
                  <h2 class="ma-1">Deepak Shapeti</h2>
                  <div class="subtitle-2 ma-1">
                    Obsessive Serial Entrepreneur
                  </div>
                  <v-divider class="mx-4 mb-2"></v-divider>
                  <div>
                    Small plates, salads & sandwiches - an intimate setting with
                    12 indoor seats plus patio seating.
                  </div>
                </v-card-text>

                <v-card-text>
                  <v-chip-group>
                    <v-chip x-small>5:30PM</v-chip>

                    <v-chip x-small>7:30PM</v-chip>

                    <v-chip x-small>8:00PM</v-chip>
                  </v-chip-group>
                </v-card-text>
              </v-card>
            </v-sheet>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" sm="4">
            <v-card elevation="6" rounded="xl" min-height="268">
              <v-card-title class="justify-center">
                <span style="border-bottom: 2px solid #f3164d"
                  >Key Takeaways</span
                ></v-card-title
              >

              <v-card-text>
                <ul>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                </ul>
              </v-card-text>
            </v-card>
          </v-col>

          <v-col cols="12" sm="8">
            <v-card elevation="6" rounded="xl" min-height="268">
              <v-card-title class="justify-center">
                <span style="border-bottom: 2px solid #f3164d"
                  >Card title</span
                ></v-card-title
              >

              <v-card-text>
                Phasellus magna. Quisque rutrum. Nunc egestas, augue at
                pellentesque laoreet, felis eros vehicula leo, at malesuada
                velit leo quis pede. Aliquam lobortis. Quisque libero metus,
                condimentum nec, tempor a, commodo mollis, magna. In turpis. In
                dui magna, posuere eget, vestibulum et, tempor auctor, justo. In
                turpis. Pellentesque dapibus hendrerit tortor. Ut varius
                tincidunt libero.
              </v-card-text>
              <v-card-text>
                <ol class="mb-0">
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                </ol>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="12" sm="8">
            <v-card elevation="6" rounded="xl" min-height="268">
              <!-- <v-img
                height="300"
                
                src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
              ></v-img> -->
              <video width="100%" controls>
                <source
                  src="https://www.w3schools.com/html/movie.mp4"
                  type="video/mp4"
                />
                Your browser does not support the video tag.
              </video>
            </v-card>
          </v-col>

          <v-col cols="12" sm="4">
            <v-card elevation="6" rounded="xl">
              <v-card-title class="justify-center">
                <span style="border-bottom: 2px solid #f3164d"
                  >Is this EMC for you?</span
                ></v-card-title
              >

              <v-card-text>
                Digital Marketing 101 is the ultimate primer you need to get
                started with a career in Digital marketing. This course is a
                Digital Marketing 101 is the ultimate primer you need to get
                started with a career in Digital marketing. This course is
                Digital Marketing 101 is the ultimate primer you need to get
                started Digital Marketing 101 is the ultimate primer This course
                isDigital Marketing 101 is the ultimate primer you need to get
                started. Digital Marketing 101 is the ultimate primer you need
                to get started with a career in Digital marketing This course is
                a Digital Marketing 101 is the ultimate primer you need to get
                started with a career in Digital marketing. This course is
                Digital Marketing 101 is the ultimate primer you need to get
                started Digital Marketing 101 is the in Digital marketing. This
                course is Digital Marketing 101 is the ultimate primer you need
                to get started Digital Marketing 101 is the This course is
                Digital Marketing 101 is the ultimate primer you need to get
                started Digital Marketing 101 is the in Digital marketing. This
                course is Digital Marketing 101 is the ultimate primer you need
                to get started Digital Marketing 101 is the This course is
                Digital Marketing 101 is the ultimate
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="12" sm="4">
            <v-card elevation="6" rounded="xl" min-height="268">
              <v-card-title class="justify-center">
                <span style="border-bottom: 2px solid #f3164d"
                  >About this Mentor</span
                ></v-card-title
              >

              <v-card-text>
                <v-card-text>
                  Digital Marketing 101 is the ultimate primer you need to get
                  started with a career in Digital marketing. Thi course is a
                  Digital Marketing 101 is the ultimate primer you need to get
                  started with a career in Digital marketing. This course
                  isDigital Marketing 101 is the ultimate primer you need to get
                  started. Digital Marketing 101 is the ultimate primer you need
                  to get started with a career in Digital marketing This course
                  is a Digital Marketing 101 is the ultimate primer you need to
                  get started with a career in Digital marketing. This course is
                  Digital Marketing 101 is the ultimate primer you need to get
                  started Digital Marketing 101 is the in Digital marketing.
                  This course is Digital Marketing 101 is the ultimate primer
                  you need to get started Digital Marketing 101 is the
                </v-card-text>
              </v-card-text>
            </v-card>
          </v-col>

          <v-col cols="12" sm="8">
            <v-card elevation="6" rounded="xl" min-height="268">
              <v-card-title class="justify-center">
                <span style="border-bottom: 2px solid #f3164d"
                  >Card title</span
                ></v-card-title
              >

              <v-card-text>
                Phasellus magna. Quisque rutrum. Nunc egestas, augue at
                pellentesque laoreet, felis eros vehicula leo, at malesuada
                velit leo quis pede. Aliquam lobortis. Quisque libero metus,
                condimentum nec, tempor a, commodo mollis, magna. In turpis. In
                dui magna, posuere eget, vestibulum et, tempor auctor, justo. In
                turpis. Pellentesque dapibus hendrerit tortor. Ut varius
                tincidunt libero.
              </v-card-text>
              <v-card-text>
                <ol class="mb-0">
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                </ol>
              </v-card-text>

              <v-card-text>
                Phasellus magna. Quisque rutrum. Nunc egestas, augue at
                pellentesque laoreet, felis eros vehicula leo, at malesuada
                velit leo quis pede. Aliquam lobortis. Quisque libero metus,
                condimentum nec, tempor a, commodo mollis, magna. In turpis. In
                dui magna, posuere eget, vestibulum et, tempor auctor, justo. In
                turpis. Pellentesque dapibus hendrerit tortor. Ut varius
                tincidunt libero.
              </v-card-text>
              <v-card-text>
                <ol class="mb-0">
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                </ol>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="12" sm="7">
            <v-card rounded="xl" class="text-center" elevation="6">
              <v-card rounded="xl">
                <v-img
                  height="280"
                  src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                ></v-img>
              </v-card>
            </v-card>
          </v-col>

          <v-col cols="12" sm="5">
            <v-card elevation="6" rounded="xl" min-height="268">
              <v-card-title class="justify-center">
                <span style="border-bottom: 2px solid #f3164d"
                  >Key Takeaways</span
                ></v-card-title
              >

              <v-card-text>
                <ul>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                  <li>
                    Digital Marketing need get started 101 is the ultimate
                    primer
                  </li>
                </ul>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
  <!-- <v-main>
      <HelloWorld/>
    </v-main> -->
</template>

<style scoped>
ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

ul > li {
  padding-left: 1em;
  text-indent: -1.7em;
}

ul > li:before {
  display: inline-block;
  vertical-align: middle;
  width: 10px;
  height: 10px;
  background-color: #f3164d;
  border-radius: 50%;
  margin-right: 8px;
  content: " ";
  box-shadow: 2px 2px 5px gray;
}
</style>

<script>
// import HelloWorld from './components/HelloWorld';

export default {
  name: "App",

  components: {
    // HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
