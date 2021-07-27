<template>
  <div class="container">
    <AppNameHeader></AppNameHeader>

    <div class="body">
      <div class="main">
        <div class="worksdebateq">
          <div class="worksimg"><img src="~/assets/screanshot-debateq.jpg" class="workss" /></div>
          <h1>ディベート甲子園九州大会サイト</h1>
        </div>

        <div class="explanation">
          <div class="excomponent">
            <h2 class="subtitle">概要</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="extxt">
              <p>
                ディベート甲子園とは毎年夏に行われる、全国の中学校・高校の競技ディベート日本一を決める大会です。
              </p>
              <p>2021年度オンラインでの開催になってしまったため、</p>
              <p>
                スタッフとしてお手伝いさせていただいている九州支部で行われる大会で使用するためにこちらのサイトを作成しました。
              </p>
              <p>初めて1から作ったのがこのページです。</p>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">URL</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div>
              <p class="skilltxt">https://portalnadeq.herokuapp.com/</p>
              <p class="skilltxt">https://nade9portal-for-pc.herokuapp.com/</p>
              <p>途中で仕様変更があり2個作成</p>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">作成期間</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div>
              <p class="skilltxt">約2週間</p>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">使用言語･ツール</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="skillitems">
              <div class="usedskill">
                <div class="logo">
                  <img src="~/assets/HTML-Logo.png" class="skilliconimg" />
                </div>
                <p class="skilltxt">&ensp;HTML</p>
              </div>

              <div class="usedskill">
                <div class="logo">
                  <img src="~/assets/CSS-Logo.png" class="skilliconimg" />
                </div>
                <p class="skilltxt">&ensp;CSS</p>
              </div>

              <div class="usedskill">
                <div class="logo">
                  <img src="~/assets/js-Logo.png" class="skilliconimg" />
                </div>
                <p class="skilltxt">&ensp;JavaScript</p>
              </div>

              <div class="usedskill">
                <div class="logo">
                  <img src="~/assets/Git-Logo.png" class="skilliconimg" />
                </div>
                <p class="skilltxt">&ensp;git</p>
              </div>

              <div class="usedskill">
                <div class="logo">
                  <img src="~/assets/VisualStudioCode-Logo.png" class="skilliconimg" />
                </div>
                <p class="skilltxt">&ensp;Visual Studio Code</p>
              </div>
            </div>
          </div>

          <div class="excomponent">
            <h2 class="subtitle">ひとこと</h2>
            <div class="separation"><p>:&ensp;</p></div>
            <div class="extxt">
              <p>
                ･ メディアクエリを活用したレスポンシブウェブデザイン<span
                  >(スマホを使用する生徒や保護者が想定されるため)</span
                >
              </p>
              <p>
                ･ 上スクロールすると出現し下スクロールで消えるヘッダー<span>(JSを使って実装)</span>
              </p>
              <p>･ ボタンのデザイン</p>
              <p>･ ホバーエフェクト</p>
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

import AppNameHeader from '../../components/AppNameHeader.vue'
components: {
  AppNameHeader
}
</script>

<style>
.body {
  font-family: 'Kiwi Maru', serif;
  min-height: calc(100vh - 150px);
}

.worksdebateq {
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

/* レスポンシブ */
@media screen and (max-width: 959px) {
  /* 959px以下に適用されるCSS（タブレット用） */
}
@media screen and (max-width: 480px) {
  /* 480px以下に適用されるCSS（スマホ用） */
  .profile,
  .works,
  .skill,
  .contact {
    display: inline-block;
    margin: 3px 10px 3px 10px;
    font-size: 0.65em;
  }
  .title {
    display: inline-block;
    margin: 5px 10px 5px 10px;
    font-size: 1.3em;
    vertical-align: middle; /* 親のheight/line-heightと合わせて使って子を中央揃えに */
  }

  span {
    display: block;
  }
}
</style>
