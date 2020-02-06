<template>
   <b-collapse class="sideNavColor" id="nav-collapse" is-nav>
      <b-navbar-nav>
        <!-- 
        <b-nav-item href="#">Link</b-nav-item>
        <b-nav-item href="#" disabled>Disabled</b-nav-item>
      < -->

      <!-- Right aligned nav items -->
        <section class="content-sidebar">
            <div class="side-bar"> 
              <div class=" navbar-collapse displaynav-mobile">
                  <ul>
                      <li id="schools"><nuxt-link to="school" title="school"><i class="fa fa-graduation-cap"></i>Schools</nuxt-link></li>
                      <li id="events"><nuxt-link to="events" title="events" ><i class="fa fa-calendar"></i>Events</nuxt-link></li>
                      <li id="reports"><nuxt-link to="reports" title="reports" ><i class="fa fa-file"></i>Reports</nuxt-link></li>
                      <li id="rates"><nuxt-link to="rates" title="rates"><i class="fa fa-star"></i>Rates</nuxt-link></li>
                      <li class="" id="profile"><nuxt-link to="profile" title="logout" ><i class="fa fa-user"></i>Profile</nuxt-link></li>
                      <li class=""><nuxt-link to="/" title="logout" id="logout"><i class="fa fa-sign-out"></i>Log out</nuxt-link></li>
                  </ul>
              </div>
            </div>
            <!-- End of side nav -->
          </section>
          </b-navbar-nav>
    </b-collapse>
</template>
<script>
import TheHeader from '@/components/Navigation/TheHeader'
export default {
  components:{
    TheHeader
  },
  name:'SideBar',
  props:{
    show:{
      type:Boolean,
      default:false
    }
  }
}
</script>
<style scoped>
/* @media(min-width:780px){
.sideNavColor{
  background-color:black;
  z-index:1000;
  height:200px;
  display:block ;
}
} */
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
   /*padding-left: 15px;*/
  border-top: 8px solid #F31E1E;
  margin-top: 54px;
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
  padding: 14px 27px;
}
@media (max-width: 767.98px){
.p-l30{
  padding-left:12px;
}
.displaynav-mobile{
  background: #2A3F54;;
    width: 176px;
    position: absolute;
    height: 100%;
    z-index:9;
    margin-top: 54px;
    border-top:5px solid #F31E1E;
}
.navbar-brand{
  padding-left:12px
}
.content-sect{
  padding: 27px;
  padding-top: 73px;
}
}
</style>