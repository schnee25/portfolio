<template>
      <div class="workscontents">
        <div class="workstitle"><h1>- works -</h1></div>
          <div class="workscomponent">

          <div class="worksportpolio">
            <img src="~/assets/screanshot-portfolio.jpg" class="workss"/>
            <router-link to="/works.portforio">
            <p>ポートフォリオ</p>
            </router-link>
          </div>
          
          <div class="worksdebateq">
            <img src="~/assets/screanshot-debateq.jpg" class="workss"/>
            <router-link to="/works-debateq">
            <p>ディベート甲子園九州大会サイト</p>
            </router-link>
           
          </div>
      
        </div>    
      </div>
</template>

<script>
export default {
}
</script>

<style>
.workscontents {
    padding-top: 3%;
    margin: 0 auto;
    margin-top: 2%;
    text-align: center;
}
.worksportpolio,.worksdebateq{
  display: inline-block;
  margin: 1% 3% 1% 3%;
}

.workss{
   max-width: 250px;
   max-height: 250px;
   margin-bottom: 2%;
}

</style>