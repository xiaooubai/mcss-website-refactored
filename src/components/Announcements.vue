<template>
  <div class="events">
    <h1 style="text-align: center; font-size: 30px; font-family: IKEABold;">NEW <span style="font-size: 30px; color: #be0819;">RECRUITS</span></h1>
    <hr class="hr1">
    <div class="event2"><b-img-lazy :src="require('../assets/About/New Recruits Winter 2020.png')" alt="New Recruit Winter 2020" style="border-radius: 7px;" /></div>
    
    <hr class="hr2">
    <div id="sogaeting"><h1 style="text-align: center; font-size: 30px; font-family: IKEABold;">SOGAETING -<span style="font-size: 30px; color: #be0819;"> FEB 14 2020</span></h1></div>
    <hr class="hr1">
    <div class="event2"><b-img-lazy :src="require('../assets/Sogaeting/pic1.jpg')" alt="New Recruit Winter 2020" style="border-radius: 7px;" /></div>
    <div class="event2"><b-img-lazy :src="require('../assets/Sogaeting/pic2.jpg')" alt="New Recruit Winter 2020" style="border-radius: 7px;" /></div>
    <div class="event2"><b-img-lazy :src="require('../assets/Sogaeting/pic3.jpg')" alt="New Recruit Winter 2020" style="border-radius: 7px;" /></div>
    <div class="event2"><b-img-lazy :src="require('../assets/Sogaeting/pic5.jpg')" alt="New Recruit Winter 2020" style="border-radius: 7px;" /></div>
    <div class="event2"><b-img-lazy :src="require('../assets/Sogaeting/pic4.jpg')" alt="New Recruit Winter 2020" style="border-radius: 7px;" /></div>
  </div>
</template>

<script>
export default {
  name: 'announcements',
};
</script>

<style scoped>
  .hr1{
      background-color: #be0819;
      width: 28%;
      height: 1px;
  }

  .event1 img{
    padding: 20px;
    margin-top: 20px;
    margin-left: auto;
    margin-right: auto;
    display: block;
    width: 80%;
    height: auto;
    background-image: url(../assets/sky-background.jpg);
  }

  .event2 img{
    border-radius: 7px;
    margin-top: 20px;
    margin-left: auto;
    margin-right: auto;
    display: block;
    width: 80%;
    height: auto;
  }

  .hr2 {
    margin-top: 3rem;
    margin-bottom: 3rem;
    width: 80%;
    border: 0;
    border-top: 1px solid rgba(0,0,0,.1);
}

</style>