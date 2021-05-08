<template>
  <div class="container">
    <div class="header">
      <div class="profile">
        <div class="icon"><img src="~/assets/re.jpeg" /></div>
        <p class="iconsub">about</p>
      </div>
      <div class="works">
        <div class="icon"><img src="~/assets/goodjobIcon.jpeg" /></div>
        <p>works</p>
      </div>
      <div class="title"><p>yukipedia</p></div>
      <div class="skill">
        <div class="icon"><img src="~/assets/penIcon.jpeg" /></div>
        <p>skill</p>
      </div>
      <div class="contact">
        <div class="icon"><img src="~/assets/comentIcon.jpeg" /></div>
        <p>contact</p>
      </div>
    </div>
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
              2000年12月生まれ。熊本県内の公立高校を卒業。現在は都内の大学の法学部に在籍。
            </p>
            <p>好きなこと: 食べること🍙</p>
          </div>
        </div>
      </div>
    </div>
    <div class="footder"></div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  display: flex;
  /* justify-content: center; いらんかも*/
  flex-direction: column;
}

.header {
  font-family: 'Hachi Maru Pop', cursive;
  display: inline-block;
  display: flex;
  justify-content: center;
  align-content: center;

  /* height: 100px;
  line-height: 100px; */
  /* height/line-height -> 子要素の上下を中央揃えにするため */
}

.profile,
.works,
.skill,
.contact {
  display: inline-block;
  margin: 3px 40px 3px 40px;
  /* vertical-align: middle; */
}

.title {
  display: inline-block;
  margin: 10px 60px 10px 60px;
  font-size: 1.3em;
  vertical-align: middle; /* 親のheight/line-heightと合わせて使って子を中央揃えに */
}
.icon {
  height: 50px;
  width: 50px;
  margin: auto;
}
.iconsub {
  margin-top: 0px;
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
    font-size: 0.6em;
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
}
</style>
