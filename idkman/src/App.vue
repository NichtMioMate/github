<template>
  <div class ="menu">
  
    <div class="menu-item menu-text"> <router-link to="/">Home</router-link> </div>
    <div class="menu-item menu-text"><router-link to="/about">About</router-link> </div>
    <div class="menu-center ">Samuel Lins </div>
    <div class="menu-item menu-text"><router-link to="/nachrichten">Nachrichten</router-link> </div>
    <div class="menu-item menu-text"><router-link to="/resume">Resume</router-link> </div>
 
</div>
  <router-view/>
</template>‚
‚
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}

*{
  margin:0;
  padding:0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
  background-color: black;
}


.menu{
  display: flex;
  align-items: center;
  justify-content: space-around;
  text-decoration:none;
}
.menu-item{
  flex: 1;
 
  text-align: center;
}
.menu-text{
  font-size: 26px;
  color: white;
  
  padding: 10px;
  border-bottom: 2px solid #000000c4;
}
.menu-text:hover{
  border-bottom: 2px solid #ffffff;
}
.menu-center{
  font-size: 50px;
  color: white;
}
.Text{
  margin-top: 100px;
}
</style>
