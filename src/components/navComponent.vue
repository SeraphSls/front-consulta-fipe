<template lang="">
       
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    
    <div class="topnav" id="myTopnav">
       <div id="logoDiv">
          <img alt="Dragon" class="logo" src="@/assets/logotransparent.png" width="100" height="100"/>
       </div>
      <div class="buttons">
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
      </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>
<style>

@font-face {
   font-family: "Poppins-Light-Italic";
   src: url("../assets/fonts/Poppins-LightItalic.ttf");
}

@font-face {
   font-family: "Poppins-Regular";
   src: url("../assets/fonts/Poppins-Regular.ttf");
}

@font-face {
   font-family: "Poppins-Regular-Italic";
   src: url("../assets/fonts/Poppins-Italic.ttf");
}
.topnav {
  overflow: hidden;
  display: flex;
}

.buttons {
  display: flex;
  margin-left: 60%;
}

.buttons a {
    height: 60px;
    float: left;
    display: block;
    color: #04BBBA;
    text-align: center;
    padding: 1% 10%;
    text-decoration: none;
    font-size: 38px;
    font-family: 'Poppins-Regular-Italic';
}

.buttons a:hover {
  background-color: #233A54;
  color: #04BBBA;
  border-radius: 25%;
}

</style>