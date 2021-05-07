<template>
  <div class="container">
    <div class="header">
      <div class="profile">
        <p>about</p>
      </div>
      <div class="works">
        <p>works</p>
      </div>
      <div class="title"><p>yukipedia</p></div>
      <div class="skill">
        <p>skill</p>
      </div>
      <div class="contact">
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

  height: 100px;
  line-height: 100px;
  /* height/line-height -> 子要素の上下を中央揃えにするため */
}

.profile,
.works,
.skill,
.contact {
  display: inline-block;
  margin: 10px;
  vertical-align: middle;
}

.title {
  display: inline-block;
  margin: 10px 13px 10px 13px;
  font-size: 1.3em;
  vertical-align: middle;
}
</style>
