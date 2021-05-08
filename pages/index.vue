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
    <div class="body"></div>
    <div class="footder"></div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  font-family: 'Hachi Maru Pop', cursive;
  margin: 0 auto;
  display: flex;
  justify-content: center;
}

.header {
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
</style>
