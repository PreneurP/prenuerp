<template>
  <div id="project">
      <h3>Recent Projects</h3>
      <div class="projects">
          <div class="box1">
              <div class="site">
                  <div class="txt">
                  </div>
                  <a href="https://paypaddi.com" target="_blank" class="btn-visit"><strong>Visit</strong></a>
              </div>
          </div>
          <div class="box2">
              <div class="site">
                  <div class="txt">
                  </div>
                  <a href="https://panuelmfbank.com" target="_blank" class="btn-visit"><strong>Visit</strong></a>
              </div>
            </div>
          <div class="box3">
              <div class="site">
                  <div class="txt">
                  </div>
                  <a href="https://raudhafoundations.com" target="_blank" class="btn-visit"><strong>Visit</strong></a>
              </div>
            </div>
          <div class="box4">
              <div class="site">
                  <div class="txt">
                  </div>
                  <a class="btn-visit" target="_blank" href="https://blockvilla.grayscaleintl.com"><strong>Visit</strong></a>
              </div>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Project'
}
</script>

<style>
a{
    text-decoration: inherit;
}
    #project{
        padding: 40px 8%;
        background: #fff;
        position: relative;
    }
    #project h3{
        font-size: 44px;
        color: #18191f;
        font-weight: 800;
        text-align: left;
        margin: 80px 0;
    }
    .projects{
        display: grid;
        height: 950px;
        grid-template-columns: repeat(6, 1fr);
        grid-template-rows: repeat(8, 1fr);
        grid-gap: 20px;
        color: #fff;
        font-weight: 300;
    }
    .box1{
        grid-row: span 4;
        grid-column: span 3;
        background: url('../assets/cover1.jpg');
        padding: 4%;
        background-size: cover;
    }
    .box2{
        grid-row: span 4;
        grid-column: span 3;
        background: url('../assets/cover2.jpg');
        background-size: cover;
        padding: 4%;
    }
    .box3{
        grid-row: span 4;
        grid-column: span 3;
        background: url('../assets/cover3.jpg');
        background-size: cover;
        padding: 4%;
    }
    .box4{
        grid-row: span 4;
        grid-column: span 3;
        background: url('../assets/cover4.jpg');
        background-size: cover;
        padding: 4%;
    }
    .site{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
    }
    .lang{
        font-size: 12px;
        color: #c4c4c4;
    }
    .btn-visit{
        background: #1d1d1d;
        color: #fff;
        padding: 12px 32px;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-weight: 500;
    }
    .btn-visit:hover{
        background:#b50005;
        color: #fff;
    }

    @media (max-width: 480px){
        #project{
        padding: 40px 8%;
        background: #fff;
        position: relative;
    }
    #project h3{
        font-size: 20px;
        color: #18191f;
        font-weight: 800;
        text-align: left;
        margin: 40px 0;
    }
    .projects{
        display: grid;
        height: 950px;
        grid-template-columns: repeat(6, 1fr);
        grid-template-rows: repeat(24, 1fr);
        grid-gap: 20px;
        color: #fff;
        font-weight: 300;
    }
    .box1{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .box2{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .box3{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .box4{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .site{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
    }
    .lang{
        font-size: 12px;
        color: #c4c4c4;
    }
    .btn-visit{
        background: #fff;
        color: #b50005;
        padding: 8px 15px;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-weight: 500;
    }
    }

    @media (min-width: 480px) and (max-width: 768px){
        #project{
        padding: 50px 8%;
        background: #fff;
        position: relative;
    }
    #project h3{
        font-size: 22px;
        color: #18191f;
        font-weight: 800;
        text-align: left;
        margin: 40px 0;
    }
    .projects{
        display: grid;
        height: 950px;
        grid-template-columns: repeat(6, 1fr);
        grid-template-rows: repeat(24, 1fr);
        grid-gap: 20px;
        color: #fff;
        font-weight: 300;
    }
    .box1{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .box2{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .box3{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .box4{
        grid-row: span 6;
        grid-column: span 6;
        padding: 4%;
    }
    .site{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
    }
    .lang{
        font-size: 12px;
        color: #c4c4c4;
    }
    .btn-visit{
        background: #fff;
        color: #b50005;
        padding: 8px 15px;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-weight: 500;
    }
    }

    @media (min-width: 769px) and (max-width: 1024px){
        #project{
        padding: 60px 8%;
        background: #fff;
        position: relative;
    }
    #project h3{
        font-size: 24px;
        color: #18191f;
        font-weight: 800;
        text-align: left;
        margin: 40px 0;
    }
    .projects{
        display: grid;
        height: 950px;
        grid-template-columns: repeat(6, 1fr);
        grid-template-rows: repeat(12, 1fr);
        grid-gap: 20px;
        color: #fff;
        font-weight: 300;
    }
    .box1{
        grid-row: span 4;
        grid-column: span 3;
        padding: 4%;
    }
    .box2{
        grid-row: span 4;
        grid-column: span 3;
        padding: 4%;
    }
    .box3{
        grid-row: span 4;
        grid-column: span 3;
        padding: 4%;
    }
    .box4{
        grid-row: span 4;
        grid-column: span 3;
        padding: 4%;
    }
    .site{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
    }
    .lang{
        font-size: 12px;
        color: #c4c4c4;
    }
    .btn-visit{
        background: #fff;
        color: #b50005;
        padding: 8px 15px;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-weight: 500;
    }
    }
</style>