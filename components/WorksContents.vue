<template>
  <div class="workscontents">
    <div class="workstitle">
      <h1>- works -</h1>
    </div>
    <div class="workscomponent">
      <div class="worksportpolio">
        <router-link to="/works/portforio" class="nonboder">
          <img src="~/assets/screanshot-portfolio.jpg" class="workss" />
          <p>ポートフォリオ</p>
        </router-link>
      </div>

      <div class="worksdebateq">
        <router-link to="/works/debateq" class="nonboder">
          <img src="~/assets/screanshot-debateq.jpg" class="workss" />
          <p>ディベート甲子園九州大会サイト</p>
        </router-link>
      </div>

      <div class="empathyBot">
        <router-link to="/works/empathyBot" class="nonboder">
          <img src="~/assets/empathyBotss.png" class="workss" />
          <p>共感Bot</p>
        </router-link>
      </div>
    </div>

    <div>
      <router-link to="/worksOverWiew" class="nonboder">
        <p class="exactly">&#x1f449; More information</p>
      </router-link>
      <!-- ↑ 詳しいページ作る？リンクに -->
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.workscontents {
  padding-top: 3%;
  margin: 0 auto;
  margin-top: 2%;
  text-align: center;
}
.worksportpolio,
.worksdebateq,
.empathyBot {
  display: inline-block;
  margin: 3% 3% 1% 3%;
}

.workss {
  max-width: 250px;
  max-height: 250px;
  margin-bottom: 2%;
}
.ssimg {
  min-height: 200px;
  min-width: 250px;
}
.exactly {
  margin-top: 10px;
}
</style>
