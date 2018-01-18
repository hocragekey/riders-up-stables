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
      <p class="big-p">Our facility has 21 high quality stalls on 5 acres with a house, an official size dressage arena with GT Grade #1 footing, foot mirrors, a viewing gazebo, and a round pen.  All stalls are large with pads, water to each, fans and fly spray system.  We have two air-conditioned tack rooms, one with a washer and dryer.  There are multiple paddocks, of various sizes to suit your needs.  We have a manager on site 24/7.  Our horses enjoy a safe, comfortable and relaxed environment in the barn and in the paddocks.</p>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Location</h1>
      <p class="big-p">
         We are in the Wildwood Equestrian Community, 19498 Green Grove Ct, Loxahatchee, Florida 33470. hacking distance to White Fences, and a 20 minute drive to Global in Wellington.
      </p><br/><br />
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6854.252042393191!2d-80.35697084836086!3d26.742646915653953!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88d9315a5d4f40ed%3A0x61840c7650dc3c07!2s19498+Green+Grove+Ct%2C+Loxahatchee%2C+FL+33470!5e0!3m2!1sen!2sus!4v1512527705005" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Boarding / Grooming</h1>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <p class="big-p">We would like to build quality relationships with our boarders and their horses so we may provide the best of care.  We offer Full Board:  Seasonal: $1800/mo Annual: $850/mo and Dry Board: Seasonal: $850/mo Annual: $500/mo</p>
     </div>
    <div class="col-md-2"></div>
    
    <div class="col-md-8">
        <div class="boarding-grooming"></div>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Lessons</h1>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-8">
        <div class="lessons"></div>
    </div>
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <p class="big-p">We have an experienced trainer, Daniel, who is available for lessons in Dressage, Hunter Jumper, as well as Western Pleasure, the rate is $60/hr. Our trainer can also break and train horses fee commensurate with specific needs.  We also teach horse care, frooming, tacking and health care pointers.</p>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Trail Rides</h1>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <p class="big-p">We have trail rides on and around the property as well as miles of trails along a canal.  We also have access to white fences where there is a 3 miles loop.  Our guided rides are $50/hour, $80 for 2 hours.</p>
     </div>
    <div class="col-md-2"></div>
    
    <div class="col-md-8">
        <div class="trail-rides"></div>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>House on Property</h1>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-8">
        <div class="boarding-grooming"></div>
    </div>
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <p class="big-p">Our house is a 3 bed/2 bath facility with washer and dyer and a salt water pool.  In season it rents for $300 a month plus utilities.  The season runs from Dec 1st to April 30th.  Off season it can be rented by the week or weekend - call for rates.</p>
    </div>
    <div class="col-md-2"></div>
  </div>


  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Staff</h1>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <p class="big-p">Our staff includes owners: Paul and Caryl, our trainer Daniel; our stable manager Skylar; and Kenna, Michaela, and Hailey, our assistants</p>
     </div>
    <div class="col-md-2"></div>
    
    <div class="col-md-8">
        <div class="boarding-grooming"></div>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-24">
      <h1>Our Horses</h1>
    </div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-8">
        <div class="boarding-grooming"></div>
    </div>
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <h3>Papa</h3><p class="big-p">Our star retired Thoroughbred, 13 years old who is gentle and easy and who has been trained for spcial needs children, lessons and trail rides.</p>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <h3>Gina</h3><p class="big-p">An 11 year retired Thoroughbred who loves lessons and trails and is full of spunk for the experienced rider.</p>
     </div>
    <div class="col-md-2"></div>
    
    <div class="col-md-8">
        <div class="boarding-grooming"></div>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-8">
        <div class="golly"></div>
    </div>
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <h3>Golly</h3><p class="big-p">An 11 year old retired Thoroughbred who loves lessons and is beautiful for photography.</p>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <h3>Apollo</h3><p class="big-p">A 5 years old Arabian with a prance and dancing gait and a joy to ride.</p>
     </div>
    <div class="col-md-2"></div>
    
    <div class="col-md-8">
        <div class="boarding-grooming"></div>
    </div>
    <div class="col-md-2"></div>
  </div>

  <div class="row at-row main-section">
    <div class="col-md-2"></div>
    <div class="col-md-8">
        <div class="boarding-grooming"></div>
    </div>
    <div class="col-md-2"></div>
    <div class="col-md-10">
      <h3>Tilly</h3><p class="big-p">Our almost 3 years old Thoroughbred with her blond mane and long legs is still in training.</p>
    </div>
    <div class="col-md-2"></div>
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
      <p class="dark-bg-text"><i class="fa fa-facebook-square fa-3x" aria-hidden="true"></i> <i style="padding-left:10px;" class="fa fa-twitter-square fa-3x" aria-hidden="true"></i></p>
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
    background-repeat: no-repeat;
}

.lessons {
    background-image: url('./../assets/imgs/IMG_0027.jpg');
    padding-top: 280px;
    color: white;
    background-repeat: no-repeat;
}

.trail-rides {
    background-image: url('./../assets/imgs/DSC00756.jpg');
    padding-top: 280px;
    color: white;
    background-repeat: no-repeat;
}

.golly {
    background-image: url('./../assets/imgs/DSC00750.jpg');
    padding-top: 280px;
    color: white;
    background-repeat: no-repeat;
}

h1 {
  font-size:46px;
  font-weight:400;
}

h2 {
  font-size:26px;
  font-weight:100;
}

h3 {
  font-size:22px;
}

h4 {
  font-size: 18px;
  font-weight: bold;
}

.slider-div {
  overflow: hidden;
}

.main-section {
  padding-top:15px;
}

.big-p {
  font-size:18px;
  padding-top: 30px;
}

.big-p-no-pad {
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
