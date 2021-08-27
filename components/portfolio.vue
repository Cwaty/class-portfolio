<template>
<v-container>
  <link href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" rel="stylesheet">
<div id ="profil-fotografi" class="d-flex flex-column justify-center align-center">
<img src = "https://cdn.discordapp.com/attachments/856641561675825162/880474909371924500/shw.jpg"/>
<h1>{{ name }}</h1>
<p>{{ description }}</p>
<div class="d-flex">
<a href="https://github.com/Cwaty" target="_blank" title="Github"> <i class="fab fa-github mx-2"></i></a>
<a href="https://twitter.com/liltamercan" target="_blank" title="Twitter"> <i class="fab fa-twitter mx-2"></i></a>
<a href="discord://discord.com/users/338768594899042304" target="_blank" title="Discord"> <i class="fab fa-discord mx-2"></i></a>
</div>
</div>
</v-container>
</template>

<script>
export default{
    data() {
        return {
            name: "Tamercan | Sherwood",
            description: "Bot Developer at discord , Mod of Codesty & Atmosfer",
        }
    }

}
</script>

<style scope lang = "scss">
i {
     margin-right: 10px;
    font-size: 44px;
    color: #D7D7D7;
}
i {
  padding: 5px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
}
i:hover {
  opacity: 0.7;
}
#profil-fotografi {
    height: 85vh;
    img{
        max-height: 150px;
        border-radius: 130px
    } 
}

</style>

