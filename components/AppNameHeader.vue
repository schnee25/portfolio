<template>
  <div class="container">
    <div class="header">
      <div class="profile">
        <div class="icon"><img src="~/assets/redyPortfolio.jpeg" /></div>
        <p class="iconsub">about</p>
      </div>
      <div class="works">
        <div class="icon"><img src="~/assets/goodjobIcon.jpeg" /></div>
        <p>works</p>
      </div>

      <router-link to="/" class="Home">
      <div class="title"><p>yukipedia</p></div>
      </router-link>
      
      <div class="skill">
        <div class="icon"><img src="~/assets/penIcon.jpeg" /></div>
        <p>skill</p>
      </div>
      <div class="contact">
        <div class="icon"><img src="~/assets/comentIcon.jpeg" /></div>
        <p>contact</p>
      </div>
    </div>
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
img {
  max-width: 40px;
}
.icon {
  height: 40px;
  width: 40px;
  margin: auto;
}
.iconsub {
  margin-top: 0px;
}
.border {
  display: block;
}

.Home:hover{
  color: #000;
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
