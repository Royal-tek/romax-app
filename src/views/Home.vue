<template>
  <div class="home my-5 py-5">
    <!-- <section id="landing"> -->
      <div class="container-fluid" style="height:100vh;">
        <div class="row left-part">
          <div class="col-6" style="height:100%">

          </div>
          <div class="col-6" style="background-color:rgb(235,133,16);">
            <div class="right-part  text-white p-5">
              <div class="mb-2" >
              <h1 class="py-2" style="font-weight: bold; text-transform: capitalize; font-size: 60px;">Luxury real estate:</h1>
              <h2 class="py-2" style="font-weight: bold; text-transform: capitalize; font-size: 40px;">Redefined.</h2>
              </div>
              <p class="py-2" style="font-weight: 800; color: white; font-size: 20px;">At Romax Properties we specialise in the development of residential buildings with the aim to construct luxury homes in cozy and functional estates so as to curb the housing deficit in Lagos and its environments.</p>
              <router-link to="/about" class="btn more-btn p-2 my-4"><span>More About Us</span></router-link>
            </div>
          
          </div>
        </div>
      </div>
    <!-- </section> -->
  </div>
</template>

<script>



export default {
  name: 'Home',

}
</script>

<style lang="scss" scoped>
  *{
    margin: 0 ;
    padding: 0 ;
    box-sizing: border-box !important;
}
  .left-part{
    background-image: url(../assets/images/1.jpg);
    height: 100%;
    width: 100%;
    background-size: cover;
    background-attachment: fixed;
    background-position: center;
  }
  .right-part{
    display: flex;
    // align-items: center;
    justify-content: center;
    flex-direction: column;
    height: 100%;
  
  }
  .more-btn{
    background-color: black;
    color: #fff;
    // width: 50%;
    
    &:hover{
      background-color: rgb(21, 21, 21);
    }
  }

@media (max-width:700px){
  .right-part{
    padding: 10px !important;
    h1{
      font-size: 30px !important;
    }
    h2{
      font-size: 22px !important;
    }
    p{
      font-size: 15px !important;
    }
    .more-btn{
      padding: 2px !important;
      font-size: 14px;
    }
    
  }
}

</style>