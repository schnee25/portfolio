<template>

  <div class="container">
    <AppNameHeader></AppNameHeader>

    <div class="body">
        <div class="main">
       
          <div class="worksportfolio">
            <div class="worksimg"><img src="~/assets/screanshot-portfolio.jpg" class="workss"/></div>
            <h1>ポートフォリオ</h1>
          </div>

          <div class="explanation">
            <div class="excomponent">
              <h2 class="subtitle">概要</h2>
              <div class="separation"><p>:&ensp;</p></div>
              <div class="extxt">
                <p>自身のポートフォリオサイトです。</p> 
                <p>インターン等で使うため作成しました。</p>
                <p>作成途中です。</p>
              </div>
              
            </div>

            <div class="excomponent">
              <h2 class="subtitle">URL</h2>
              <div class="separation"><p>:&ensp;</p></div>
              <div><p class="skilltxt">https://yukipedia-portfolio.herokuapp.com/</p></div>
            </div>

            <div class="excomponent">
              <h2 class="subtitle">作成期間</h2>
              <div class="separation"><p>:&ensp;</p></div>
              <div>
                <p class="skilltxt">
                  役1週間(未完成)
                  <!-- 5/9 〜 until now -->
                </p>
              </div>
            </div>
            
            <div class="excomponent">
              <h2 class="subtitle">使用言語･ツール</h2>
              <div class="separation"><p>:&ensp;</p></div>
              <div class="skillitems">
                <div class="usedskill">
                  <div class="logo">
                  <img src="~/assets/HTML-Logo.png" class="skilliconimg"/>
                  </div>
                  <p class="HTML">&ensp;HTML</p>
                </div>

                <div class="usedskill">
                  <div class="logo">
                    <img src="~/assets/CSS-Logo.png"  class="skilliconimg"  />
                  </div>
                  <p class="CSS">&ensp;CSS</p>
                </div>
                
                <div class="usedskill">
                  <div class="logo">
                    <img src="~/assets/js-Logo.png" class="skilliconimg"/>
                  </div>
                    <p class="JavaScript">&ensp;JavaScript</p>
                </div>

                <div class="usedskill">
                  <div class="logo">
                   <img src="~/assets/Vue-Logo.png" class="skilliconimg"/>
                  </div>
                    <p class="Vue">&ensp;Vue.js</p>
                </div>


                <div class="usedskill">
                  <div class="logo">
                  <img src="~/assets/Git-Logo.png" class="skilliconimg"/>
                  </div>
                  <p class="git">&ensp;git</p>
                </div>

                 <div class="usedskill">
                   <div class="logo">
                    <img src="~/assets/VisualStudioCode-Logo.png" class="skilliconimg"/>
                  </div>
                  <p class="VScode">&ensp;Visual Studio Code</p>
                 </div>
              </div>
            </div>
            

            <div class="excomponent">
              <h2 class="subtitle">実装の際に意識した点</h2>
              <div class="separation"><p>:&ensp;</p></div>
              <div class="extxt">
                <p>･ 初めてVueを使って作ったプロジェクトなので<span>Vueの理解が難しかったです。</span></p>
                <p>･ トップページのみスマホでの表示のみ<span>メディアエクリでレスポンシブ対応</span></p>
                <p>･ その他のページやタブレットでの表示にも対応予定</p>
                <p>ブラウザバックに未対応なのでそこの対応も早急に</p>
                <p>･ 未完成なのでこれから頑張って作り上げたいと思っています。<span></span></p>
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
export default {
}

import AppNameHeader from '../../components/AppNameHeader.vue';
components: {
  AppNameHeader
}

</script>

<style>
.body {
  font-family: 'Kiwi Maru', serif;
  min-height: calc(100vh - 150px);
}

.worksportfolio{
  display: inline-block;
  margin: 3% 0 1% 0;
  width: 100vw;
  text-align: center;
}

.workss{
   max-width: 250px;
   max-height: 250px;
   margin-bottom: 2%;
}
h1 {
  font-size: 130%;
  font-weight: normal;
}

p{
  text-align: left;
  }
h2{
  margin-left: 2%;
  }
.subtitle {
  display: flex;
  font-size: 110%;
  font-weight: normal;
  justify-content: center;
  width: 180px;
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
}
.HTML,.CSS,.JavaScript,.Vue,.git,.VScode{
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
.udedskill{
 display: inline-block;
}

.skillitems{
  display: flex;
  flex-direction: column;
}

.border {
  display: block;
}



</style>