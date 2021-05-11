<template>
    <div class="contactcontents">
       <div class="contacttitle"><h1>- contact -</h1></div>
       
       <div class="account">
            <div><img src="~/assets/GitHub-Logo.jpg" class="contactIconimg"></div>
            <div class="contactmedium"><p>Github:&ensp;</p> <a href="https://github.com/schnee25" class="contactlink" rel=”noopener noreferrer” target="_blank">schnee25</a></div>
       </div>
       
       <div class="account">
            <div><img src="~/assets/mail-icon.jpeg" class="contactIconimg"></div>
            <div class="contactmedium"><p>Email:&ensp;</p> <p>schnee.2525yukiあっとgmail.com  / あっと→@</p></div>
       </div>

       <div class="account">
            <div><img src="~/assets/facebook-Logo.png" class="contactIconimg"></div>
            <div class="contactmedium"><p>facebook:&ensp;</p> <a href="https://www.facebook.com/yuki.O2525" rel=”noopener noreferrer” target="_blank">Yukino Oyamda</a></div>
       </div>
       
    </div>
</template>

<script>
export default {
}
</script>

<style>


.contacttitle {
    margin-top: 2%;
    text-align: center;
}
.account {
    display: flex;
    justify-content: center;
}
.contactIconimg {
    max-width: 20px;
}
.contactmedium{
    padding-left: 0.5%;
    display: flex;
}

</style>