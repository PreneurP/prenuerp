<template>
  <div id="contact">
    <div class="contact">
      <div class="contact-text">
        <h4>
          Looking to design your new startup product and software?<br> or Looking to
          redesign your web and mobile application?<br> or StartUp Ideation?<br> Get
          started PreneurPulse!
        </h4>
        <a href="mailto:preneurpulse@gmail.com" class="btn-visit">Contact Us</a>
      </div>
      <div class="contact-images">
          <div class="first-img">
            <img src="../assets/img1.png" alt="">
            <img src="../assets/img2.png" alt="">
          </div>
        <img src="../assets/img3.png" alt="" class="end">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style>
#contact {
  background: #fff;
  padding: 80px 8%;
}
.contact {
  display: flex;
  flex-direction: row;
  align-items: center;
  background: #b50005;
  height: 280px;
  border-radius: 16px;
  padding: 20px 8%;
  padding-right: 0;
  color: #fff;
}
.contact-text{
    width: 70%;
    padding-right: 40px;
}
.contact-text h4{
    margin-bottom: 30px;
}
.contact-images{
    display: flex;
    flex-direction: row;
    width: 34.5%;
    justify-content: space-between;
}
.first-img{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.end{
    border-radius: 16px;
    display: flex;
    justify-content: flex-end;
}

@media (max-width: 480px){
  #contact {
  background: #fff;
  padding: 40px 8%;
}
.contact {
  display: flex;
  flex-direction: row;
  align-items: center;
  background: #b50005;
  height: auto;
  border-radius: 16px;
  padding: 20px 8%;
  color: #fff;
}
.contact-text{
    width: 100%;
    padding-right: 0px;
}
.contact-text h4{
  font-size: 16px;
    margin-bottom: 30px;
}
.contact-images{
    display: none;
    flex-direction: row;
    width: 30%;
}
.first-img{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.end{
    border-radius: 16px;
    display: flex;
    justify-content: flex-end;
}
}

@media (min-width: 481px) and (max-width: 768px){
  #contact {
  background: #fff;
  padding: 40px 8%;
}
.contact {
  display: flex;
  flex-direction: row;
  align-items: center;
  background: #b50005;
  height: auto;
  border-radius: 16px;
  padding: 20px 8%;
  color: #fff;
}
.contact-text{
    width: 100%;
    padding-right: 0px;
}
.contact-text h4{
  font-size: 16px;
    margin-bottom: 30px;
}
.contact-images{
    display: none;
    flex-direction: row;
    width: 30%;
}
.first-img{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.end{
    border-radius: 16px;
    display: flex;
    justify-content: flex-end;
}
}

@media (min-width: 769px) and (max-width: 1024px){
  #contact {
  background: #fff;
  padding: 40px 8%;
}
.contact {
  display: flex;
  flex-direction: row;
  align-items: center;
  background: #b50005;
  height: auto;
  border-radius: 16px;
  padding: 0px 8%;
  color: #fff;
}
.contact-text{
    width: 70%;
    padding-right: 40px;
}
.contact-text h4{
  font-size: 16px;
    margin-bottom: 30px;
}
.contact-images{
    display: flex;
    flex-direction: row;
    width: 30%;
    height: 100%;
}
.first-img{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
}
.end{
    border-radius: 16px;
    display: flex;
    justify-content: flex-end;
    display: none;
}
}

@media (min-width: 1025px) and (max-width: 1200px){
.contact-images{
    display: flex;
    flex-direction: row;
    width: 64.5%;
}
.first-img{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
}
.end{
  width: 100%;
    border-radius: 16px;
    display: flex;
    justify-content: flex-end;
}
}
</style>