<template>
  <div class="container">
    <AppNameHeader></AppNameHeader>
    <hr class="border" />

    <div class="body">
      <div class="main">
        <div class="aboutme">
          <div class="profImg"></div>
          <div class="proftext">
            <h1 class="aboutmetxt">- about me -</h1>
            <p>名前: 小山田　雪乃</p>
            <p>　　おやまだ ゆきの</p>
            <p>
              2000年12月生まれ。
              <span>熊本高校卒。</span>
              <span>立教大学法学部に在籍。</span>
            </p>
            <p>好きなこと: 食べること🍙</p>
            <router-link to="/aboutme">
            <p class="exactly">More information</p>
            </router-link>
            <!-- ↑ 詳しいページ作る？リンクに -->
          </div>
        </div>

       <div class="worksbox">
         <WorksContents></WorksContents>
       </div>
       <div class="skillbox"><SkillContents></SkillContents></div>

       <div class="contactcontents"><ContactContents></ContactContents></div>
     </div>
    </div>
    <hr class="border" />
    <div class="footer">
      <AppFooter></AppFooter>
    </div>
  </div>
  
</template>

<script>
export default {
}

import AppNameHeader from '../components/AppNameHeader.vue';
components: {
  AppNameHeader
}

import WorksContents from '../components/WorksContents.vue'
components: {
  WorksContents
}

import SkillContents from '../components/SkillContents';
components: {
  SkillContents
}

import ContactContents from '../components/ContactContents'
components: {
  ContactContents
}

import AppFooter from '../components/AppFooter'
components: {
  AppFooter
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
  text-align: center;
}
.exactly{
  text-align: center;
}
a{
  color: #000;
}
a:hover{
  color: blueviolet;
}
.Home:hover{
  color: #000;
}
a {
    text-decoration:none; 
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
