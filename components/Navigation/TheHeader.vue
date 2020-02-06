<template>
<div>
  <div>
  
      <b-navbar toggleable="lg" type="dark" class="deep-blue" fixed="top">
        <b-container fluid>
        <b-navbar-brand href="#">Campus Central</b-navbar-brand>
        <ul class="nav-social-icon ml-auto">
            <li href="#" ><i class="fa fa-facebook"></i></li>
            <li href="#" ><i class="fa fa-twitter"></i></li>
            <li href="#" ><i class="fa fa-instagram"></i></li>
       </ul>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        

  </b-container>
    </b-navbar>
</div>
</div>
</template>
<script>
export default {
 
};
</script>
<style scoped>
.nav-social-icon  {
  display:flex;
  list-style: none;
}
.nav-social-icon li{
  padding-left:10px;
}
.nav-social-icon{
  margin-bottom:0 !important;
}
  .header-container{
    height:60px;
  }
  .deep-blue{
    background-color:#2A3F54;
    color:#ffffff;
    font-weight:bold;
  }
  .the-Header{
    width:100%;
    position:fixed;
    height:60px;
    display:flex;
    justify-content:space-around;
    align-items:center;
    background-color:black;
    z-index:100;
    box-sizing:border-box;
    padding:0 20px;
  }
  .logo{
    margin:0 10px;
    font-size:1.3rem;
  }
  @media(min-width:768px){
    .navigation-items{
      display:block;
    }
 
  }
   @media(max-width:768px){
  .nav-social-icon li{
  padding-left:10px;
  padding-right:10px;
}
.nav-social-icon ul{
  margin-right:10px;
 
}
}
  .nav-list{
    list-style:none;
    padding:0;
    margin:0;
    display:flex;
  }
  .nav-item{
    margin: 0 10px;
  }
</style>