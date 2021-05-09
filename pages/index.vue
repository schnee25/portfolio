<template>
  <div class="container">
    <AppNameHeader></AppNameHeader>
    <hr class="border" />
    <div class="body">
      <div class="main">
        <div class="aboutme">
          <div class="proimg"></div>
          <div class="proftext">
            <h1 class="aboutmetxt">about me</h1>
            <p>名前: 小山田　雪乃</p>
            <p>　　おやまだ ゆきの</p>
            <p>
              2000年12月生まれ。
              <span>熊本県内の公立高校を卒業。</span>
              <span>現在は都内の大学の法学部に在籍。</span>
            </p>
            <p>好きなこと: 食べること🍙</p>
          </div>
        </div>
        <div class="workscomtents">
          <div class="worksportpolio">
            <!-- スクショとリンク貼る -->
            <p>ポートフォリオ</p>
          </div>
        </div>
        <div class="skillcomtents"></div>
        <div class="contactcomtents"></div>
      </div>
    </div>
    <div class="footder"></div>
  </div>
</template>

<script>
import header from '../components/AppNameHeader.vue'
export default {
  components: { header },
}
import AppNameHeader from '../components/AppNameHeader.vue'
components: {
  AppNameHeader
}
</script>

<style>
.container {
  margin: 0 auto;
  display: flex;
  /* justify-content: center; いらんかも*/
  flex-direction: column;
}

.border {
  display: block;
}

.body {
  font-family: 'Kiwi Maru', serif;
}
.aboutme {
  display: flex;
  justify-content: center;
  margin-top: 2%;
}
h1 {
  font-size: 130%;
}

.workscomtents {
}

.skillcomtents {
}

.contactcomtents {
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

  img {
    max-width: 30px;
  }
  .icon {
    height: 30px;
    width: 30px;
    margin: auto;
  }
  span {
    display: block;
  }
}
</style>
