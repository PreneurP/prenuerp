<template>
  <div id="header">
    <div class="d-flex contain">
      <div class="left">
        <div class="head">
          <h2>Speed.</h2>
          <h2>Automation.</h2>
          <h2>Revamp.</h2>
          <div class="text">
            Let’s redefine how your business and organisation work. <span>Experience the pulse effect and have your customers smiling back to you for constant satisfaction while using your tech products.</span>
          </div>
          <button class="btn-pulse"><a href="#services">Get Started</a></button>
        </div>
      </div>
      <div class="right">
        <Icons name="dots" class="dot"/>
        <Icons name="half1" class="half1"/>
        <Icons name="half2" class="half2"/>
        <Icons name="half3" class="half3"/>
        <Icons name="pattern" class="pattern"/>
        <img src="../assets/User1.png" alt="" class="user1">
        <img src="../assets/User2.png" alt="" class="user2">
        <img src="../assets/User3.png" alt="" class="user3">
        <img src="../assets/User4.png" alt="" class="user4">
      </div>
    </div>
    <Nav />
  </div>
</template>

<script>
import Nav from './Nav.vue'
import Icons from './Icons.vue'

export default {
    name: "Header",
    components: {
      Nav,
      Icons
    }
}
</script>

<style>
  #header{
    height: 140vh;
  }
  .contain{
    position: absolute;
    width: 100%;
    height: 140%;
  }
  .left{
    width: 50%;
    background: #fff;
    padding: 15% 8%;
    padding-top: 20%;
  }
  .head{
    height: 100%;
    display: flex;
    flex-direction: column;
    align-content: center;
    justify-content: center;
    text-align: left;
  }
  .head h2{
    font-size: 72px;
    font-weight: 800;
  }
  .text{
    margin-top: 20px;
    margin-bottom: 30px;
    font-size: 18px;
  }
  .btn-pulse{
    background: #b50005;
    color: #fff;
    padding: 12px 32px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
  .btn-pulse a{
    color: #fff;
    text-decoration: none;
  }
  .right{
    width: 50%;
    background: #18191f;
    right: 0;
  }
  .user1{
    position: absolute;
    top: 35%;
    left: 45.5%;
  }
  .user2{
    position: absolute;
    top: 28%;
    right: 12%;
  }
  .user3{
    position: absolute;
    top: 63%;
    right: 30%;
  }
  .user4{
    position: absolute;
    top: 70%;
    right: 7%;
  }
  .dot{
    position: absolute;
    top: 28%;
    right: 10%;
    width: 68px;
    height: 68px;
  }
  .half1{
    position: absolute;
    top: 15%;
    right: 41%;
    width: 144px;
    height: 72px;
  }
  .half2{
    position: absolute;
    top: 55%;
    right: 0;
    width: 65px;
    height: 72px;
  }
  .half3{
    position: absolute;
    bottom: 0;
    right: 22%;
    width: 72px;
    height: 72px;
  }
  .pattern{
    position: absolute;
    top: 63%;
    right: 26%;
    width: 162px;
    height: 162px;
  }

  @media (max-width: 480px){
    #header{
    height: 100vh;
  }
  .contain{
    position: absolute;
    width: 100%;
    height: 100%;
  }
  .left{
    width: 100%;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('../assets/dev.jpg');
    background-size: cover;
    padding: 15% 8%;
    padding-top: 20%;
    color: #fff;
  }
  .head h2{
    font-size: 24px;
    font-weight: 800;
  }
  .text{
    margin-top: 20px;
    margin-bottom: 15px;
    font-size: 14px;
  }
  /* .text span{
    display: none;
  } */
  .btn-pulse{
    background: #b50005;
    color: #fff;
    padding: 8px 10px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 16px;
    width: 50%;
  }
  .right{
    width: 50%;
    background: #18191f;
    right: 0;
    display: none;
  }
  .user1{
    position: absolute;
    top: 35%;
    left: 45.5%;
    width: 50px;
    height: 50px;
    display: hidden;
  }
  .user2{
    position: absolute;
    top: 28%;
    right: 12%;
    width: 50px;
    height: 50px;
    display: hidden;
  }
  .user3{
    position: absolute;
    top: 63%;
    right: 30%;
    width: 50px;
    height: 50px;
    display: hidden;
  }
  .user4{
    position: absolute;
    top: 70%;
    right: 7%;
    width: 50px;
    height: 50px;
    display: hidden;
  }
  .dot{
    position: absolute;
    top: 28%;
    right: 10%;
    width: 30px;
    height: 30px;
    display: hidden;
  }
  .half1{
    position: absolute;
    top: 15%;
    right: 41%;
    width: 50px;
    height: 50px;
    display: hidden;
  }
  .half2{
    position: absolute;
    top: 55%;
    right: 0;
    width: 50px;
    height: 50px;
    display: hidden;
  }
  .half3{
    position: absolute;
    bottom: 0;
    right: 22%;
    width: 50px;
    height: 50px;
    display: hidden;
  }
  .pattern{
    position: absolute;
    top: 63%;
    right: 26%;
    width: 65px;
    height: 70px;
    display: hidden;
  }
  }

  @media (min-width: 481px) and (max-width: 768px){
    #header{
    height: 100vh;
  }
  .contain{
    position: absolute;
    width: 100%;
    height: 100%;
  }
  .left{
    width: 100%;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('../assets/dev.jpg');
    background-size: cover;
    color: #fff;
    padding: 15% 8%;
    padding-top: 20%;
  }
  .head h2{
    font-size: 24px;
    font-weight: 800;
  }
  .text{
    margin-top: 20px;
    margin-bottom: 15px;
    font-size: 16px;
  }
  /* .text span{
    display: none;
  } */
  .btn-pulse{
    background: #b50005;
    color: #fff;
    padding: 8px 10px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    width: 50%;
  }
  .right{
    width: 50%;
    background: #18191f;
    right: 0;
    display: none;
  }
  .user1{
    position: absolute;
    top: 35%;
    left: 45.5%;
    width: 60px;
    height: 60px;
  }
  .user2{
    position: absolute;
    top: 28%;
    right: 12%;
    width: 65px;
    height: 65px;
  }
  .user3{
    position: absolute;
    top: 63%;
    right: 30%;
    width: 60px;
    height: 60px;
  }
  .user4{
    position: absolute;
    top: 70%;
    right: 7%;
    width: 60px;
    height: 60px;
  }
  .dot{
    position: absolute;
    top: 28%;
    right: 10%;
    width: 35px;
    height: 35px;
  }
  .half1{
    position: absolute;
    top: 15%;
    right: 41%;
    width: 60px;
    height: 60px;
  }
  .half2{
    position: absolute;
    top: 55%;
    right: 0;
    width: 50px;
    height: 50px;
  }
  .half3{
    position: absolute;
    bottom: 0;
    right: 22%;
    width: 50px;
    height: 50px;
  }
  .pattern{
    position: absolute;
    top: 63%;
    right: 26%;
    width: 65px;
    height: 70px;
  }
  }

  @media (min-width: 769px) and (max-width: 1024px){
    #header{
    height: 100vh;
  }
  .contain{
    position: absolute;
    width: 100%;
    height: 100%;
  }
  .left{
    width: 50%;
    background: #fff;
    padding: 15% 8%;
    padding-top: 20%;
  }
  .head h2{
    font-size: 28px;
    font-weight: 800;
  }
  .text{
    margin-top: 20px;
    margin-bottom: 15px;
    font-size: 18px;
  }
  .btn-pulse{
    background: #b50005;
    color: #fff;
    padding: 8px 12px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
  .right{
    width: 50%;
    background: #18191f;
    right: 0;
  }
  .user1{
    position: absolute;
    top: 35%;
    left: 45.5%;
    width: 70px;
    height: 70px;
  }
  .user2{
    position: absolute;
    top: 28%;
    right: 12%;
    width: 75px;
    height: 75px;
  }
  .user3{
    position: absolute;
    top: 63%;
    right: 30%;
    width: 70px;
    height: 70px;
  }
  .user4{
    position: absolute;
    top: 70%;
    right: 7%;
    width: 70px;
    height: 70px;
  }
  .dot{
    position: absolute;
    top: 28%;
    right: 10%;
    width: 40px;
    height: 40px;
  }
  .half1{
    position: absolute;
    top: 15%;
    right: 41%;
    width: 80px;
    height: 70px;
  }
  .half2{
    position: absolute;
    top: 55%;
    right: 0;
    width: 50px;
    height: 50px;
  }
  .half3{
    position: absolute;
    bottom: 0;
    right: 22%;
    width: 50px;
    height: 50px;
  }
  .pattern{
    position: absolute;
    top: 63%;
    right: 26%;
    width: 80px;
    height: 85px;
  }
  }

  @media (min-width: 1025px) and (max-width: 1200px){
    #header{
    height: 130vh;
  }
  .contain{
    position: absolute;
    width: 100%;
    height: 130%;
  }
  .left{
    width: 50%;
    background: #fff;
    padding: 15% 8%;
    padding-top: 20%;
  }
  .head h2{
    font-size: 30px;
    font-weight: 800;
  }
  .text{
    margin-top: 20px;
    margin-bottom: 15px;
    font-size: 18px;
  }
  .btn-pulse{
    background: #b50005;
    color: #fff;
    padding: 10px 14px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
  .right{
    width: 50%;
    background: #18191f;
    right: 0;
  }
  .user1{
    position: absolute;
    top: 35%;
    left: 45.5%;
    width: 80px;
    height: 80px;
  }
  .user2{
    position: absolute;
    top: 28%;
    right: 12%;
    width: 85px;
    height: 85px;
  }
  .user3{
    position: absolute;
    top: 63%;
    right: 30%;
    width: 80px;
    height: 80px;
  }
  .user4{
    position: absolute;
    top: 70%;
    right: 7%;
    width: 80px;
    height: 80px;
  }
  .dot{
    position: absolute;
    top: 28%;
    right: 10%;
    width: 45px;
    height: 45px;
  }
  .half1{
    position: absolute;
    top: 15%;
    right: 41%;
    width: 90px;
    height: 70px;
  }
  .half2{
    position: absolute;
    top: 55%;
    right: 0;
    width: 50px;
    height: 50px;
  }
  .half3{
    position: absolute;
    bottom: 0;
    right: 22%;
    width: 50px;
    height: 50px;
  }
  .pattern{
    position: absolute;
    top: 63%;
    right: 26%;
    width: 105px;
    height: 110px;
  }
  }

  @media (min-width: 1201px){
    #header{
    height: 140vh;
  }
  .contain{
    position: absolute;
    width: 100%;
    height: 140%;
  }
  .head{
    height: 100%;
    position: relative;
    margin-bottom: 20px;
  }
  .btn-pulse{
    width: 50%;
  }
  }
</style>