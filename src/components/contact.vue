<template>
  <div id="contact" class="main pt-16"> 
     <h1 class="contact-title text-h4 text-sm-h3 text-md-h2 ml-5 mb-10" data-aos="fade-right"
     
     data-aos-easing="linear"
     data-aos-duration="800">contact <span class="text-h3 text-sm-h2 text-md-h1 ">m</span>e</h1>
    <v-container>
        <p class="text-subtitle-1 text-sm-h5 text-md-h5">
            Please fill out the form in this section to contact with me. or call me via phone or reach out by linkedin.
        </p>
        <v-row>
            <v-col cols="12">
                 <v-form
    ref="form"
    v-model="valid"
    lazy-validation
    action="https://formsubmit.co/afa49cf06a9c112744a2699ec8c44f4a" method="POST" 
  >
    <v-text-field
      v-model="name"
      
      :rules="nameRules"
      label="Name"
      name="name"
      required
      
    ></v-text-field>

    <v-text-field
      v-model="email"
      :rules="emailRules"
      label="E-mail"
      name="email"
      required
      
      
    ></v-text-field>
     <v-text-field
     
      v-model="message"
      :rules="messageRules"
      
      height="150"
      name="message"
      label="message"
     
      required
    ></v-text-field>
    



    

   

    <v-btn
      class="form-btn mt-10 px-5"
      elevation="0"
      type="submit"
      
    >
      send 
    </v-btn>
  </v-form>
            </v-col>
        </v-row>
    </v-container>

  </div>
</template>

<script>
export default {
     data (){
        return{
             valid: true,
      name: '',
      nameRules: [
        v => !!v || 'Name is required',
        v => (v && v.length <= 10) || 'Name must be less than 10 characters',
      ],
      email: '',
      emailRules: [
        v => !!v || 'E-mail is required',
        v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
      ],
      message: '',
      messageRules: [
        v => !!v || 'message is required',
        v => (v && v.length <= 10) || 'message must be less than 10 characters',
      ],


        }
    
     }


}
</script>

<style scoped>
.contact-title {
  text-transform: capitalize;
  font-weight: 800;
  color: #fc1600;
}
.contact-title span {
  color: #3bb5c9;
  font-weight: 800;
}
.form-btn{
background-color: white !important;
font-size: 1.3rem;
color: #fc1600 !important;
border: solid 1px #fc1600;
text-transform: capitalize;
    border-radius: 0;
    transition: all 0.5s ease-in-out;
   
}
.form-btn:hover{
     background-color: #fc1600 !important;
    color: white !important;
}

</style>