<template>
  <div id="service">
      <div id="partner">
        <img src="../assets/benshada.png" alt="" class="partner">
        <img src="../assets/mealtrips.png" alt="" class="partners">
      </div>
      <div id="services">
        <h3>Services that connects you to your users</h3>
        <div class="boxes">
          <b-row class="first-row">
            <b-col cols="4">
              <div class="box">
                <Icons name="1" class="serv"/>
                <h4>Mobile Application</h4>
                <p>We build mobile apps that intuitively resonates with its users ensuring that value is gained throughout.</p>
              </div>
            </b-col>
            <b-col cols="4">
              <div class="box">
                <Icons name="3" class="serv"/>
                <h4>Web Application</h4>
                <p>Putting users at the center of your solution, providing the best platform to guarantee success via web apps.</p>
              </div>
            </b-col>
            <b-col cols="4">
              <div class="box">
                <Icons name="4" class="serv"/>
                <h4>User Interface Design</h4>
                <p>What is an interface design without the focus on users. lets design solutions that converts easily for you.</p>
              </div>
            </b-col>
            <b-col cols="4">
              <div class="box">
                <Icons name="5" class="serv"/>
                <h4>Strategy and Branding</h4>
                <p>Having the right strategy and plan ensures your business stands out. lets help brand and plan your idea.</p>
              </div>
            </b-col>
            <b-col cols="4">
              <div class="box">
                <Icons name="6" class="serv"/>
                <h4>Idea Launch</h4>
                <p>You are busy, but have an idea you love to execute. Let’s ease the stress and run it for you as you would have.</p>
              </div>
            </b-col>
            <b-col cols="4">
              <div class="box">
                <Icons name="7" class="serv"/>
                <h4>Project Management</h4>
                <p>It can be overwhelming having the right team and knowing how best to move, we got you covered. Relax.</p>
              </div>
            </b-col>
          </b-row>
        </div>
        <div class="explore">
        <button class="btn-explore"><a href="#project">Explore All</a> </button>
        </div>
      </div>
  </div>
</template>

<script>
import Icons from './Icons.vue'

export default {
    name: "Services",
    components: {
      Icons
    }
}
</script>

<style>
  #partner{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    width: 100%;
    background: #fff;
    height: auto;
    padding: 10px 0;
  }
  .partner{
    width: 220px;
    height: 120px;
  }
  .partners{
    width: 250px;
    height: 200px;
  }
  #services{
    background: #18191f;
    padding: 20px 8%;
  }
  #services h3{
    font-size: 44px;
    color: #fff;
    font-weight: 800;
    text-align: center;
    margin: 80px 0;
  }
  .first-row{
    margin-bottom: 30px;
    flex-flow: row wrap;
  }
  .box{
    width: 100%;
    height: 300px;
    background: #fff;
    border-radius: 8px;
    padding: 8% 6%;
    margin: 18px 0;
  }
  .serv{
    margin-bottom: 55px;
  }
  .box h4{
    font-weight: 600;
  }
  .explore{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .btn-explore{
    margin-top: 40px;
    background: transparent;
    border: 1px solid #b50005;
    color: #b50005;
    padding: 12px 20px;
    border-radius: 6px;
  }
  .btn-explore a{
    color: #b50005;
    text-decoration: none;
  }

  @media (max-width: 480px){
    #partner{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    width: 100%;
    background: #fff;
  }
  .partner{
    width: 60px;
    height: 40px;
  }
  .partners{
    width: 70px;
    height: 65px;
  }
  #services{
    background: #18191f;
    padding: 5% 10%;
    font-size: 16px;
  }
  #services h3{
    font-size: 20px;
    color: #fff;
    font-weight: 800;
    text-align: center;
    margin: 40px 0;
  }
  .row{
    flex-direction: column;
  }
  .first-row{
    margin-bottom: 0;
  }
  .col-4{
    max-width: 100%;
  }
  .box{
    width: 100%;
    height: 300px;
    background: #fff;
    border-radius: 8px;
    padding: 8% 6%;
    margin: 10px 0;
  }
  .serv{
    margin-bottom: 55px;
  }
  .box h4{
    font-weight: 600;
  }
  .btn-explore{
    margin: 20px 0;
    background: transparent;
    border: 1px solid #b50005;
    color: #b50005;
    padding: 5px 8px;
    border-radius: 6px;
  }
  }

  @media (min-width: 481px) and (max-width: 768px){
  .partner{
    width: 75px;
    height: 55px;
  }
  .partners{
    width: 90px;
    height: 80px;
  }
  #services{
    background: #18191f;
    padding: 5% 15%;
    font-size: 16px;
  }
  #services h3{
    font-size: 22px;
    color: #fff;
    font-weight: 800;
    text-align: center;
    margin: 50px 0;
  }
  .row{
    flex-direction: column;
  }
  .first-row{
    margin-bottom: 0;
  }
  .col-4{
    max-width: 100%;
  }
  .box{
    width: 100%;
    height: 300px;
    background: #fff;
    border-radius: 8px;
    padding: 8% 6%;
    margin: 10px 0;
  }
  .serv{
    margin-bottom: 55px;
  }
  .box h4{
    font-weight: 600;
  }
  .btn-explore{
    margin: 20px 0;
    background: transparent;
    border: 1px solid #b50005;
    color: #b50005;
    padding: 5px 8px;
    border-radius: 6px;
  }
  }

  @media (min-width: 769px) and (max-width: 1024px){
  .partner{
    width: 75px;
    height: 55px;
  }
  .partners{
    width: 90px;
    height: 80px;
  }
  #services{
    background: #18191f;
    padding: 5% 15%;
    font-size: 16px;
  }
  #services h3{
    font-size: 24px;
    color: #fff;
    font-weight: 800;
    text-align: center;
    margin: 60px 0;
  }
  .first-row{
    margin-bottom: 0;
  }
  .col-4{
    flex: 0 0 50%;
    max-width: 50%;
  }
  .box{
    width: 100%;
    height: 300px;
    background: #fff;
    border-radius: 8px;
    padding: 8% 6%;
    margin: 10px 0;
    font-size: 16px;
  }
  .serv{
    margin-bottom: 55px;
  }
  .box h4{
    font-weight: 600;
  }
  .btn-explore{
    margin: 20px 0;
    background: transparent;
    border: 1px solid #b50005;
    color: #b50005;
    padding: 5px 8px;
    border-radius: 6px;
  }
  }
</style>