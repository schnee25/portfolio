<template>
  
        <div class="skillcontents">
            <div class="skilltitle"><h1>- skill -</h1></div>
          <div class="exskill">
            <div class="logo">
              <img src="~/assets/HTML-Logo.png" class="skilliconimg"/>
            </div>
              <p>　HTML　/ </p>
          </div>

          <div class="exskill">
            <div class="logo">
              <img src="~/assets/CSS-Logo.png"  class="skilliconimg"  />
            </div>
              <p>　CSS　/ </p>
          </div>

          <div class="exskill">
            <div class="logo">
              <img src="~/assets/js-Logo.png" class="skilliconimg"/>
            </div>
              <p>　JavaScript　/ </p>
          </div>
<br>
          <div class="exskill">
            <div class="logo">
              <img src="~/assets/Microsoft-Word-Logo.png" class="skilliconimg"/>
            </div> 
            <p class="skills">　Word　/ </p>
          </div>

          <div class="exskill">
            <div class="logo">
              <img src="~/assets/Microsoft-Excel-Logo.png" class="skilliconimg"/>
            </div>
            <p class="skills">　Excel　/ </p>
          </div>

          <div class="exskill">
            <div class="logo">
                <img src="~/assets/Microsoft-Powerpoint-Logo.png" class="skilliconimg"/>
            </div><p lass="skills">　PowerPoint　/ </p>
          </div>

<br>

         <div class="exskill">
            <div class="logo">
                <img src="~/assets/Git-Logo.png" class="skilliconimg"/>
            </div><p lass="skills">　git　/ </p>
          </div>

          <div class="exskill">
            <div class="logo">
                <img src="~/assets/VisualStudioCode-Logo.png" class="skilliconimg"/>
            </div><p lass="skills">　Visual Studio Code　/ </p>
          </div>

          <div class="exskill">
            <div class="logo">
                <img src="~/assets/Vue-Logo.png" class="skilliconimg"/>
            </div><p lass="skills">　Vue.js</p>
          </div>
        
        </div>
   
</template>

<script>
export default {}
</script>

<style>
.skillcontents {
    padding-top: 3%;
    margin: 0 auto;
    margin-top: 2%;
    text-align: center;
}
.skilltitle{
    text-align: center;
    margin-bottom: 2%;
}
.skillbox{
    text-align: center;
}

.exskill {
 display: inline-flex;
 
}

.skilliconimg {
  max-width: 21px;
  max-height: 21px;
}
.logo {
  height: 21px;
  width: 21px;
}



</style>
