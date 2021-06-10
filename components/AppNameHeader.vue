<template>
  <div class="container">
    <div class="header">
      <div class="profile">
        <router-link to="/aboutme" class="nonboder">
            <div class="icon"><img src="~/assets/redyPortfolio.png" /></div>
            <p class="iconsub">CV</p>
        </router-link>
        
      </div>
      <div class="works">
        <router-link to="/worksOverWiew" class="nonboder">
        <div class="icon"><img src="~/assets/goodjobIcon.png" /></div>
        <p class="iconsub">works</p>
        </router-link>
      </div>

      
      <div class="title"><a href="/" class="home"><p>yukipedia</p></a></div>
      
      
      <div class="skill">
        <!-- <router-link to="/worksOverWiew" class="nonboder"> -->
          <div class="icon"><img src="~/assets/penIcon.png" /></div>
          <p class="iconsub">skill</p>
        <!-- </router-link> -->
      </div>

      <div class="contact">
      <!-- <router-link to="/worksOverWiew" class="nonboder"> -->
        <div class="icon"><img src="~/assets/comentIcon.png" /></div>
        <p class="iconsub">contact</p>
      <!-- </router-link> -->
      </div>
    </div>
    <hr class="line" />
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
  max-width: 100vw;
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
p{
  text-align: center;
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

.home:hover,.home:visited{
  color: #000;
}

.home{
  text-decoration:none; 
  font-size: 25px;
}

hr{
  width: 100vw;
}

.line{
	position: relative;
	overflow: visible;
	text-align: center;
	color: #a3b9e0;
	border-width: 3px 0 0 0;
	border-style: double;
	border-color: #a3b9e0;
}
.line::after {
	position: absolute;
	top: -0.7em;
	left: 50%;
  transform: translate(-50%, 0);
	display: inline-block;
	content: '　♡　';
	background: #f7f8fb;
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
