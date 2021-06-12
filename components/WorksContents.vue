<template>
  <div class="workscontents">
    <div class="workstitle">
      <a name="workslink"><h1>- works -</h1></a>
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

      <div class="worksportpolio">
        <router-link to="/works/meisi" class="nonboder">
          <div class="ssimg"><img src="~/assets/screanshot-meisi.png" class="workss" /></div>
          <p>名刺案</p>
        </router-link>
      </div>
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
.worksdebateq {
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
</style>
