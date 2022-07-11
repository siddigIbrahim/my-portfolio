<template>
   <v-footer
   color="#fc1600"
   class="mt-15"
    
  >
  <v-container>
    <v-row class="d-flex justify-center">
        <v-col cols="12" class="col-sm-8 col-md-6 d-flex justify-space-around">
            <v-icon large class="footer-icon">mdi-linkedin</v-icon>
            <v-icon large class="footer-icon">mdi-github</v-icon>
            <v-icon large class="footer-icon">mdi-email</v-icon>
        </v-col>
    </v-row>
     <v-row class="d-flex justify-center">
        <v-col cols="12" class="col-sm-8 col-md-6 d-flex justify-space-around text-subtitle-1 text-md-h6 mt-3">
            <p class="white--text ">
                 &copy; Designed and Devloped By <span class="footer-span">Siddig Ibrahim</span>



            </p>
            

           
        </v-col>
    </v-row>
  </v-container>
  
  </v-footer>
</template>

<script>
export default {
    data(){
        return{
             icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
        }
    }

}
</script>

<style scoped>
.footer-span{
    color: #3bb5e9;
}
.footer-icon{
    color: white;
    transition: all 0.5s ease-in-out;
    cursor: pointer;

}
.footer-icon:hover{
   color: #3bb5e9 !important;
}
</style>