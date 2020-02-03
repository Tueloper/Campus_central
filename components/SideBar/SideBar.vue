<template>
  <div>
   <section class="content-sidebar">
    <div class="side-bar"> 
      <div class="collapse navbar-collapse displaynav-mobile" id="navbarResponsive">
          <ul>
              <nuxt-link to="/school/" title="school">
                <li id="schools"><i class="fa fa-graduation-cap"></i>Schools</li>
              </nuxt-link>
              <nuxt-link to="/events/" title="events" >
                <li id="events"><i class="fa fa-calendar"></i>Events</li>
              </nuxt-link>
              <nuxt-link to="/reports/" title="reports" >
                <li id="reports"><i class="fa fa-file"></i>Reports</li>
              </nuxt-link>
              <nuxt-link to="/rates/" title="rates">
                <li id="rates"><i class="fa fa-star"></i>Rates</li>
              </nuxt-link>
              <nuxt-link to="/profile/" title="logout" >
                <li class="" id="profile"><i class="fa fa-user"></i>Profile</li>
              </nuxt-link>
              <nuxt-link to="/" title="logout" id="logout">
                <li class=""><i class="fa fa-sign-out"></i>Log out</li>
              </nuxt-link>
          </ul>
      </div>
    </div>
  </section>
  </div>
</template>

<style scoped>
.content-sidebar{
  height:100%;
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
  z-index: 9;
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
/* .collapse:not(.show){
  display:block !important;
} */
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
  padding: 14px 30px;
}


</style>