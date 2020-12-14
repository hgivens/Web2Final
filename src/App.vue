<template>
  <div id="app">
    <Header title= 'Weather Checker'></Header>
    <Weather></Weather>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Weather from './components/Weather.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Weather,
    Footer
  },
  data(){
    return{
      weather: [
        //
      ]
    };
  },
  // mounted(){
  //   axios.get('api.openweathermap.org/data/2.5/weather?zip={zip code},{country code}&appid=8ccc67cbf2fc8f7352903633cb91e4fc')
  //   .then((response) => {
  //     this.weather = response.data.results;
  //   });
  // }
}
</script>

<style>
*{
  margin: 0%;
  padding: 0%;
}
#app{
  background: rgb(169, 169, 226);
}
</style>
