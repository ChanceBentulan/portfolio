<template>
  <div class="home">
    <v-parallax height="1000" dark src="@/assets/myFace.png">
      <v-layout fill-height align-center>
        <v-container>
          <v-row align="center">
            <v-col md="5" cols="auto">
              <div class="display-2 font-weight-bold">Welcome to my page</div>
              <div class="headline" dense>&nbsp;Software Developer</div>
            </v-col>
          </v-row>
        </v-container>
      </v-layout>
    </v-parallax>
    <v-container class="mt-5">
      <section id="sec-1">
        <v-layout wrap>
          <v-row align="center" justify="center">
            <v-col>
              <v-flex xs12 align-self-center>
                <div class="display-1 font-weight-bold pb-5" >
                  About
                </div>
              </v-flex></v-col
            ></v-row
          >
          <v-flex xs12 nt-2>
            <div class="body-1 pb-10">{{ aboutText }}</div>
          </v-flex>
        </v-layout>
      </section>
      <v-spacer></v-spacer>
      <section id="sec-2">
        <v-layout wrap nt-5>
          <v-flex xs12>
            <div class="display-1 font-weight-bold pb-5" >Skills</div>
          </v-flex>
          <v-container class="mt-5">
            <v-card class="pa-6" elevation="10" max-width="624">
              <v-row>
                <v-flex>
                  <v-progress-circular
                    class="me-5 mb-3"
                    size="100"
                    value="90"
                    width="10"
                  >
                    <v-row>
                      <v-col>
                        <div class="font-weight-medium">HTML</div>
                        <div class="font-weight-medium pl-1">90%</div>
                      </v-col>
                    </v-row>
                  </v-progress-circular>
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="70"
                    width="10"
                  >
                    <v-row>
                      <v-col>
                        <div class="font-weight-medium">CSS</div>
                        <div class="font-weight-medium pl-1">70%</div>
                      </v-col>
                    </v-row>
                  </v-progress-circular>
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="65"
                    width="10"
                  >
                    <v-row>
                      <v-col>
                        <div class="font-weight-medium">VUEJS</div>
                        <div class="font-weight-medium pl-2">65%</div>
                      </v-col>
                    </v-row>
                  </v-progress-circular>
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="50"
                    width="10"
                  >
                    <v-row>
                      <v-col>
                        <div class="font-weight-medium">DJANGO</div>
                        <div class="font-weight-medium pl-3">50%</div>
                      </v-col>
                    </v-row></v-progress-circular
                  >
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="70"
                    width="10"
                  >
                    <v-row>
                      <v-col>
                        <div class="font-weight-medium">PYTHON</div>
                        <div class="font-weight-medium pl-3">70%</div>
                      </v-col>
                    </v-row></v-progress-circular
                  >
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="70"
                    width="10"
                  >
                    <v-row>
                      <v-col>
                        <div class="font-weight-medium">&nbsp;C</div>
                        <div class="font-weight-medium">70%</div>
                      </v-col>
                    </v-row></v-progress-circular
                  >
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="60"
                    width="10"
                    ><v-row>
                      <v-col>
                        <div class="font-weight-medium">C++</div>
                        <div class="font-weight-medium">60%</div>
                      </v-col>
                    </v-row></v-progress-circular
                  >
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="50"
                    width="10"
                    ><v-row>
                      <v-col>
                        <div class="font-weight-medium">OBJECTIVE-C</div>
                        <div class="font-weight-medium pl-7">50%</div>
                      </v-col>
                    </v-row></v-progress-circular
                  >
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="60"
                    width="10"
                    ><v-row>
                      <v-col>
                        <div class="font-weight-medium">FLUTTER</div>
                        <div class="font-weight-medium pl-4">60%</div>
                      </v-col>
                    </v-row></v-progress-circular
                  >
                  <v-progress-circular
                    class="me-5"
                    size="100"
                    value="50"
                    width="10"
                    ><v-row>
                      <v-col>
                        <div class="font-weight-medium">PHP</div>
                        <div class="font-weight-medium pl-1">50%</div>
                      </v-col>
                    </v-row>
                  </v-progress-circular>
                </v-flex>
              </v-row>
            </v-card>
            <v-container class="mt-5">
              <section id="sec-3">
                <v-layout wrap>
                  <v-flex xs12>
                    <div class="display-1 font-weight-bold pb-10" id="sec-3">
                      Contact
                    </div>
                  </v-flex>
                  <v-flex xs12 nt-2>
                    <v-row>
                      <v-icon class="ml-3" x-large
                        >fas fa-solid fa-envelope</v-icon
                      >
                      <div class="ml-2">ChanceBentulan@gmail.com</div>
                      <v-icon class="ml-16" x-large>fa-brands fa-github</v-icon>
                      <div class="ml-2">
                        <a
                          href="https://github.com/ChanceBentulan"
                          target="_blank"
                          >Chance Diago Bentulan</a
                        >
                      </div>
                    </v-row>
                    <v-row class="mt-10">
                      <v-icon class="ml-3" x-large
                        >fa-brands fa-linkedin</v-icon
                      >
                      <div class="ml-2 mr-12">
                        <a
                          href="https://www.linkedin.com/in/chance-diago-bentulan-9185a2230/"
                          target="_blank"
                          >Chance Diago Bentulan</a
                        >
                      </div>
                      <v-icon class="ml-16" x-large
                        >fa-brands fa-facebook-square</v-icon
                      >
                      <div class="ml-2">
                        <a
                          href="https://www.facebook.com/ChansuDiago/"
                          target="_blank"
                          >Chance Diago Bentulan</a
                        >
                      </div>
                    </v-row>
                  </v-flex>
                </v-layout>
              </section>
            </v-container>
          </v-container>
        </v-layout>
      </section>
    </v-container>
  </div>
</template>

<script>
import About from "./About.vue";
import "@/styles/override.sass";
export default {
  name: "Home",
  components: { About },
  data() {
    return {
      aboutText:
        "Hello, my name is Chance Bentulan",
    };
  },
};
</script>

<style scoped>
.font-weight-medium {
  font-size: 0.75rem;
}

a,
a:hover,
a:visited,
a:active {
  color: inherit;
  text-decoration: none;
}

.before-enter {
  opacity: 0;
  transform: translateY(100px);
  transition: all 2s ease-out;
}

.enter {
  opacity: 1;
  transform: translateY(0px);
}

/* section {
  min-height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
} */

#sec-1{
  background-color: white;
  position: flex;

}

</style>
