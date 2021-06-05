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

hr{
margin-top: 15px;
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

h1 {
  font-size: 110%;
  font-weight: normal;
  text-align: center;
}



.border {
  display: block;
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