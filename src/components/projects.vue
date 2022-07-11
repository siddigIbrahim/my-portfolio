<template>
  <div id="projects" class="main pt-16">
     <h1 class="project-title text-h4 text-sm-h3 text-md-h2 ml-5 mb-10" data-aos="fade-right"
     
     data-aos-easing="linear"
     data-aos-duration="800"
    >my <span  class="text-h3 text-sm-h2 text-md-h1 ">p</span>rojects</h1>
    <v-container class="project-container">
        <v-row class="tech-row d-flex justify-center align-center" >
            <v-col cols="12" class="col-md-5 col-lg-4" data-aos="fade-right"
     
     data-aos-easing="linear"
     data-aos-duration="800">
    <v-hover v-slot="{ hover }">
         <v-card
    class="mx-auto proj-card"
    elevation="10"
    max-width="370"
  >
    <v-img
      class="white--text align-end"
      height="300px"
      src="../assets/dealership.png"
    >
     <v-fade-transition>
          <v-overlay
            v-if="hover"
            absolute
            color="#3bb5e9"
            opacity="1"
          >
             
      <div class="pa-1 d-flex align-start justify-center overlay-div">A Dealership Website consist of car galery with responsive and beutiful design, 
        it consist of a navbar, a header, a prodect section, partnership section, contact, reviews and a footer

      </div>

    
   
          </v-overlay>
        </v-fade-transition>
      
    </v-img>
    <v-card-title class="text-capitalize">car dealership</v-card-title>

    <v-card-subtitle class="pb-0">
      (html - css - javascript - bootstrap)
    </v-card-subtitle>

   

    <v-card-actions>
       <v-btn
       class="project-btn"
       elevation="0"

        
        
      >
        live demo
      </v-btn>

      <v-btn
       class="project-btn"
       elevation="0"
       href="https://github.com/siddigIbrahim/car-dealership.git"
        
        
      >
        github ripo
      </v-btn>
    </v-card-actions>
    
  </v-card>
    </v-hover >
            </v-col>
                   <v-col cols="12" class="col-md-5 col-lg-4" data-aos="fade-right"
     
     data-aos-easing="linear"
     data-aos-duration="800"
     data-aos-delay="300">
                    <v-hover v-slot="{ hover }">
                        <v-card
                elevation="10"
    class="mx-auto proj-card"
    max-width="370"
  >
    <v-img
      class="white--text align-end"
      height="300px"
      src="../assets/rps.png"
    >
      <v-fade-transition>
          <v-overlay
            v-if="hover"
            absolute
            color="#3bb5e9"
            opacity="1"
          >
             
      <div class="pa-1 d-flex align-start justify-center overlay-div"> A Rock Paper Scissors game made with HTML 
        CSS and Javascript. It can be played by one user against
        a computer function and the game shows winner of the round, scores and the players choices. It also have 
        simple animations

      </div>

    
   
          </v-overlay>
        </v-fade-transition>
    </v-img>
    <v-card-title class="text-capitalize">rock paper scissor game</v-card-title>

    <v-card-subtitle class="pb-0">
      (html - css - javascript)
    </v-card-subtitle>



    <v-card-actions>
         <v-btn
       class="project-btn"
       elevation="0"
       href="https://siddigibrahim.github.io/rock-paper-scissors/"
        
        
      >
        live demo
      </v-btn>

      <v-btn
       class="project-btn"
       elevation="0"
        href="https://github.com/siddigIbrahim/rock-paper-scissors.git"
        
      >
        github ripo
      </v-btn>
    </v-card-actions>
  </v-card>

                    </v-hover>
                
            </v-col>
    <v-col cols="12" class="col-md-5 col-lg-4" data-aos="fade-right"
     
     data-aos-easing="linear"
     data-aos-duration="800"
     data-aos-delay="600">
        <v-hover v-slot="{ hover }">
              <v-card
    class="mx-auto proj-card"
    elevation="10"
    max-width="370"
  >
    <v-img
      class="white--text align-end"
      height="300px"
      src="../assets/streaming.png"
    >
    <v-fade-transition>
          <v-overlay
            v-if="hover"
            absolute
            color="#3bb5e9"
            opacity="1"
          >
             
      <div class="pa-1 d-flex align-start justify-center overlay-div">
       A streaming website that uses imdb-api to search, and show details of movies and tv shows.
       it consist of different routes and UI elemants and API calls. 

      </div>

    
   
          </v-overlay>
        </v-fade-transition>
      
    </v-img>
    <v-card-title class="text-capitalize">movie app</v-card-title>

    <v-card-subtitle class="pb-0">
      (html - css - javascript - vuejs/router - vuetify - API)
    </v-card-subtitle>


    <v-card-actions>
         <v-btn
       class="project-btn"
       elevation="0"
       href="https://siddigibrahim.github.io/streaming/"
        
        
      >
        live demo
      </v-btn>

      <v-btn
       class="project-btn"
       elevation="0"
        href="https://github.com/siddigIbrahim/streaming.git"
        
      >
        github ripo
      </v-btn>
    </v-card-actions>
  </v-card>
        </v-hover>
              
            </v-col>
          
        </v-row>
    </v-container>
    
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.project-title {
  text-transform: capitalize;
  font-weight: 800;
  color: #fc1600;
}
.project-title span {
  color: #3bb5c9;
  font-weight: 800;
  
}
.project-container {
  min-width: 100%;

  margin: 0;
}
.tech-row {
  min-width: 100%;
}
.proj-card {
  height: 450px;
}
.overlay-div{
    height: 300px !important;
    padding: 2rem !important;
    background-color: #3bb5c9 !important;
    font-size: 1.2rem;
}

.project-btn{
background-color: white !important;
font-size: 1rem;
color: #fc1600 !important;
border: solid 1px #fc1600;
text-transform: capitalize;
    border-radius: 0;
    transition: all 0.5s ease-in-out;
   
}
.project-btn:hover{
     background-color: #fc1600 !important;
    color: white !important;
}
</style>