<template>
  <v-app id="inspire">
    <v-app-bar app color="white" flat>
      <v-toolbar-title>Scool</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn color="black" text>Become a Mentor</v-btn>

      <v-btn color="primary" elevation="0"> Join Us </v-btn>
      
    </v-app-bar>

    <v-main class="">
      <v-container>
        <v-row>
          <v-col cols="12" sm="8">
            <v-row>
              <v-col cols="12" sm="12">
                <v-sheet rounded="xl">
                  <v-card :loading="loading" rounded="xl" elevation="6" style="padding: 0!important;">
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

                    <v-card-text class="headline font-weight-bold pb-0" ><span style="border-bottom:2px solid #f3164d; padding-bottom:10px">Iphone</span> Videography For Product</v-card-text>
                    <div class="mb-0">
                      <v-list-item class="grow">
                        <v-row align="center" justify="end">
                          <v-spacer></v-spacer>
                          <v-spacer></v-spacer>
                          <v-col align="right" justify="end" class="pb-0">
                            <span class=" mr-1" style="font-size:x-small;color:#f3164d" >Apply promocode</span>
                          </v-col>
                          <v-col align="right" justify="end" class="pb-0">
                            <small class="text-decoration-line-through mr-5">₹ 799</small>
                            <span class=" mr-1" style="font-size:x-large;color:#f3164d" >₹ 799</span>
                          </v-col>
                        </v-row>
                      </v-list-item>
                    </div>
                    <v-card-actions class="pt-0">
                      <v-list-item class="grow">

                      <v-icon left class="text--disabled"> mdi-account </v-icon>
                      <span class="font-weight-light text--disabled" style="font-size: smaller;">By Ajay Sharma</span>
                      <v-spacer></v-spacer>
                      <v-icon class="text--disabled" left> mdi-calendar </v-icon>
                      <span class="font-weight-light text--disabled" style="    font-size: smaller;">05 March 2020</span>
                      <v-spacer></v-spacer>
                      <v-icon class="text--disabled" left> mdi-clock </v-icon>
                      <span class=" font-weight-light text--disabled" style="    font-size: smaller;">09:00 AM To 07:00 PM</span>

                        <v-row align="center" justify="end" >
                          <v-btn
                            color="primary" 
                            class='text-transform-none'
                          >
                            Book Now
                          </v-btn>
                        </v-row>
                      </v-list-item>
                    </v-card-actions>
                  </v-card>
                </v-sheet>
              </v-col>
              <v-col cols="12" sm="12">
                <v-card elevation="6" rounded="xl" style="padding: 0!important;">
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

          <v-col cols="12" sm="4">
            <v-sheet rounded="xl">
              <v-card rounded="xl" class="text-center pa-5" elevation="6" style="padding: 0!important;">
                <v-card rounded="xl" style="padding: 0!important;">
                  <v-img
                    height="280"
                    src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                  ></v-img>
                </v-card>

                <v-card-text>
                  <h2 class="ma-1 text-uppercase" style="color:#f3164d; font-weight:900;">Deepak Shapeti</h2>
                  <div class="subtitle-2 ma-1">
                    Obsessive Serial Entrepreneur
                  </div>
                  <v-divider class="mx-4 mb-2"></v-divider>
                  <div>
                    <small>
                      Small plates, salads & sandwiches - an intimate setting with
                    12 indoor seats plus patio seating.  plus patio seating. 
                    an intimate setting with
                    12 indoor seats plus patio seating.  plus patio seating
                    </small>
                  </div>
                </v-card-text>

                <v-card-text>
                  <v-chip-group column>
                    <v-chip x-small>metext here</v-chip>

                    <v-chip x-small>metext here</v-chip>

                    <v-chip x-small>metext here</v-chip>
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
                started Digital Marketing 101 is the in Digital
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
            <v-card rounded="xl" class="text-center" elevation="6" style="padding:0">
              <v-card rounded="xl" style="padding:0">
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

.v-application {
   font-family: 'Montserrat', sans-serif!important;
   font-weight: bold;
 }

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
.v-btn {
  text-transform:none !important;
}
.v-card{
  padding: 2%;

}
.v-card__text{
  line-height: 1.7rem!important;
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
