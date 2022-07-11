<template>
  <div id="about" class="pt-16 main">
    <h1 class="about-title text-h4 text-sm-h3 text-md-h2 ml-5 mb-10"
    data-aos="fade-right"
     
     data-aos-easing="linear"
     data-aos-duration="800"
    
    >about <span  class="text-h3 text-sm-h2 text-md-h1 ">m</span>e</h1>
    <div class="image-holder" data-aos="zoom-out"
    data-aos-easing="linear"
     data-aos-duration="800"
    
    
     >
        <div class="img-div" >
            <img src="../assets/me2.jpg" >
        </div>
        
    </div>
    <div class="intro mt-10 mx-5 text-subtitle-1 text-sm-h5 text-md-h5">
        <p>Hi! My name is<span class="name-span"> siddig ibrahim.</span> I am a junior Front end Devloper, aspiring to achieve excellence
        in my work. Fueled by the passion and dedication to learning and implementing new technologies to further improve
        my self as well as my clinets experience and bussinesses. </p>
    </div>
    <v-container fluid>
         <v-row>
        <v-col cols="12" class="col-md-6"
     >
             <v-list flat disabled>
     
      <v-list-item-group
       
        
      >
       <v-list-item
          
        >
          <v-list-item-icon>
            <v-icon large color="#fc1600">mdi-account</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title class="text-capitalize text-h6 black--text">full name: 
                <span class="text-capitalize text-subtitle-2 black--text">
                 siddig mohammed alsiddig ibrahim</span></v-list-item-title>
            
            
          </v-list-item-content>
        </v-list-item>
        <v-list-item
          
        >
          <v-list-item-icon>
            <v-icon large color="#fc1600">mdi-gift</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title class="text-capitalize text-h6 black--text" > birthday: <span class="text-capitalize text-subtitle-2 black--text"> 09/03/1997</span></v-list-item-title>
            
            
          </v-list-item-content>
        </v-list-item>
         <v-list-item
          
        >
          <v-list-item-icon>
            <v-icon large color="#fc1600">mdi-map-marker</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title class="text-capitalize text-h6 black--text" > location: 
                <span class="text-capitalize text-subtitle-2 black--text"> khartoum, sudan</span></v-list-item-title>
            
            
          </v-list-item-content>
        </v-list-item>
         
        
      </v-list-item-group>
    </v-list>
            
        </v-col>
        <v-col cols="12" class="col-md-6" 
     >
               <v-list flat disabled>
     
      <v-list-item-group
       
        
      >
       
         <v-list-item
          
        >
          <v-list-item-icon>
            <v-icon large color="#fc1600">mdi-school</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title class="text-capitalize text-h6 black--text" > study: 
                <span class="text-capitalize text-subtitle-2 black--text"> sudan university of science and technolog</span></v-list-item-title>
            
            
          </v-list-item-content>
        </v-list-item>
         <v-list-item
          
        >
          <v-list-item-icon>
            <v-icon large color="#fc1600">mdi-book-open-page-variant</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title class="text-capitalize text-h6 black--text" > degree: <span class="text-capitalize text-subtitle-2 black--text">
                 bachelor</span></v-list-item-title>
            
            
          </v-list-item-content>
        </v-list-item>
         <v-list-item
          
        >
          <v-list-item-icon>
            <v-icon large color="#fc1600">mdi-email</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title class="text-capitalize text-h6 black--text" > email: 
                <span class="text-capitalize text-subtitle-2 black--text">
                 siddigi015@gmail.com</span></v-list-item-title>
            
            
          </v-list-item-content>
        </v-list-item>
        
      </v-list-item-group>
    </v-list>



        </v-col>
    </v-row>
    <v-row>
        <v-col cols="12" class="d-flex justify-center mt-10 white--text" data-aos="fade-up"
     
     data-aos-easing="linear"
     data-aos-duration="800">
            <v-btn  class="about-btn" elevation="0"> <a href=""></a> download CV</v-btn>
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


img{
    width: 300px;
    height: 300px;
    border: solid 3px #3BB5E9;
    padding: 0.5rem;
    border-radius: 50%;
    position: relative;
    
}
.about-title span{
  color: #3bb5c9;
  font-weight: 800;

}

.img-div::before{
    content: '';
    position: absolute;
    
    top: 0;
    left: 0;


    width: 100%;
    height: 100%;
    background-color: transparent;
    border-radius: 50%;
    border: dashed 5px #fc1600;
    

    animation: rotating 5s infinite linear;
  
}
.img-div{
    position: relative;
    width: 320px;
    height: 320px;
       display: flex;
    justify-content: center;
    
    align-items: center;


}
.image-holder{
    display: flex;
    justify-content: center;
    
    align-items: center;
    
    
}
.name-span{
    color: #fc1600;
    text-transform: capitalize;
}
.about-title{
    text-transform: capitalize;
    font-weight: 800;
    color: #fc1600;
    
}
.about-btn{
background-color: white !important;
font-size: 1.2rem;
color: #fc1600 !important;
border: solid 1px #fc1600;
text-transform: capitalize;
    border-radius: 0;
    transition: all 0.5s ease-in-out;
   
}
.about-btn:hover{
     background-color: #fc1600 !important;
    color: white !important;
}
@keyframes rotating {
    from{
        transform: rotate(0deg);
    }
    to{
        transform: rotate(359deg);
    }
    
}

</style>