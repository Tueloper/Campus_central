<template>
  <div class="content-sect">
      
  </div>
</template>
<style scoped>
body{
  font-family: 'Nunito Sans', sans-serif;
}
.card-login{
  position: relative;
    min-width: 0;
    word-wrap: break-word;
    background-color: #fff;
    background-clip: border-box;
    border: 1px solid rgba(0,0,0,.125);
    border-radius: .25rem;
    margin-bottom:3px;
    box-shadow: 1px 1px 4px 0px #cccccc;
}
.card-login img{
  width:100%
}
.card-login h1{
padding-bottom: 19px;
}
.mt-7{
  margin-top:5rem;
}
@media(max-width:900px){
  .card-login img{
    display:none;
  }
  .chat-row{
    display:block;
  }
}
.navBar{
  background: #2a3f54;
}
.navBar  a{
  color:#fff;
}
.m-auto {
  margin: 0 auto;
}
.color-red{
  color:#F31E1E
}
.p-5-30{
  padding:5px 30px;
}
.display-inline{
  display:inline-flex;
  margin-right: 12px;
}

.container- {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}
@media (min-width: 768px){
  .m-r-166{
    margin-right:170px;
  }
.side-bar{
  position: fixed;
  width: 196px;
  height: 100%;
  background: #2A3F54;
  padding-top: 30px;
  color: #fff;
  /* padding-left: 15px; */
  border-top: 8px solid #F31E1E;
  margin-top: 57px;
  font-weight:900;
  z-index: 1;
}

.content-sect{
  width: 69%;
  float: right;
  margin: 98px 167px 0 0px;
  border: 0px solid #ccc;
  padding: 48px;
  box-shadow: 0px 0px 3px 0px;
}
.content-sidebar{
  height:100%;
}
}

.side-bar ul{
  margin:0;
  padding: 0;
  list-style-type: none;

}
.side-bar li{
  padding: 5px 0px;
}
.side-bar a{
  color:#ffffff;
  text-decoration: none;
}
.side-bar i{
  padding-right:5px;
}
.side-bar li:hover{
  border-left: 3px solid #fff;
  padding-left: 25px;
  background: #F31E1E;
  padding: 14px 25px;
  transition: .5s ease;
}
.side-bar li{
  padding-left: 25px;
  padding: 14px 25px;
}
.bottom-footer{
  position: fixed;
  bottom:0;
  background: #d9dce0;
  width:100%;
  color:#000000;
  padding-bottom:5px;
  padding-top:10px;
}
.navTransparent{
  background:#2A3F54;
}
.navTransparent a{
  color:#fff;
  font-weight:bold;
}
@media (max-width: 767.98px){
.p-l30{
  padding-left:12px;
}
.displaynav-mobile{
  background: #000;
    margin-top: 56px;
    width: 176px;
    position: absolute;
    height: 100%;
    z-index:9;
}
.navbar-brand{
  padding-left:12px
}
.content-sect{
  padding: 27px;
  padding-top: 73px;
}
}
.active{
  border-left: 3px solid #fff;
  padding-left: 25px;
  background: #F31E1E;
  padding: 14px 25px;
  transition: .5s ease;
}

@media (min-width: 768px){
#sidebar {
    position: fixed;
    width: 248px;
    height: 100%;
    background: #000;
    left: -248px;
    transition: all 500ms linear;
    z-index: 9;
}
.logout{
  display: none;
}
.collapse:not(.show) {
  display: contents !important;
}
}
.bold{
  font-weight:bold;
}
.navbar-toggler-icon {
  padding-top: 8px;
  color: #fff;
}
.navbar-toggler{
  background:#F31E1E;
  
}
.img-sec{
  width:40%;
  border:1px solid #ccc;

}
.uni-content img{
  border:1px solid #ccc;
  width: 100%;
}
.uni-content h4{
  font-size:30px;
  font-weight:700;

}
.uni-content h5{
  font-weight:bold;
  font-size:20;
}
.rating-sec{
  display:flex;
}
.rating-sec p{
  padding-right:80px
}
.rating-sec i{
  color:#F31E1E;
}
.uni-content p{
  text-align:justify;
}
.btn-danger{
  background-color:#F31E1E;
  font-size: 14px;
}

.uni-content{
  border-bottom:1px solid #ccc;
  margin-bottom:4rem;
  padding-bottom:4rem;
}
.school-vibes h4{
  font-size:30px;
  font-weight:700;
}
.school-vibes img{
  border:1px solid #ccc;
  width: 100%;
}
.students-img{
  background-image: url(../);
  padding: 77px;
  background-size: cover;
}
.text-mid{
  margin-left:40px;
}
.mb-7{
  margin-bottom:7rem;
}
.comment-section{
  /* border-bottom:1px solid #ccc; */
  margin-bottom: 0.5rem;
  margin-top:2rem;
  padding-top:2rem;
}
.border-bottom {
  border-bottom:3px solid #F31E1E !important;
}
.chat-row{
  display: flex;
}
.chat-img{
  width: 0px;
  /* margin: 10px; */
  text-align: center;
  font-size: 30px;
  flex-grow: 1;
  margin:4px;
}
.chat-img img{
  height: 80px;
  width: 80px;
  
}
.chat-text{
  text-align: center;
  line-height: 75px;
  font-size: 30px;
  flex-grow: 7;
  margin:4px;
}
.tweet{
  background: #18C4EA;
    color: #fff;
    padding: 7px;
    border-radius: 4px;
}
.share{
  background: #324194;
    color: #fff;
    padding: 7px;
    border-radius: 4px;
}
.chat-social-icon{
  margin-bottom: 1.5rem;
  margin-top: 13px;
}
.navbar-nav {
margin-right: 10% !important;
}
.p-l-24{
  padding-left:24px;
}
.events-listing {
  padding:0px;
  list-style-type:none;
  width:100%;
}
.events-listing-text {
  background: #ccc;
  padding: 27px 9px 9px 9px;
} 

.events-listing-text h5{
  font-size: 35px;
  text-align: center;
  font-weight: bold;
  margin: 0;
}
.events-listing-text p{
  font-size: 21px;
  text-align: center;
  font-weight: normal;
  margin: 0;
}
.events-listing-content p{
  text-align:justify;
}
.events-listing-content h5{
  font-size:22px;
  font-weight:bold;
}
.m-l-auto{
  margin-left:auto;
}
.events-listing{
  box-shadow: 1px 1px 8px 2px #ccc;
  margin-top:9px;
 }
.events-page ul{
  padding:0;
  list-style-type: none;
}
.events-listing-content{
  padding-right:32px;
}

.events-readmore{
  box-shadow: 0px 0px 3px 0px;
  border: 0px solid #ccc;
}
.events-img img{
  width:100%;
}
.events-readmore {
  display:flex;
  
}
.events-img {
  flex-basis: 220px;
}
.event-detailed-page{
  flex-basis:200px;
  padding-left:16px;
  padding-top:10px;
}



.img-evt{
  background: url(../img/name_person.jpeg);
  width: 100px;
  background-size: cover;
  border: 246px;
  background-repeat: no-repeat;
  background-position: center;
}
.fs-16{
  font-size:16px !important;
}
.max-s{
  width: 100%;
    margin: 0;
}
.about-event h5{
  font-size: 27px;
  font-weight: bold;
  border-top: 2px solid #ccc;
  padding-top: 17px;
  color: #f31e1e;
}
.about-event p{
  text-align: justify;
}
.comment-event-pix{
  background-image: url(../img/name_person.jpeg);
    padding: 34px;
    background-size: cover;
    width: 100%;
    max-height: max-content;
}
.chat-text-box{
  text-align: center;
    line-height: 75px;
    font-size: 30px;
    flex-grow: 1;
    margin: 4px;
}
@media(max-width:700px){
  .mb-no-dis{
    display:block
  }
  .rate-school-btn{
    display:flex;
  }
  .card-login{
    margin: 0px;
  } 
  .p0{
    padding:0 !important;
    margin-top:9px;
  }
  .nodisplay-mb{
    display:none
  }
  .uni-content {
    border-bottom: 1px solid #ccc;
    margin-bottom: 1rem;
    padding-bottom: 0.7rem;
}
.events-listing-text {
  padding-top: 39px;
}
.btn-danger{
  padding:7px;
}
.comment-section{
  margin-top:0;
  padding-top:0;
}
.chat-img{
  width: 0px;
  /* margin: 10px; */
  text-align: center;
  font-size: 30px;
  flex-grow: 8;
  margin:4px;
}
.chat-img img{
  height:auto;
  width: 100%;
  
}
.fs-16{
  font-size:16px !important;
}
}
.b-b-1{
  border-bottom: 1px solid #ccc;
}
.bg-img{
  background: url(../img/girl-typing.jpg);
  background-size:cover;
  background-position: right;
}
@media (min-width: 1200px){
.container-min {
    max-width: 989px;
    }
  }


.heading{
  color: #000;
  font-size: 30px;
  font-weight:900;
}
.ml-0{
  margin-left:0px !important;
}
.ml-10{
  margin-left:10px;
}
</style>