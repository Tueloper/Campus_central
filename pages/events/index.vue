<template>
  <div>
    <b-container fluid>
      <div class="content-sect">
        <div class="events-page">
            <h4 class="heading ml-10">Events</h4>
            <div class="row  m-l-auto">
              <div class="col-md-6 col-sm-6 col-xs-6 ">
                <div class="">
                  <ul >
                    <eventPost id="1" 
                    day="13th" 
                    month="Jan, 2020"
                    title="Campus Central" 
                    previewText="Lorem ipsum dolor sit amet consectur adipisicing elit. Placeat, aliquammoles tiae. Lorem ipsum dolor sit amet consectur adipisicing elit." />
                   <eventPost id="2" 
                    day="13th" 
                    month="Jan, 2020"
                    title="Campus Central" 
                    previewText="Lorem ipsum dolor sit amet consectur adipisicing elit. Placeat, aliquammoles tiae. Lorem ipsum dolor sit amet consectur adipisicing elit." />
                   
                  </ul>
                </div>
              </div>
              <div class="col-md-6 col-12 col-xs-12 ">
                <div class="events-listing p-3">
                  <ul >
                    <li class="">
                      <div class="row max-s">
                        <div class="col-md-4 col-4 img-evt events-listing-text">
                        <!-- <img src="img/name_person.jpeg" width="100%">                        -->
                        </div>
                        <div class="col-md-8 col-8 events-listing-content pt-3">
                            <p class="m-0">Aug. 30th, 2020 </p>
                          <h5 class="fs-16">Uniuyo Host Davido</h5>
                          <p>Time:<span>8:30am</span>   </p>
                          <div><span>Free</span>   <a href="#" class="btn btn-danger ">Register</a> </div>
                        </div>
                      </div>
                    </li>
                  </ul>
                  
                <div class="about-event">
                  <h5 class="sub-heading">About this Event</h5>
                  <p>Lorem ipsum dolor sit amet consectur adipisicing elit. 
                    Placeat, aliquammoles tiae.  
                    Lorem ipsum dolor sit amet consectur adipisicing elit. 
                    Placeat, aliq Lorem ipsum dolor sit amet consectur adipisicing elit. 
                    Placeat, aliquammoles tiae.  
                    Lorem ipsum dolor sit amet consectur adipisicing elit. Placeat, aliq
                  </p>
                  
                        <div class="row wow fadeIn">
                            <div class="col-md-3 col-3">
                              <div class="comment-event-pix"></div>
                            </div>
                            <div class="col-md-9 col-9">
                              <h4>Sarah Connor</h4>
                              <p>I could love to go to this school </p>
                              <div class="rating-sec">
                                <p><i class="fa fa-star"></i><span>0</span></p>
                                <p><i class="fa fa-star"></i><span>0</span></p>
                              </div>
                            </div>
                          </div>
                          <div class="">
                            <h5><b>Add a comment</b></h5>
                            <div class="">
                              <span class="border-bottom">3 comments</span>
                              <span class="text-mid"><b class="color-red">Campus Central</b></span>
                              <span class="pull-right"><i class="fa fa-user"></i>Admin</span>
                            </div>
                          </div>
                          <div class="chat-social-icon">
                            <i class="fa fa-facebook share"> share</i>
                            <i class="fa fa-twitter tweet"> tweet</i>
                          </div>
                
                          <div class="chat-row mb-no-dis">
                            <div class="chat-img">
                              <img src="img/name_person.jpeg">
                            </div>
                            <div class="chat-text-box ml-3">
                              <form>
                                  <div class="form-group">
                                      <textarea class="form-control " type="text" placeholder="Join the discussion"></textarea>
                                    </div>
                                    <div class="text-right">
                                        <button type="submit" class="p-5-30 btn btn-danger">Submit</button>
                                        </div>  
                              </form>
                            </div>
                          </div>
                  </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </b-container>
  </div>
</template>


<script >
import eventPost from '@/components/eventsPost/eventPost'
export default{
  components:{
    eventPost: eventPost,
}
}
</script>
<style scoped>
@media (max-width: 767.98px){
  .content-sect{
  padding: 27px;
  padding-top: 73px;
}
}
.content-sect{
      width: 78%;
    float: right;
    margin: 101px 32px 0 22px;
    border: 0px solid #ccc;
    padding: 48px;
    box-shadow: 0px 0px 3px 0px;
}
.heading{
  color: rgb(0, 0, 0);
    font-size: 30px;
    font-weight: 900;
}
.card {
    position: relative;
    display: flex;
    flex-direction: column;
    min-width: 0px;
    overflow-wrap: break-word;
    background-color: rgb(255, 255, 255);
    background-clip: border-box;
    border-width: 1px;
    border-style: solid;
    border-color: rgba(0, 0, 0, 0.125);
    border-image: initial;
    border-radius: 0.25rem;
}
.result-container {
    padding: 20px;
    margin: 10px 0px;
}
.events-listing {
    padding: 0px;
    list-style-type: none;
    width: 100%;
}
.events-listing {
    box-shadow: 1px 1px 8px 2px #ccc;
    margin-top: 9px;
}
.events-listing {
    padding: 0px;
    list-style-type: none;
    width: 100%;
}
.events-listing-text {
    background: #ccc;
    padding: 27px 9px 9px 9px;
}
.events-listing-content {
    padding-right: 32px;
}
.events-page ul {
    padding: 0;
    list-style-type: none;
}
.events-listing-text h5 {
    font-size: 35px;
    text-align: center;
    font-weight: bold;
    margin: 0;
}
.events-listing-text p {
    font-size: 21px;
    text-align: center;
    font-weight: normal;
    margin: 0;
}
.events-listing-content h5 {
    font-size: 22px;
    font-weight: bold;
}
.events-listing-content h5 {
    font-size: 22px;
    font-weight: bold;
}
.about-event h5 {
    font-size: 27px;
    font-weight: bold;
    border-top: 2px solid #ccc;
    padding-top: 17px;
    color: #f31e1e;
}
.about-event p {
    text-align: justify;
}
.rating-sec {
    display: flex;
}
.border-bottom {
    border-bottom: 3px solid #F31E1E !important;
}
.text-mid {
    margin-left: 40px;
}
.share {
    background: #324194;
    color: #fff;
    padding: 7px;
    border-radius: 4px;
}
.tweet {
    background: #18C4EA;
    color: #fff;
    padding: 7px;
    border-radius: 4px;
}
.chat-social-icon {
    margin-bottom: 1.5rem;
    margin-top: 13px;
}
.rating-sec i {
    color: #F31E1E;
}
.rating-sec p {
    padding-right: 80px;
}
.img-evt {
    /* background: url(assests/img/pple.jpeg); */
    width: 100px;
    background-size: cover;
    border: 246px;
    background-repeat: no-repeat;
    background-position: center;
}
</style>