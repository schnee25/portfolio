<template>
  <div class="container">
    <div class="header">
      <div class="profile">
        <router-link to="/aboutme" class="nonboder">
            <div class="icon"><img src="~/assets/redyPortfolio.jpeg" /></div>
            <p class="iconsub">CV</p>
        </router-link>
        
      </div>
      <div class="works">
        <div class="icon"><img src="~/assets/goodjobIcon.jpeg" /></div>
        <p>works</p>
      </div>

      
      <div class="title"><a href="/" class="home"><p>yukipedia</p></a></div>
      
      
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
export default {
  data(){
    return {
      isOpen: false,
    }
  },
  methods: {
    hello(){

    },
    seeyou(){

    }
  }
}
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
  margin: 15px 60px 10px 60px;
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
  text-align: center;
  color: #000;
  text-decoration:none; 
}
.border {
  display: block;
}

.home:hover{
  color: #000;
}

.home{
  text-decoration:none; 
  font-size: 25px;
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
