<template>
<div class="main d-flex justify-center align-center" v-if="loading">
 <div class="first pa-1 d-flex justify-center align-center">
    <div class="second pa-1 d-flex justify-center align-center">
        <div class="third pa-1 d-flex justify-center align-center"> 
            <div class="forth white--text d-flex justify-center align-center">
                
            </div>
        </div>
    </div>
  </div>
</div>
 
</template>

<script>
export default {
    data(){
        return{
            loading: true,
        }
    },
    created(){
       setTimeout(() => {
        this.loading = false
        
       }, 10);

    }

}
</script>

<style scoped>
.main{
    
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 999;
    background-color: rgb(255, 255, 255);


}
.first{
    width: 400px;
    height: 400px;
    border: dashed 8px #fc1600;
    border-radius: 50%;
    animation: rotating 2s infinite linear;
    
}
.second{
     width: 300px;
    height: 300px;
    border: dotted 10px #3bb5e9;
    border-radius: 50%;
    animation: rotating 8s infinite linear;
    

}
.third{
      width: 200px;
    height: 200px;
    border: dashed 8px #fc1600;
    border-radius: 50%;
    animation: rotating 8s infinite linear;
    padding: 3rem;
}
.forth {
    font-weight: 700;
    color: #3bb5e9;
    background-color: #3bb5e9;
    width: 100%;
    height: 100%;
    border-radius: 50%;
    


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