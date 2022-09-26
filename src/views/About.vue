<template>
  <div class="about mt-5 py-5">
    <div class="container">
      <h1 class="text-center text-capitalize mt-4" style="font-weight: bold; font-size: 50px; ">Romax properties limited</h1>
      <p class="text-center mt-4" style="font-weight: bold; width: 65%; margin: 0 auto; font-size: 19px;">We are a front-line real estate development and management company located in Lagos metropolis, the commercial hub of Nigeria with over sixteen years’ experience in delivering premium quality homes to hundreds of clients  in search of style, comfort and value.</p>
    
    <div class="video  my-5">
      <iframe width="100%" height="100%" src="https://www.youtube.com/embed/K6N_FeVyQec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

    <div class="rem-text">
    <h1 class="text-center text-capitalize about-text" style="font-weight: bold; font-size: 50px; ">about us</h1>
    <p class=" mt-4" style="font-weight: bold; width: 80%; margin: 0 auto; font-size: 19px; text-align: justify;">
    Romax Property Limited is a highly reputable company that has been delivering exceptional real estate development and management services in Lagos Metropolis for over 16 years. Our company was founded in 2005 by Chief Ugochukwu Orji with the aim to construct premium homes in cozy and functional estates so as to curb the housing demand in Lagos and its environments. As one of the top Realty in the City, we have created a competitive edge for investors, buyers, and sellers by prioritizing their needs.
    </p>

    <p class=" mt-4" style="font-weight: bold; width: 80%; margin: 0 auto; font-size: 19px; text-align: justify;">
      We have built a strong team of professional architects, engineers, site managers, lawyers, and marketers who place a premium on customer satisfaction over quick results. With specialization in new construction, sales, property management, valuation, and interior building works, we are always available to ensure that clients achieve their goals. We understand the dynamics that inspire people to invest in a quality home and how personal each decision is. Therefore, our focus as a company is on creating real estate solutions that work best for our clients and add tangible value across property sectors. In recognition of our drive for exemplary work, we have delivered premium quality homes to hundreds of clients in need of class, comfort, and exclusivity.
    </p>

    <p class=" mt-4" style="font-weight: bold; width: 80%; margin: 0 auto; font-size: 19px; text-align: justify;">
      Through our deep understanding of the market, latest technology, and the changing trends, we guide clients to achieve the best results in this fast-transitioning industry. Whether you are a buyer or seller, you will appreciate our integrity, competence, and proven ability to provide personalised, clear, and well-researched advice on real estate in Lagos.
    </p>
    
  </div>

  
    </div>
    <div class="over my-5 py-5">
    <div class="container">
      <h3 class="text-center text-capitalize text-white" style="font-weight: bold;">Build your dream home</h3>
      <h1 class="text-center text-capitalize text-white" style="font-weight: bold;">visit our projects today</h1>
    </div>
  </div>

  </div>
</template>

<script>
export default {
  name : 'About',

}
</script>

<style lang="scss" scoped>
.video{
  height: 50vh;
  background-color: rgb(235,133,16);
}
.about-text::after{
  margin: 10px auto;
  content: '';
  background-color: rgb(235,133,16);
  display: block;
  height: 5px;
  width: 50px;
}
// .rem-text{
//   margin-top: 100px;
// }
.over{
  width: 100%;
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url(../assets/images/7.jpg);
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
  height: 40vh;
  display: flex;
  align-items: center;
}
</style>