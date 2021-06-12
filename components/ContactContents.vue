<template>
  <div class="contactcontents">
    <div class="contacttitle">
      <h1>- contact -</h1>
    </div>

    <div class="account">
      <div class="imgtitle">
        <div class="contactIconimg">
          <img src="~/assets/GitHub-Logo.jpg" class="Iconimg" />
        </div>
        <p>Github&emsp;:&ensp;</p>
      </div>
      <div class="contactmedium">
        <a
          href="https://github.com/schnee25"
          class="contactlink"
          rel="”noopener"
          noreferrer”
          target="_blank"
          >schnee25</a
        >
      </div>
    </div>

    <div class="account">
      <div class="imgtitle">
        <div class="contactIconimg">
          <img src="~/assets/mail-icon.jpeg" class="Iconimg" />
        </div>
        <p>Email&emsp;:&ensp;</p>
      </div>
      <div class="contactmedium">
        <p class="mailadress">schnee.2525yukiあっとgmail.com / <span>あっと→@</span></p>
      </div>
    </div>

    <div class="account">
      <div class="imgtitle">
        <div class="contactIconimg">
          <img src="~/assets/facebook-Logo.png" class="Iconimg" />
        </div>
        <p>facebook&emsp;:&ensp;</p>
      </div>
      <div class="contactmedium">
        <a
          href="https://www.facebook.com/yuki.O2525"
          class="contactlink"
          rel="”noopener"
          noreferrer”
          target="_blank"
          >Yukino Oyamda</a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.contacttitle {
  margin-top: 2%;
  text-align: center;
}
.account {
  display: flex;
  justify-content: center;
  padding: 3px 0 4px 0;
}
.imgtitle {
  display: flex;
  padding: 0 1% 0 1%;
}
.Iconimg {
  max-width: 20px;
  max-height: 20px;
}
.imgtitle {
  display: flex;
  min-width: 50vw;
  justify-content: flex-end;
}
.contactmedium {
  padding-left: 0.5%;
  display: flex;
  min-width: 50vw;
}

.contactIconimg {
  padding-right: 2%;
}
.mailadress {
  text-align: left;
}

/* レスポンシブ */
@media screen and (max-width: 959px) {
  /* 959px以下に適用されるCSS（タブレット用） */
}
@media screen and (max-width: 480px) {
  /* 480px以下に適用されるCSS（スマホ用） */
  .account {
    display: flex;
    justify-content: center;
    flex-direction: column;
    padding-left: 2%;
  }

  .imgtitle {
    justify-content: center;
  }
  .Iconimg {
    max-width: 20px;
    max-height: 20px;
  }
  .contactmedium {
    padding-bottom: 5%;
    display: flex;
    justify-content: center;
  }
}
</style>
