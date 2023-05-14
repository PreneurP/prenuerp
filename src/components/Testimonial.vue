<template>
  <div id="testimonial">
    <h3>Our Clients Speak</h3>
    <p class="tag">We have been working with clients around the world</p>
    <swiper ref="mySwiper" :options="swiperOption">
      <swiper-slide>
        <div class="slide">
          <h5>Efficient Collaboration</h5>
          <p>We would like to express our satisfaction on the cooperation regarding the development of our web application and the tailor made training. You and your development team did a very professional job. We are satisfied with the solution given to us and with the communication flow through the project.</p>
        </div>
        <div class="author">
            <img src="../assets/User1.png" alt="" class="aut">
            <div class="name">
                <h6>Chioma</h6>
                <span>CEO of ABC Corporation</span>
            </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="slide">
          <h5>Intuitive Design</h5>
          <p>It was an awesome experience having prenuer plus handle our website, Kudos to the Tech team for all their quick response towards my observations during the process, am grateful and very much willing to recommend my colleagues to prenuer plus.:raised_hands:</p>
        </div>
        <div class="author">
            <img src="../assets/User1.png" alt="" class="aut">
            <div class="name">
                <h6>John Doe</h6>
                <span>CEO of ABC Corporation</span>
            </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="slide">
          <h5>Mindblowing Service</h5>
          <p> Working with your team has been a good learning curve for my company. The professionalism and the quality relationship built during the development of my app was second to none. I'm recommending your team for any project. Yeah your strategies on having a better product offerings is also working well for the business. Thank you</p>
        </div>
        <div class="author">
            <img src="../assets/User1.png" alt="" class="aut">
            <div class="name">
                <h6>John Doe</h6>
                <span>CEO of ABC Corporation</span>
            </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="slide">
          <h5>Meet Deadline</h5>
          <p>Thanks to your team for their wonderful job on helping me develop a software program. Everyone were good at what they do, professional, hardworking and kind. Thanks to them my software program is up and running. I recommend them anytime any day. Keep up the good work PreneurPulse, I look forward to working with you in the future projects.</p>
        </div>
        <div class="author">
            <img src="../assets/User1.png" alt="" class="aut">
            <div class="name">
                <h6>John Doe</h6>
                <span>CEO of ABC Corporation</span>
            </div>
        </div>
      </swiper-slide>
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
import { Swiper, SwiperSlide, directive } from "vue-awesome-swiper";
import "swiper/css/swiper.css";

export default {
  name: "Testimonial",
  components: {
    Swiper,
    SwiperSlide,
  },
  directives: {
    swiper: directive,
  },
  data() {
    return {
      swiperOption: {
        slidesPerView: 3.2,
        spaceBetween: 50,
        pagination: {
          el: ".swiper-pagination",
          clickable: true,
        },
        loop: true,
        autoplay: {
          delay: 2000,
        },
        speed: 500,
        breakpoints: {
          1024: {
            slidesPerView: 3.1,
            spaceBetween: 40,
          },
          768: {
            slidesPerView: 2.2,
            spaceBetween: 30,
          },
          640: {
            slidesPerView: 1,
            spaceBetween: 20,
          },
          320: {
            slidesPerView: 1,
            spaceBetween: 30,
          },
        },
      },
    };
  },
};
</script>

<style>
#testimonial {
  background: #f4f5f7;
  padding: 40px 8%;
}
#testimonial h3 {
  font-size: 44px;
  color: #18191f;
  font-weight: 800;
  text-align: center;
  margin: 80px 0;
  margin-bottom: 20px;
}
.tag {
  font-size: 20px;
  text-align: center;
  font-weight: 500;
}
.swiper-container{
  width: 100%;
}
.slide{
    width: 100%;
    height: auto;
    padding: 8%;
    background: #fff;
    text-align: center;
    margin-bottom: 20px;
}
.author{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    text-align: center;
}
.aut{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    margin-bottom: 10px;
}
.name{
    line-height: 10px;
}
.name h6{
    font-weight: 800;
}
.name span{
    font-weight: 300;
    font-size: 12px;
}
.swiper-pagination{
    position: relative;
    margin-top: 20px;
}

@media (max-width: 480px){
  .swiper-container{
    width: 100%;
  }
}
</style>
