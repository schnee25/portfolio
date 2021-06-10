<template>

  <div class="container">
    <AppNameHeader></AppNameHeader>

    <div class="body">
        <div class="main">
          <div class="workstitle"><h1>Works</h1></div>

            <div class="works"></div>
          

        </div>
    </div>

    
    <div class="footer">
      <AppFooter></AppFooter>
    </div>

  </div>

</template>

<script>
export default {
}

import AppNameHeader from '../components/AppNameHeader.vue';
components: {
  AppNameHeader
}

import AppFooter from '../components/AppFooter'
components: {
  AppFooter
}

</script>

<style scoped>
.body {
  font-family: 'Kiwi Maru', serif;
  min-height: calc(100vh - 150px);
}
.border {
  display: block;
}
h1 {
  width: 100vw;
  text-align: center;
  margin: 15px 0 10px 0;
  font-size: 1.3em; 
}



/* 
.subtitle {
  display: flex;
  font-size: 110%;
  font-weight: normal;
  justify-content: center;
  width: 180px;
  text-align: center;
}
.separation{
  font-weight: bold;
  padding: 0% 2% 0% 2%;
}
.extxt{
  text-align: left;
}
p{
  text-align: left;
}
.excomponent{
  display: flex;
  margin: 2% 0% 2% 0%;
} */




</style>