<template>

  <div class="container">
    <AppNameHeader></AppNameHeader>

    <hr class="border" />


    <div class="body">
      <div class="main">
       
     </div>
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

</script>

<style>
.body {
  font-family: 'Kiwi Maru', serif;
}
.main{
  text-align:center;
}
h1 {
  font-size: 130%;
  font-weight: normal;
}

</style>