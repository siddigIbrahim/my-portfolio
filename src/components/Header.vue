<template>
<div class=" main">
    
        <nav>
              <div class="navbar-div">
             <b-navbar toggleable="lg">
    <b-navbar-brand class="nav-brand" href="#" >SID.
    </b-navbar-brand>
    
    <b-navbar-toggle target="nav-collapse" class="nav-btn"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="navbar-nav" >
        <b-nav-item class="nav-list" href="#about">about</b-nav-item>
        <b-nav-item class="nav-list" href="#tech">skills</b-nav-item>
        <b-nav-item class="nav-list" href="#projects">my projects</b-nav-item>
        <b-nav-item class="nav-list" href="#contact">contact</b-nav-item>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>

        </div>


        </nav>
              
         <header>
        <div class="header pl-3">
            
             <p class="animate__animated animate__slideInRight text-capitalize text-h3 text-sm-h2 text-md-h1 ">hello there,</p>
             <p class="animate__animated animate__slideInLeft text-capitalize text-h5 text-sm-h4 text-md-h3">i'm</p>
              
              <p class="animate__animated animate__slideInRight text-capitalize text-h3 text-sm-h2 text-md-h1 ">siddig ibrahim .</p>
              <p class="animate__animated animate__slideInLeft text-capitalize text-h5 text-sm-h4 text-md-h3">a front-end devloper</p>
              
            

            
           
        </div>
        
           

    </header>
    

    
   

</div>
 
    
    

</template>

<script>
export default {
    data() {
        return{
          
        }
    },
  
   

}
</script>

<style scoped>
.navbar-div{
    width: 100%;
    background-color: rgb(255, 255, 255);
    padding: 0rem 1rem;
    position: fixed;
    transition: all 0.5s ease-in-out;
    z-index: 9;
    box-shadow: 0px 0px 2px 2px rgba(0, 0, 0, 0.2);
}
.navbar-nav{
    margin: 0;
    color: white !important;
    
}
.nav-btn{
    
    border: none !important;
}
.nav-brand{
      color: #FC1600 !important;
    font-weight: 700;
    font-size: 2rem;

}
.main{
    overflow-x: hidden;
}
.nav-list{
    
    text-transform: capitalize;
    font-weight: 500;
    transition: all 0.5s ease-in-out;
    margin-left: 1rem;
    padding: 0rem 1rem;
    color: #ffffff;
    
}

.nav-list:hover{
    background-color: #FC1600;
    
}



.header{
    height: 100vh;
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('../assets/x7.jpg');
    background-position: center;
    background-size: cover;
    color: #ffffff;
    display: flex;
   
    justify-content: center;
    flex-direction: column;
}
.animate__animated.animate__backInLeft {
  --animate-duration: 2s;
}
p:nth-of-type(1){
    animation-delay: 0.3s;
    /* font-size: 4rem; */
    color: #3BB5E9;
    font-weight: 700;
    margin: 0;
}
p:nth-of-type(2){
    animation-delay: 0.6s;
    
     font-weight: 700;
     margin: 0;
     margin-top: 1rem;
     margin-left: 4rem;
   
}
p:nth-of-type(3){
    animation-delay: 1.2s;
    
    color: #3BB5E9;
    font-weight: 700;
    margin: 0;
  
}
p:nth-of-type(4){
    animation-delay: 1.5s;
   
     font-weight: 700;
     margin: 0;
     margin-top: 1rem;
     margin-left: 2rem;
   
}



</style>