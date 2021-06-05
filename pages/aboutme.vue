<template>

  <div class="container">
    <AppNameHeader></AppNameHeader>

    <div class="body">
        <div class="main">
          <div class="cvtitle"><h1>Curriculum Vitae</h1></div>

          <div class="biocontents">

                <div class="excomponent">
                    <h2 class="subtitle">Name</h2>
                        <div class="separation"><p>:&ensp;</p></div>
                    <div class="extxt">
                        <p>小山田 雪乃</p> 
                    </div>
                </div>

                <div class="excomponent">
                    <h2 class="subtitle">Birth</h2>
                        <div class="separation"><p>:&ensp;</p></div>
                    <div class="extxt">
                        <p>2000.12.26</p> 
                    </div>
                </div>

                <div class="excomponent">
                    <h2 class="subtitle">Academic background</h2>
                        <div class="separation"><p>:&ensp;</p></div>
                    <div class="extxt">
                        <p>2019  熊本高校 卒業</p>
                        <p>2020  立教大学 法学部法学科 入学</p>
                        <p>2021  立教大学 法学部法学科 在籍</p>   
                    </div>
                </div>
            
          </div>
          

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

</script>

<style>
.body {
  font-family: 'Kiwi Maru', serif;
  min-height: calc(100vh - 150px);
}
.cvtitle{
  width: 100vw;
  text-align: center;
  margin: 15px 0 10px 0;
  font-size: 1.3em;
  
}
h1 {
  font-size: 130%;
  font-weight: normal;
}


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
}

.border {
  display: block;
}



</style>