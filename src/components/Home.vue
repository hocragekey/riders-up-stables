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
          <h1>Welcome to Rider's Up Stables!</h1>
      </div>
    </div>

    <div class="row at-row">
        <div class="col-md-24">
          <h2>We are a full service equistrian stable located in the beautiful West Palm area offering boarding in our beautiful 13 stall barn, horseback 
              riding lessons, boarding, trail rides, and other services to help give your horse a home.</h2>
      </div>
    </div>

    <div style="padding-top:10px;" class="row at-row">
      <div class="col-md-8">
        <h2>Boarding</h2>
        <p>We offer partial and full boarding at both a seasonal or annual frequency.  We have a beautiful 13 stall barn with an official size mirrored dressage arena, round pen, and grass paddocks.</p>
      </div>
      <div class="col-md-8">
        <h2>Lessons</h2>
        <p>We offer both english and western lessons to individuals or groups.  We also offer horse grooming and tacking lessons all by our very experienced in house trainer.</p>
      </div>
      <div class="col-md-8">
        <h2>Trail Rides</h2>
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


</style>
