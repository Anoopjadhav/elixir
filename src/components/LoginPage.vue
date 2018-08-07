<template>
<div>
  <div class="login-header">
    <img class="beaker-img" src="../assets/white-beaker-copy.png"/>

    <ul class="login-menu">
      <li><a href="">Login</a></li>
      <li><a href="">About Us</a></li>
    </ul>
  </div>
  <div class="form-container">
    <form class="login-form">
      <div class="login-main-logo-wrapper">
        <img src="../assets/header-icon-white.png" />
      </div>

    <div class="input-wrapper">
      <input type="text" value="" label="Username" placeholder="Username"/>
      <input type="password" value="" label="Password" placeholder="Password"/>
  
        <button onclick="" class="login-button">
          <span>LOGIN</span> <span class="login-arrow">></span>
        </button>
      </div>
    </form>
  </div>
</div>
</template>

<script>
export default {
  name: 'LoginPage',
  props: {
    msg: "Eternity"
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.login-header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: white;
}
.beaker-img{
  height:61px;
  margin-left: 1rem;
}
.login-menu{
  display:flex;
  justify-content: center;
  align-items: center;
}
.login-menu li{
  list-style: none;
  margin:0 1rem;
}
.login-menu a{
  color:white;
  text-decoration: none;
}
.login-form{
  width:40%;
  background-blend-mode: multiply;
  background: rgba(0,0,0,0.4);
  margin:auto;
  margin-top:5rem;
  color:white;
  padding:5rem 2rem 6rem 2rem;;
}
.login-main-logo-wrapper{
  text-align:center;
}
.input-wrapper{
  margin-top:3.75rem;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.input-wrapper > input{
  width:30%;
}
.login-button{
  margin-top:3rem;
  background: #5974d9;
  border:0;
  color:white;
  font-size:1.125rem;
  font-weight: bold;
  display:flex;
  padding:0.5rem 2rem;;
  align-items: center;
}
.login-arrow{
  font-size: 2rem;
  margin-left:0.5rem;
}
</style>
