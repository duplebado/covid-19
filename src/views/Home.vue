<template>
  <div id="home_container">
       <div id="news_flash">
         <p><span><h6>FEDERAL GOVERNMENT DECLARES TWO WEEKS LOCKDOWN STARTING ON 31/03/2020 TO FIGHT CORONA</h6></span></p>
      </div>

    <div id="bckgrd_image" >
    </div>

    <div id="left_container">
      <h5>COVID-19 STATS IN NIGERIA (06/04/2020) </h5>
      <Table/>
    </div>

    <div id="right_container">
      <Slider/>
    </div>

    <div id="contact_us">
      <h3>ARE YOU EXPERIENCING ANY COVID-19 SYMPTOMS?</h3> <hr>

      <h5>Don't panic, contact NCDC (NATIONAL CENTER FOR DISEASE CONTROL)</h5>

      <ul>
        <li>Toll Free Number: 0800 9700 0010</li>
        <li>Whatsaap: +234708 711 0839</li>
        <li>SMS: +234809 955 5577</li>
      </ul>
    </div>
  </div>     
</template>

<script>
import Table from '../components/Table.vue'
import Slider from '../components/Slider'
export default {
    name: 'Home',
    components: {
      Table,
      Slider
    }
}
</script>

<style scoped>
#home_container{
  /* background-color: yellow; */
  position: relative;
  margin-top: 99px;
  width: 99.4%;
  height: 455px;

}
#bckgrd_image{
  background-image: url('../assets/Coronavirus-CDC-645x645.jpg');
  /* background-color: purple; */
  opacity: 0.2;
  width: 100%;
  height: 725px;
}

#left_container{
  /* float: left; */
  margin-top: 32px;
  margin-left: 10px;
  width: 390.5px;
  height: 300px;
  /* opacity: 0.8; */
  background-color: rgb(230,236,240, 0.4);
  position: absolute;
  top: 0;
  left: 0;
}

#right_container{
  margin-top: 32px;
  margin-left: 10px;
  width: 900px;
  height: 400px;
  position: absolute;
  top: 0;
  right: 0;
}
#news_flash{
  position: fixed;
  padding-top: 8px;
  top:-3.7px;
  left: 10;
  margin-top: 100px;
  margin-left: 8px;
  background-color: whitesmoke;
  width:1300px;
  height: 30px;
  z-index: 1500;
}
  span{
  position: relative;
  color:palevioletred;
  animation-name: leftToRight;
  animation-duration: 20s;
  animation-iteration-count: infinite;
}

@keyframes leftToRight {
  0%   { left:0px; top:0px;}
  50%  {left:465px; top:0px;}
  99% {left:0px; top:0px;} 
}

#contact_us{
  background-color: rebeccapurple;
  background-color: rgb(230,236,240, 0.3);
  width: 900px;
  height: 205px;
  position: absolute;
  top: 545px;
  right: 0;

}
</style>