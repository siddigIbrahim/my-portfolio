<template>
  <div class="main pt-16 " id="tech">
    <h1 class="tech-title text-h4 text-sm-h3 text-md-h2 ml-5 mb-10" data-aos="fade-right"
     
     data-aos-easing="linear"
     data-aos-duration="800"
    >technologies i <span  class="text-h3 text-sm-h2 text-md-h1 ">u</span>se</h1>
    <v-container class="tech-container">
        <v-row class="tech-row d-flex justify-space-around align-center">
            <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-language-html5</v-icon>
            </v-col>
             <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-language-css3</v-icon>
            </v-col>
             <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-language-javascript</v-icon>
            </v-col>
             <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-vuejs</v-icon>
            </v-col>
             <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-vuetify</v-icon>
            </v-col>
             <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-bootstrap</v-icon>
            </v-col>
             <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-git</v-icon>
            </v-col>
             <v-col cols="3" class="col-md-2 col-lg-1">
                <v-icon color="#3bb5e9" size="80">mdi-github</v-icon>
            </v-col>
        </v-row>
    </v-container>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.main{
  margin-bottom: 10rem;
}
.tech-title{
    text-transform: capitalize;
    font-weight: 800;
    color: #fc1600;
    
}
.tech-title span{
  color: #3bb5c9;
  font-weight: 800;
}




</style>