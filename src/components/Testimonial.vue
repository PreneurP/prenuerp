<template>
  <div id="testimonial">
    <h3>Our Clients Speak</h3>
    <p class="tag">We have been working with clients around the world</p>
    <swiper ref="mySwiper" :options="swiperOption">
      <swiper-slide>
        <div class="slide">
          <h5>Efficient Collaboration</h5>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus libero ab modi quibusdam cupiditate amet vel nobis voluptatibus in, velit magni fugiat quam inventore quos provident optio ad tempora quidem!</p>
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
          <h5>Intuitive Design</h5>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro, atque delectus corrupti consectetur sapiente enim autem quis asperiores labore voluptatem repudiandae consequuntur inventore assumenda dicta, error id? Nostrum, veniam animi.</p>
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
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, nostrum! Iusto eaque praesentium, culpa veritatis in sed doloribus nulla accusamus quisquam numquam quos aperiam voluptates ad modi expedita non enim?</p>
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
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eius sunt accusantium fugit dolore repellat omnis iusto quisquam, sed aliquam atque? Minus vero ad, quasi at reprehenderit ea neque debitis exercitationem?</p>
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