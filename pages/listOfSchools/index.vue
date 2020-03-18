<template>
    
    <div>
      <b-container fluid>
        <div class="content-sect mb-7  ">
        <div class="uni-content wow fadeIn ">
          <div class="row">
            <div class="col-md-5">
              <img src="img/unilag.jpg">
            </div>
            <div class="col-md-7">
              <h3 class="search-title">University of Uyo</h3>
              <h4 class="search-subtitle">Akwa Ibom State Nigeria</h4>
              <p>Brief comment about the school
                  Brief comment about the school
                  Brief comment about the school
                  Brief comment about the schoolBrief comment about the schoolBrief
                  comment about the schoolBrief comment about the school
                  Brief comment about the school
              </p>
              <div class="rating-sec">
                <p><i class="fa fa-star"></i><span>0</span> Rate</p>
                <p><i class="fa fa-comments"></i><span>0</span> Comments</p>
              </div>
              <div class="rate-school-btn">
                  <a href="#" class=" text-center btn btn-danger">Rate this campus</a>
                  <a href="#"  class="text-center ml-5 btn btn-danger">Share</a>
              </div>
            </div>
          </div>
        </div>
          <div class="school-vibes ">
            <h4 class="mb-5 sub-heading">Vibes about University of Uyo</h4>
            <div class="row wow fadeIn">
                <div class="col-md-3 col-4">
                  <div class="">
                    <img src="img/name_person.jpeg">
                  </div>
                </div>
                <div class="col-md-5 col-8 ">
                  <h4 class="fs-16">Sarah Connor</h4>
                  <p>I could love to go to this school </p>
                  <div class="rating-sec">
                    <p><i class="fa fa-thumbs-up"></i><span>0</span></p>
                    <p><i class="fa fa-thumbs-down"></i><span>0</span></p>
                  </div>
                </div>
            </div>
            <div class="comment-section b-b-1">
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
            <div class="chat-row">
              <div class="chat-img">
                <img src="img/name_person.jpeg">
              </div>
              <div class="chat-text ml-3">
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
      </b-container>
    </div>
</template>
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
      margin: 101px 22px 0 22px;
      border: 0px solid #ccc;
      padding: 48px;
      box-shadow: 0px 0px 3px 0px;
      margin-bottom: 77px;
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
.uni-content h4 {
    font-weight: 500;
    font-size: 14px;
    font-weight: 900;
}
.search-title{
  font-size: 30px;
    font-weight: 700;
    margin: 0;
}
.uni-content {
    border-bottom: 1px solid #ccc;
    margin-bottom: 4rem;
    padding-bottom: 4rem;
}
.rating-sec {
    display: flex;
}
.rating-sec i {
    color: #F31E1E;
}
.btn-danger {
    background-color: #F31E1E;
    font-size: 14px;
}
.school-vibes h4 {
    font-size: 30px;
    font-weight: 700;
}
.comment-section {
    margin: 30px 0;
}
.border-bottom {
    border-bottom: 3px solid #F31E1E !important;
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
.comment-section {
    margin: 20px 0;
}

.b-b-1 {
    border-bottom: 1px solid #ccc;
}
.rating-sec p {
    padding-right: 80px;
}
</style>