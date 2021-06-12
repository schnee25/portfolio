<template>
  <div class="container">
    <div class="foooter">
      <hr class="border" />
      <h1 class="footerlogo">© 2021 oyamada</h1>
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

.footer {
  font-family: 'Hachi Maru Pop', cursive;
  display: inline-block;
  display: flex;
  justify-content: center;
  align-content: center;
  margin: 0 0 1% 0;
  /* height: 100px;
  line-height: 100px; */
  /* height/line-height -> 子要素の上下を中央揃えにするため */
}

.footerlogo {
  font-size: 20px;
  font-weight: normal;
  text-align: center;
  margin-block-start: 0.67em;
  margin-block-end: 0.67em;
}

.border {
  display: block;
  margin-top: 8px;
}
</style>
