<template lang="">
       
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    
    <div class="topnav" id="myTopnav">
       
        <a href="#home" class="active">
            <img alt="Dragon" class="logo" src="@/assets/logotransparent.png" width="100" height="100"/>
        </a>
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
    </div>
</template>

<script>

    export default {
        
    }
</script>
<style>
.topnav {
  overflow: hidden;
}

.topnav a {
  float: left;
  display: block;
  color: #04BBBA;
  text-align: center;
  padding: 1% 10%;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #B79370;
  color: #04BBBA;
}

.topnav a.active.logo {
  color: #B79370;
  position: absolute;
}

.topnav logo {
  color: #B79370;
}
</style>