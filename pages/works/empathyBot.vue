<template>
  <div class="container">
    <AppNameHeader></AppNameHeader>

    <div class="body">
      <div class="main">
        <div class="worksEmpathyBot">
          <div class="worksimg">
            <img src="~/assets/empathyBotss.png" class="workss" />
            <img src="~/assets/empathyBotQR.png" class="qrCode" />
          </div>
          <h1>共感Bot</h1>
        </div>

        <div class="explanation">
          <div class="excomponent">
            <h2 class="subtitle">概要</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="extxt">
              <p>
                知人に病みLINEを送ったら<span
                  >自分は共感Botではないので共感が欲しいなら他をあったてくれ</span
                >
              </p>
              <p>と言われ、病んだ勢いで自分で作りました。</p>
              <p>共感してくれるBotです</p>
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
              <div class="exskill">
                <div class="logo">
                  <img src="~/assets/js-Logo.png" class="skilliconimg" />
                </div>
                <p class="skilltxt">&ensp;JavaScript　</p>
              </div>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">作成の際に意識した点</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="extxt">
              <p>初めてLineBotを作ったので難しかったです。</p>
              <p>まだ語彙があまりないのでもっとおしゃべりできる子にしていきたいです</p>
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

.workEmpathyBot {
  display: inline-block;
  margin: 3% 0 1% 0;
  width: 100vw;
  text-align: center;
}

.worksimg {
  margin-top: 6px;
  text-align: center;
}
.workss {
  max-width: 250px;
  max-height: 250px;
  margin-bottom: 2%;
  margin-right: 7px;
}
.qrCode {
  max-width: 100px;
  max-height: 100px;
  margin-bottom: 85px;
  margin-left: 7px;
}

h1 {
  font-size: 130%;
  font-weight: normal;
  text-align: center;
}

p {
  text-align: left !important;
  /* これあんまり良くないので直す */
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
