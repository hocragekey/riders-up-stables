<template>
  <div>
    <div class="row at-row">
      <div class="col-md-24">
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

    <div style="padding-top:10px;" class="row at-row">
        <div class="col-md-24">
          <h1 style="font-size:24px">Welcome to Rider's Up Stables!</h1>
      </div>
    </div>

    <div style="padding-top:10px;" class="row at-row">
        <div class="col-md-2"></div>
        <div class="col-md-20">
          <p style="font-size:18px"> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
      <div class="col-md-2"></div>
    </div>

    <div style="padding-top:10px;" class="row at-row">
        <div class="col-md-1"></div>
      <div class="boarding-grooming col-md-11">
          <div style="background-color:black"><h2 style="color:white;">Boarding / Grooming</h2>
        <p style="color:white;">We offer partial and full boarding at both a seasonal or annual frequency.  We have a beautiful 13 stall barn with an official size mirrored dressage arena, round pen, and grass paddocks.</p>
      </div>
        
      </div>
      <div class="col-md-12">
        <h2>Trail Rides</h2>
        <p>We have beautfiul locations for small group trail rides. </p>
      </div>
    </div>

    <div style="padding-top:10px;" class="row at-row">
      <div class="col-md-12">
        <h2>Another Service</h2>
        
      </div>
      <div class="col-md-12">
        <h2>Another Service</h2>
        <p>We have beautfiul locations for small group trail rides. </p>
      </div>
    </div>

    <div style="padding-top:20px;margin-top:20px;background-color:#2F2C2C;height:400px;" class="row at-row">
        <div class="col-md-8">
            <h1 style="color: white">What We Do</h1>
            <p style="color: white">We are located in West Palm Florida</p>
        </div>
      <div class="col-md-8">
        <h1 style="color: white">Get In Touch</h1>
        <p style="color: white">We are located in West Palm Florida</p>
      </div>
      <div class="col-md-8">
        <h1 style="color: white">Social Media</h1>
        <p style="color: white">We have beautfiul locations for small group trail rides. </p>
      </div>
    </div>
  </div>

</template>

<script>
  export default {
    name: 'Home',
    data() {
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

</style>
