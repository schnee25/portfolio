<template>
  
        <div class="skillcontents">
            <div class="skilltitle"><h1>- skill -</h1>
            </div>

            <div class="exskill">
            <div class="logo">
              <img src="~/assets/HTML-Logo.png" class="skilliconimg"/>
            </div>
              <p class="HTML">&ensp;HTML　/ </p>
            </div>

            <div class="exskill">
            <div class="logo">
              <img src="~/assets/CSS-Logo.png"  class="skilliconimg"  />
            </div>
              <p class="CSS">&ensp;CSS　/ </p>
            </div>

            <div class="exskill">
            <div class="logo">
              <img src="~/assets/js-Logo.png" class="skilliconimg"/>
            </div>
              <p class="JavaScript">&ensp;JavaScript　/ </p>
            </div>

            <div class="exskill">
            <div class="logo">
                <img src="~/assets/Vue-Logo.png" class="skilliconimg"/>
            </div>
            <p class="Vue">&ensp;Vue.js</p>
            </div>

<br>
          
            <div class="exskill">
            <div class="logo">
              <img src="~/assets/Microsoft-Word-Logo.png" class="skilliconimg"/>
            </div> 
             <p class="Word">&ensp;Word　/ </p>
            </div>

           <div class="exskill">
            <div class="logo">
              <img src="~/assets/Microsoft-Excel-Logo.png" class="skilliconimg"/>
            </div>
            <p class="Exel">&ensp;Excel　/ </p>
           </div>

            <div class="exskill">
            <div class="logo">
                <img src="~/assets/Microsoft-Powerpoint-Logo.png" class="skilliconimg"/>
            </div><p class="PowerPoint">&ensp;PowerPoint　/ </p>
            </div>

<br>

            <div class="exskill">
            <div class="logo">
                <img src="~/assets/Git-Logo.png" class="skilliconimg"/>
            </div><p class="git">&ensp;git　/ </p>
            </div>

            <div class="exskill">
            <div class="logo">
                <img src="~/assets/VisualStudioCode-Logo.png" class="skilliconimg"/>
            </div><p class="VScode">&ensp;Visual Studio Code　/ </p>
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

/* .HTML
.CSS
.JavaScript
.Vue
.Word
.Exel
.PowerPoint
.git
.VScode */


</style>
