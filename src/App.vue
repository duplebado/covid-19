<template>
  <div >
    <div id="app">
      <div id='logo'>
        <img src="./assets/Tiide Lab Logo 1.png"  />  <span id="top_text">CORONA VIRUS (COVID-19) INFORMATION DESK</span>
      </div>

      <div id='navbar_div'>
        <Header/>
      </div>
   
      <Home />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Home from './views/Home'

export default {
  name: "app",
  components: {
    Header,
    Home
  }
}
</script>

<style>
#app{
  font-family: Arial, Helvetica, sans-serif;
  margin: auto;
  width: 1316px;
  min-height: 558px;
}
#logo{
  position: fixed;
  background-color: whitesmoke;
  margin-top: -14px;
  float:left;
  width: 96.4%;
  height: 60px;
  top: 0;
  left: 0;
  margin-left: 24.5px ;
  margin-right: 12.5px ;
  z-index:1500;

}
img{
  width: 200px;
  height: 75px;
}
#navbar_div{
  position: fixed;
  width: 96.4%;
  top: 40px;
  left: 0;
  margin-left: 24.5px ;
  margin-right: 12.5px ;
  z-index:1500;

}
#top_text{
  margin-left: 260px;
  font-size: 18px;
  font-weight: bold;
}

</style>
