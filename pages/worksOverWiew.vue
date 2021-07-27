<template>
  <div class="container">
    <div class="header">
      <AppNameHeader></AppNameHeader>
    </div>

    <div class="body">
      <div class="main">
        <div class="workstitle"><h1>Works</h1></div>
        <div class="works">
          <div class="programing">
            <div class="web">
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
          </div>
          <div class="imageEdit">
            <!-- <div class="worksportpolio">
              <router-link to="/works/meisi" class="nonboder">
                <div class="ssimg"><img src="~/assets/screanshot-meisi.png" class="workss" /></div>
                <p>名刺案</p>
              </router-link>
            </div> -->
            <!-- <div class="photo">
              <router-link to="/works/" class="nonboder">
                <div class="ssimg"><img src="~/assets/plum.jpg" class="workss" /></div>
                <p>趣味で撮った写真</p>
              </router-link>
            </div> -->
          </div>
          <div>
            <div class="photo"></div>
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
export default {}

import AppNameHeader from '../components/AppNameHeader.vue'
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
.nonboder {
  text-decoration: none;
}
h1 {
  width: 100vw;
  text-align: center;
  margin: 15px 0 10px 0;
  font-size: 1.3em;
}
.works {
  display: flex;
  justify-content: space-evenly;
  flex-direction: column;
}
/* img {
  margin-left: auto;
  margin-right: auto;
  text-align: center;
} */
.workscontents {
  padding-top: 3%;
  margin: 0 auto;
  margin-top: 2%;
  text-align: center;
}
.worksportpolio,
.worksdebateq,
.empathyBot,
.photo {
  display: inline-block;
  margin: 3% 3% 1% 3%;
  width: 25vw;
  text-align: center;
}
p {
  text-align: center;
}
.workss {
  max-width: 250px;
  max-height: 250px;
  margin-bottom: 2%;
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

.excomponent{
  display: flex;
  margin: 2% 0% 2% 0%;
} */
</style>
