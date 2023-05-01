<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="transparent">
      <b-navbar-brand href="#">
        <img src="../assets/pulse.png" alt=""  class="logo desktop-logo"/>
        <img src="../assets/prenuer.png" alt=""  class="logo mobile-logo"/>
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse">
        <template #default="{ expanded }">
          <Icons v-if="expanded" name="close" class="close"/>
          <Icons v-else name="bar" />
      </template>
      </b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
            <b-nav-item href="#header">About</b-nav-item>
            <b-nav-item href="#partner">Partners</b-nav-item>
            <b-nav-item href="#services">Services</b-nav-item>
            <b-nav-item href="#project">Projects</b-nav-item>
            <b-nav-item href="#why">Why Us</b-nav-item>
            <b-nav-item href="#contact">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
import Icons from './Icons.vue'

export default {
  name: "Nav",
  components:{
    Icons
  }
};
</script>

<style>
  .navbar{
    padding-top: 18px;
  }
  .navbar-dark .navbar-nav .nav-link{
    color: #fff;
  }
  .navbar-nav{
    justify-content: flex-end;
    padding-right: 18%;
    font-weight: 500;
  }
  .navbar-dark .navbar-nav .nav-link:hover{
    color: #B50005;
  }
  .navbar-brand{
    margin-left: 6%;
  }
  .mobile-logo{
    display: none;
  }
  .navbar-dark .navbar-toggler{
    border: none;
  }
  button:focus{
    outline: none;
  }

  @media (max-width: 480px){
    .logo{
      width: 100px;
      height: 50px;
    }
    .close{
      position: relative;
      z-index: 9999;
    }
    .navbar-nav{
      padding-right: 0;
    }
    #nav-collapse{
      overflow-y: hidden;
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 99;
      background: #b50005;
      color: #fff;
      padding: 40% 50px;
      text-align: center;
      height: 100vh;
      font-size: 28px;
    }
    .mobile-logo{
      display: block;
    }
    .desktop-logo{
      display: none;
    }
  }

  @media (min-width: 481px) and (max-width: 768px){
    .logo{
      width: 120px;
      height: 60px;
    }
    .close{
      position: relative;
      z-index: 9999;
    }
    .navbar-nav{
      padding-right: 0;
    }
    #nav-collapse{
      overflow-y: hidden;
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 99;
      background: #b50005;
      color: #fff;
      padding: 40% 50px;
      text-align: center;
      height: 100vh;
      font-size: 28px;
    }
    .mobile-logo{
      display: block;
    }
    .desktop-logo{
      display: none;
    }
  }

  @media (min-width: 769px) and (max-width: 991px){
    .logo{
      width: 120px;
      height: 60px;
    }
    .close{
      position: relative;
      z-index: 9999;
    }
    .navbar-nav{
      padding-right: 0;
    }
    #nav-collapse{
      overflow-y: hidden;
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 99;
      background: #b50005;
      color: #fff;
      padding: 40% 50px;
      text-align: center;
      height: 100vh;
      font-size: 28px;
    }
  }

  @media (min-width: 992px) and (max-width: 1200px){
    .logo{
      width: 120px;
      height: 60px;
    }
    .navbar-nav{
      padding-right: 5%;
    }
  }

  @media (min-width: 1201px){
    .logo{
      width: 120px;
      height: 60px;
    }
    .navbar-nav{
      padding-right: 10%;
    }
  }
</style>
