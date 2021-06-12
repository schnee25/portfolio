<template>
  <div class="container">
    <AppNameHeader></AppNameHeader>

    <div class="body">
      <div class="main">
        <div class="worksmeisi">
          <div class="worksimg"><img src="~/assets/screanshot-meisi.png" class="workss" /></div>
          <h1>名刺案</h1>
        </div>

        <div class="explanation">
          <div class="excomponent">
            <h2 class="subtitle">概要</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="extxt">
              <p>名刺っぽいものが作りたかったので<span>イラレの練習を兼ねて作成</span></p>
              <p>背景の写真は自分で撮影･現像･編集を行いました。</p>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">作成期間</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div>
              <p class="skilltxt">約3時間</p>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">使用ツール</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="skillitems">
              <div class="usedskill">
                <div class="logo">
                  <!-- <img src="~/assets/HTML-Logo.png" class="skilliconimg" /> -->
                </div>
                <p class="skilltxt">&ensp;illustrator</p>
              </div>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">作成の際に意識した点</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="extxt">
              <p>
                書きます。
                <!-- 書く -->
              </p>
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
export default {}
</script>

<style>
.body {
  font-family: 'Kiwi Maru', serif;
  min-height: calc(100vh - 150px);
}

.worksmeisi {
  display: inline-block;
  margin: 3% 0 1% 0;
  width: 100vw;
  text-align: center;
}

.workss {
  max-width: 250px;
  max-height: 250px;
  margin-bottom: 2%;
}
h1 {
  font-size: 130%;
  font-weight: normal;
}

p {
  text-align: left;
}
h2 {
  margin-left: 2%;
}
.subtitle {
  display: flex;
  font-size: 110%;
  font-weight: normal;
  justify-content: center;
  width: 180px;
}

.separation {
  font-weight: bold;
  padding: 0% 2% 0% 2%;
}
.extxt {
  text-align: left;
}

.excomponent {
  display: flex;
  margin: 2% 0% 2% 0%;
}
.skilltxt {
  text-align: left;
  display: inline-block;
}
.usedskill {
  display: inline-flex;
}

.skilliconimg {
  max-width: 21px;
  max-height: 21px;
}
.logo {
  height: 21px;
  width: 21px;
  display: inline-block;
}
.udedskill {
  display: inline-block;
}

.skillitems {
  display: flex;
  flex-direction: column;
}

.border {
  display: block;
}
</style>
