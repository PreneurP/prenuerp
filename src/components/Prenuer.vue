<template>
  <div id="why">
      <h3>Why choose Prenuer Pulse?</h3>
      <div class="why">
          <div class="images">
            <img src="../assets/robot.png" alt="" class="robot">
            <img src="../assets/cyan.png" alt="" class="cyan">
            <img src="../assets/pink.png" alt="" class="pink">
            <img src="../assets/hand.png" alt="" class="hand">
            <img src="../assets/prep.png" alt="" class="prep">
            <img src="../assets/green.png" alt="" class="green">
          </div>
          <div class="read">
              <div class="point">
                <h4>
                    <div class="cyan-dot"></div> Automation
                </h4>
                <p>We delight in building systems and softwares that resonate with your clients, users and stakeholders. This is why we make your business needs easy by automating all you do and how you do them.</p>
              </div>
              <div class="point mt-5">
                  <h4>
                      <div class="red-dot"></div> Innovation
                  </h4>
                  <p>With the ever changing demands of our clients and thier business needs, we ensure to keep you ahead of your competition by offering solutions that stays ahead of time. This is promised.</p>
              </div>
              <div class="point mt-5">
                  <h4>
                      <div class="green-dot"></div> Pulse Effect
                  </h4>
                  <p>Preneur Pulse brings back life into your idea and investment, just press play, then sit back relax and see us transform your ideas and business needs into steady flow of good returns on investment.</p>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Prenuer'
}
</script>

<style>
    #why{
        background: #fff;
        padding: 80px 8%;
        height: auto;
    }
    #why h3{
        font-size: 44px;
        color: #18191f;
        font-weight: 800;
        text-align: center;
        margin: 80px 0;
    }
    .why{
        display: flex;
        flex-direction: row;
    }
    .images{
        width: 50%;
    }
    .robot{
        position: relative;
        margin-top: 0%;
        margin-left: 28%;
    }
    .cyan{
        margin-top: -60%;
        margin-left: 75%;
    }
    .pink{
        margin-top: 20%;
        margin-right: 30%;
    }
    .hand{
        position: relative;
        margin-top: -60%;
        margin-left: 5%;
        z-index: 1000;
    }
    .prep{
        margin-top: -10%;
        margin-left: -20%;
        position: relative;
        z-index: 10000;
    }
    .green{
        margin-top: 10%;
    }
    .read{
        width: 50%;
        line-height: 40px;
    }
    .read h4{
        font-size: 32px;
        font-weight: 500;
        display: flex;
        align-items: center;
    }
    .cyan-dot{
        background: #A0DCFF;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .green-dot{
        background: #C1E5C0;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .red-dot{
        background: #b50005;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }

    @media (max-width: 320px){
            #why{
        background: #fff;
        padding: 40px 12%;
        height: auto;
    }
    #why h3{
        font-size: 20px;
        color: #18191f;
        font-weight: 800;
        text-align: center;
        margin: 40px 0;
    }
    .why{
        display: flex;
        flex-direction: column;
    }
    .images{
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .robot{
        position: relative;
        margin-top: 0%;
        margin-left: 0;
        width: 100px;
        height: 100px;
    }
    .cyan{
        margin-top: 0;
        margin-right: 0;
        display: none;
    }
    .pink{
        margin-top: 0%;
        margin-right: 30%;
        display: none;
    }
    .hand{
        position: relative;
        margin-top: 0%;
        margin-left: 7%;
        z-index: 1000;
        width: 100px;
        height: 100px;
    }
    .prep{
        margin-top: -10%;
        margin-left: 36%;
        position: relative;
        z-index: 10000;
        width: 50px;
        height: 50px;
        display: none;
    }
    .green{
        margin-top: 10%;
        display: none;
    }
    .read{
        margin-top: 50px;
        width: 100%;
        line-height: 40px;
    }
    .read h4{
        font-size: 20px;
        font-weight: 500;
        display: flex;
        align-items: center;
    }
    .read p{
        text-align: justify;
    }
    .cyan-dot{
        background: #A0DCFF;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .green-dot{
        background: #C1E5C0;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .red-dot{
        background: #b50005;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    }

    @media (min-width: 321px) and (max-width: 480px){
        #why{
        background: #fff;
        padding: 40px 12%;
        height: auto;
    }
    #why h3{
        font-size: 20px;
        color: #18191f;
        font-weight: 800;
        text-align: center;
        margin: 40px 0;
    }
    .why{
        display: flex;
        flex-direction: column;
    }
    .images{
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .robot{
        position: relative;
        margin-top: 0%;
        margin-left: 0;
        width: 120px;
        height: 120px;
    }
    .cyan{
        margin-top: 0;
        margin-right: 0;
        display: none;
    }
    .pink{
        margin-top: 0%;
        margin-right: 30%;
        display: none;
    }
    .hand{
        position: relative;
        margin-top: 0%;
        margin-left: 7%;
        z-index: 1000;
        width: 120px;
        height: 120px;
    }
    .prep{
        margin-top: -10%;
        margin-left: 36%;
        position: relative;
        z-index: 10000;
        width: 50px;
        height: 50px;
        display: none;
    }
    .green{
        margin-top: 10%;
        display: none;
    }
    .read{
        margin-top: 50px;
        width: 100%;
        line-height: 40px;
    }
    .read h4{
        font-size: 20px;
        font-weight: 500;
        display: flex;
        align-items: center;
    }
    .read p{
        text-align: justify;
    }
    .cyan-dot{
        background: #A0DCFF;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .green-dot{
        background: #C1E5C0;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .red-dot{
        background: #b50005;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    }

    @media (min-width: 481px) and (max-width: 768px){
        #why{
        background: #fff;
        padding: 50px 12%;
        height: auto;
    }
    #why h3{
        font-size: 22px;
        color: #18191f;
        font-weight: 800;
        text-align: center;
        margin: 50px 0;
    }
    .why{
        display: flex;
        flex-direction: column;
    }
    .images{
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .robot{
        position: relative;
        margin-top: 0%;
        margin-left: 0;
        width: 200px;
        height: 200px;
    }
    .cyan{
        margin-top: 0;
        margin-right: 0;
        display: none;
    }
    .pink{
        margin-top: 0%;
        margin-right: 30%;
        display: none;
    }
    .hand{
        position: relative;
        margin-top: 0%;
        margin-left: 7%;
        z-index: 1000;
        width: 200px;
        height: 200px;
    }
    .prep{
        margin-top: -7%;
        margin-left: 45%;
        position: relative;
        z-index: 10000;
        width: 80px;
        height: 80px;
        display: none;
    }
    .green{
        margin-top: 10%;
        display: none;
    }
    .read{
        margin-top: 50px;
        width: 100%;
        line-height: 40px;
    }
    .read h4{
        font-size: 20px;
        font-weight: 500;
        display: flex;
        align-items: center;
    }
    .read p{
        text-align: justify;
    }
    .cyan-dot{
        background: #A0DCFF;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .green-dot{
        background: #C1E5C0;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .red-dot{
        background: #b50005;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    }

    @media (min-width: 769px) and (max-width: 1024px){
        #why{
        background: #fff;
        padding: 50px 12%;
        height: auto;
    }
    #why h3{
        font-size: 22px;
        color: #18191f;
        font-weight: 800;
        text-align: center;
        margin: 50px 0;
    }
    .why{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        align-content: center;
    }
    .images{
        width: 100%;
        padding: 0 15%;
    }
    .robot{
        position: relative;
        margin-top: 0%;
        margin-left: 0;
        width: 250px;
        height: 250px;
    }
    .cyan{
        margin-top: 0;
        margin-right: 0;
        display: none;
    }
    .pink{
        margin-top: 0%;
        margin-right: 30%;
        display: none;
    }
    .hand{
        position: relative;
        margin-top: 0%;
        margin-left: 7%;
        z-index: 1000;
        width: 250px;
        height: 250px;
    }
    .prep{
        margin-top: -5%;
        margin-left: 45%;
        position: relative;
        z-index: 10000;
        width: 80px;
        height: 80px;
    }
    .green{
        margin-top: 10%;
        display: none;
    }
    .read{
        margin-top: 50px;
        width: 100%;
        line-height: 40px;
    }
    .read h4{
        font-size: 20px;
        font-weight: 500;
        display: flex;
        align-items: center;
    }
    .read p{
        text-align: justify;
    }
    .cyan-dot{
        background: #A0DCFF;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .green-dot{
        background: #C1E5C0;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .red-dot{
        background: #b50005;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    }

    @media (min-width: 1200px){
    .robot{
        position: relative;
        margin-top: 0%;
        margin-left: 0;
        width: 250px;
        height: 250px;
    }
    .cyan{
        margin-top: 0;
        margin-right: 0;
        display: none;
    }
    .pink{
        margin-top: 0%;
        margin-right: 30%;
        display: none;
    }
    .hand{
        position: relative;
        margin-top: -10%;
        margin-left: 19%;
        z-index: 1000;
        width: 250px;
        height: 250px;
    }
    .prep{
        margin-top: -5%;
        margin-left: 45%;
        position: relative;
        z-index: 10000;
        width: 80px;
        height: 80px;
    }
    .green{
        margin-top: 10%;
        display: none;
    }
    .read{
        margin-top: 50px;
        width: 100%;
        line-height: 40px;
    }
    .read h4{
        font-size: 20px;
        font-weight: 500;
        display: flex;
        align-items: center;
    }
    .read p{
        text-align: justify;
    }
    .cyan-dot{
        background: #A0DCFF;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .green-dot{
        background: #C1E5C0;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .red-dot{
        background: #b50005;
        height: 10px;
        width: 10px;
        border-radius: 50%;
        margin-right: 20px;
    }
    }
</style>