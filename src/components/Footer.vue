<template>
  <div id="footer">
    <b-row>
      <b-col cols="5">
        <div class="d-flex foot">
          <img src="../assets/prenuer.png" alt="" class="ppr" />
          <div class="copy">
            <h6>
              Copyright &copy; 2021 PrenuerPulse Co.<br />
              All Rights Reserved
            </h6>
          </div>
          <div class="social d-flex">
            <Icons name="dribble" />
            <Icons name="twitter" />
            <Icons name="yt" />
            <Icons name="insta" />
          </div>
        </div>
      </b-col>
      <b-col cols="2">
        <h4>Company</h4>
        <ul class="footer-links">
          <li class="link-item">
            <a href="#header" class="link">About Us</a>
          </li>
          <li class="link-item">
            <a href="#contact" class="link">Contact Us</a>
          </li>
          <li class="link-item">
            <a href="#project" class="link">Projects</a>
          </li>
          <li class="link-item">
            <a href="#testimonial" class="link">Testimonials</a>
          </li>
        </ul>
      </b-col>
      <b-col cols="2">
        <h4>Support</h4>
        <ul class="footer-links">
          <li class="link-item">
            <a href="#" class="link">Help Center</a>
          </li>
          <li class="link-item">
            <a href="#" class="link">Terms of Service</a>
          </li>
          <li class="link-item">
            <a href="#" class="link">Privacy and Policy</a>
          </li>
        </ul>
      </b-col>
      <b-col cols="3">
        <h4>Stay up to Date</h4>
        <b-form class="d-flex">
          <b-form-group
            id="input-group-1"
            label-for="input-1"
          >
            <b-form-input
              id="input-1"
              type="email"
              placeholder="Your email address"
              required
            ></b-form-input>
          </b-form-group>
          <b-button type="submit" class="btn-send"><font-awesome-icon icon="paper-plane" /></b-button>
        </b-form>
      </b-col>
    </b-row>
  </div>
</template>

<script>
import Icons from './Icons.vue'

export default {
  name: "Footer",
  components: {
      Icons
  }
};
</script>

<style>
#footer {
  background: #0b0d17;
  color: #fff;
  padding: 80px 8%;
}
.foot {
  flex-direction: column;
}
.ppr {
  width: 85px;
  height: 45px;
  margin-bottom: 30px;
}
.copy {
  margin-bottom: 30px;
  color: #d9dbe1;
  font-weight: 400;
}
.social {
  width: 50%;
  justify-content: space-between;
}
.footer-links {
  margin: 0;
  padding: 0;
  list-style: none;
}
.link-item {
  margin-bottom: 20px;
}
.link {
  color: #d9dbe1;
}
.link:hover {
  color: #b50005;
  text-decoration: none;
}
form{
    background: #585858;
    widows: auto;
    border-radius: 8px;
    justify-content: space-between;
    margin-top: 35px;
}
.form-group{
    margin-bottom: 0px;
    width: 100%;
}
#input-1{
    background: none;
    color: #fff;
    border: none;
    width: 100%;
}
#input-1::placeholder{
    color: #fff;
}
#input-1:focus{
    outline: none;
    border: none;
}
.btn-send{
    background: transparent;
    border: none;
}

@media (max-width: 480px){
  #footer {
  background: #0b0d17;
  color: #fff;
  padding: 40px 12%;
}
.col-5{
  margin-bottom: 20px;
}
.col-5, .col-2, .col-3{
  max-width: 100%;
}
.ppr {
  width: 85px;
  height: 45px;
  margin-bottom: 30px;
}
.copy {
  margin-bottom: 30px;
  color: #d9dbe1;
  font-weight: 400;
}
.footer-links {
  margin: 0;
  padding: 0;
  list-style: none;
}
.link-item {
  margin-bottom: 20px;
}
.link {
  color: #d9dbe1;
}
.link:hover {
  color: #b50005;
  text-decoration: none;
}
form{
    background: #585858;
    widows: auto;
    border-radius: 8px;
    justify-content: space-between;
    margin-top: 35px;
}
.form-group{
    margin-bottom: 0px;
}
#input-1{
    background: none;
    color: #fff;
    border: none;
}
#input-1::placeholder{
    color: #fff;
}
#input-1:focus{
    outline: none;
    border: none;
}
.btn-send{
    background: transparent;
    border: none;
}
}

@media (min-width: 481px) and (max-width: 769px){
  #footer {
  background: #0b0d17;
  color: #fff;
  padding: 40px 12%;
}
.col-5{
  margin-bottom: 20px;
}
.col-5, .col-2, .col-3{
  max-width: 100%;
}
.ppr {
  width: 85px;
  height: 45px;
  margin-bottom: 30px;
}
.copy {
  margin-bottom: 30px;
  color: #d9dbe1;
  font-weight: 400;
}
.footer-links {
  margin: 0;
  padding: 0;
  list-style: none;
}
.link-item {
  margin-bottom: 20px;
}
.link {
  color: #d9dbe1;
}
.link:hover {
  color: #b50005;
  text-decoration: none;
}
form{
    background: #585858;
    widows: auto;
    border-radius: 8px;
    justify-content: space-between;
    margin-top: 35px;
}
.form-group{
    margin-bottom: 0px;
}
#input-1{
    background: none;
    color: #fff;
    border: none;
}
#input-1::placeholder{
    color: #fff;
}
#input-1:focus{
    outline: none;
    border: none;
}
.btn-send{
    background: transparent;
    border: none;
}
}

@media (min-width: 769px) and (max-width: 1024px){
  #footer {
  background: #0b0d17;
  color: #fff;
  padding: 40px 12%;
}
.col-5{
  margin-bottom: 20px;
}
.col-5, .col-2{
  max-width: 50%;
}
.col-3{
  max-width: 100%;
}
.ppr {
  width: 85px;
  height: 45px;
  margin-bottom: 30px;
}
.copy {
  margin-bottom: 30px;
  color: #d9dbe1;
  font-weight: 400;
}
.footer-links {
  margin: 0;
  padding: 0;
  list-style: none;
}
.link-item {
  margin-bottom: 20px;
}
.link {
  color: #d9dbe1;
}
.link:hover {
  color: #b50005;
  text-decoration: none;
}
form{
    background: #585858;
    widows: auto;
    border-radius: 8px;
    justify-content: space-between;
    margin-top: 35px;
}
.form-group{
    margin-bottom: 0px;
}
#input-1{
    background: none;
    color: #fff;
    border: none;
}
#input-1::placeholder{
    color: #fff;
}
#input-1:focus{
    outline: none;
    border: none;
}
.btn-send{
    background: transparent;
    border: none;
}
}
</style>