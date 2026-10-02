<script setup></script>

<template>
  <div class="background" style="display: block;"> 
  <div class="header" style="display: flex; justify-content: space-between;">
    <image class="logo"></image>
    <h1>Title</h1>
    <button class="header-btn">Labels</button>
    <button class="header-btn">Label</button>
    <button class="header-btn">Label</button>
    <div class="header-account">
      <image class="pfp"></image>
      <label class="header-label">Label</label>
    </div>
  </div>

  <div class="div-slogan">
    <label class="slogan" style="align-items: center;">Slogan</label>
  </div>

  <div class="search-container">
    <input type="text" placeholder="Label">
    <button class="button button-search">->Button<-</button>
  </div>

  <div class="subheader">
    <label class="subheader-label">Review Header</label>
  </div>

  <div class="container">
      <div class=" subcontainer izquierda"></div>
      <div class="subcontainer derecha"></div>
  </div>

  <div class="subheader">
    <label class="subheader-label">Pack Header</label>
  </div>

  <div class="container">
      <div class=" subcontainer izquierda"></div>
      <div class="subcontainer derecha"></div>

  </div>

  
  <div class="subheader">
    <label class="subheader-label">Room Header</label>
  </div>

    <div class="container">
      <div class=" subcontainer izquierda"></div>
      <div class="subcontainer derecha"></div>

    </div>
  
    <div class="footer" style="margin-top: 5vh;">
      <footer>
        <div class="footer-boxes" style="display: flex; justify-content: space-between;">
          <div class="footer-container">
          <label>About us</label> 
          </div>
          <div class="footer-container">
          <label>About us</label> 
          </div>
          <div class="footer-container">
          <label>About us</label> 
          </div>
        </div>
        <div class="very-bottom">
          <label>Privacy / Terms and Conditions</label>
        </div>
      </footer>
    </div>
  </div>
</template>

<style scoped>

.background{
  background-color: #E9E7EE;
  color: #040316;
}
.header{
  background-color: #125F50 ;
  align-items: center;
  text-align: center;

}

.header-account{
  background-color: #123A5F;
  display: flex;
  padding: 5vh;
  margin-right: 5%;
}

.search-container{
  background-color: #123A5F;
  align-items: center;
  display: grid;
  padding: 6%;

}

.div-slogan{
  margin: 10vh;
  background-color: #123A5F;
}

.subheader{
 align-items: center;
 background-color: #125F50;
 margin-top: 10%;
 margin-bottom: 10vh;
 text-align: center;
}

.container{
 
 background-color:#E9E7EE;
 display: flex;
 width: 100%;
 justify-content: center;
 
}

.subcontainer{
  flex: 1;
}

.izquierda{
  padding: 20vh;
  background-color: #125F50 ;
}

.derecha{
  padding: 20vh;
  background-color: #123A5F;
}

.footer-container {
  background-color: #125F50 ;
  
  color: #040316 ;
}

.footer-boxes{
  background-color: #125F50 ;
  
  color: #040316 ;
}

.very-bottom
{
  background-color: #125F50 ;
  
  color: #040316 ;
}
</style>
