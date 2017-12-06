<template>
<div>
  <div class="row at-row">
    <!-- TODO: need to make images 400 height -->
    <div class="col-md-24 slider-div" style="">
      <swiper :options="swiperOption">
        <swiper-slide>
          <div>
            <img src="./../assets/imgs/DSC09077.jpg" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div>
            <img src="./../assets/imgs/DSC09750.jpg" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div>
            <img src="./../assets/imgs/DSC09778.jpg" />
          </div>
        </swiper-slide>
        <div class="swiper-pagination" slot="pagination"></div>
        <div class="swiper-button-prev" slot="button-prev"></div>
        <div class="swiper-button-next" slot="button-next"></div>
      </swiper>

    </div>

  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Welcome to Rider's Up Stables!</h1>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h2>Our Primary Goal:  A fun and safe riding experience</h2>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-20">
      <p class="big-p">Our facility is a 13 stall barn on 5 acres with a house, an official size dressage arena with GT Grade #1 footing and soon to have a roof constructed, foot mirrors, a viewing gazebo, and a round pen. All stalls are large with pads, water to each,
        fans and fly spray system. We have two air-conditioned tack rooms, one with a washer and dryer. There are multiple paddocks, of various sizes to suit your needs. We have a manager on site 24/7. Our horses enjoy a safe, comfortable and relaxed
        environment in the barn and in the paddocks.</p>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-1"></div>
    <div class="boarding-grooming col-md-10">
      <div style="background-color:black">
        <h3 style="color:white;">Boarding / Grooming</h3>
        <p style="color:white;">We offer partial and full boarding at both a seasonal or annual frequency. We have a beautiful 13 stall barn with an official size mirrored dressage arena, round pen, and grass paddocks.</p>
      </div>

    </div>
    <div class="col-md-1"></div>
    <div class="boarding-grooming col-md-11">
      <div style="background-color:black">
        <h3 style="color:white;">Boarding / Grooming</h3>
        <p style="color:white;">We offer partial and full boarding at both a seasonal or annual frequency. We have a beautiful 13 stall barn with an official size mirrored dressage arena, round pen, and grass paddocks.</p>
      </div>

    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-1"></div>
    <div class="boarding-grooming col-md-10">
      <div style="background-color:black">
        <h3 style="color:white;">Boarding / Grooming</h3>
        <p style="color:white;">We offer partial and full boarding at both a seasonal or annual frequency. We have a beautiful 13 stall barn with an official size mirrored dressage arena, round pen, and grass paddocks.</p>
      </div>

    </div>
    <div class="col-md-1"></div>
    <div class="boarding-grooming col-md-10">
      <div style="background-color:black">
        <h3 style="color:white;">Boarding / Grooming</h3>
        <p style="color:white;">We offer partial and full boarding at both a seasonal or annual frequency. We have a beautiful 13 stall barn with an official size mirrored dressage arena, round pen, and grass paddocks.</p>
      </div>

    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Location</h1>
      <p>
         We are in the Wildwood Equestrian Community, 19498 Green Grove Ct, Loxahatchee, Florida 33470. hacking distance to White Fences, and a 20 minute drive to Global in Wellington.
      </p>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Our Staff</h1>
    </div>

    </div>
    <div class="row at-row">
      <div class="col-md-12">
        <h3>Paul Rubin</h3>
        <p>
          Blurb about Warren
        </p>
      </div>
      <div class="col-md-12">
        <h3>Caryl Lebonitte</h3>
        <p>
          Blurb about Caryl
        </p>
      </div>

    </div>

  <div class="row at-row footer">
    <div class="col-md-8">
      <h3 class="dark-bg-text">What We Do</h3><br />
      <p class="dark-bg-text">We are a full-service equestrain ranch for lessons, boarding, training, and group rides.</p>
    </div>
    <div class="col-md-8">
      <h3 class="dark-bg-text">Get In Touch</h3><br />
      <p class="dark-bg-text">19498 Green Grove Court<br/>


                      Loxahatchee, Florida    <br/>

                      561-777-3761    </p>
    </div>
    <div class="col-md-8">
      <h3 class="dark-bg-text">Social Media</h3><br />
      <p class="dark-bg-text">We have beautfiul locations for small group trail rides. </p>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        nextButton: '.swiper-button-next',
        prevButton: '.swiper-button-prev',
        paginationClickable: true,
        spaceBetween: 30,
        autoplayDisableOnInteraction: false
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" type="text/scss" scoped>
.boarding-grooming {
    background-image: url('./../assets/imgs/DSC09881.jpg');
    height: 350px;
    padding-top: 280px;
    color: white;
}

h1 {
  font-size:46px;
  font-weight:400;
}

h2 {
  font-size:26px;
  font-weight:100;
}

.slider-div {
  overflow: hidden;
}

.main-section {
  padding-top:15px;
}

.big-p {
  font-size:18px;
}

.footer {
  padding-top:20px;
  margin-top:20px;
  background-color:#2F2C2C;
  height:400px;
}

.dark-bg-text {
  color:white;
}
</style>
