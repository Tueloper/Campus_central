<template>
<div>
   <nav class="navbar navBar navbar-expand-md  fixed-top" id="navBar">
    <div class="container-fluid  ">
      <nuxt-link class="navbar-brand" to="/"><b>Campus Central </b></nuxt-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive">
            <span class="navbar-toggler-icon fa fa-align-justify"></span>
        </button>
        <div class="collapse navbar-collapse m-r-166" id="">
          <ul class="navbar-nav ml-auto">
              <li class="nav-item display-inline">
                <nuxt-link class="nav-link" to="#"><i class="fa fa-facebook"></i></nuxt-link>
                <nuxt-link class="nav-link" to="#"><i class="fa fa-twitter"></i></nuxt-link>
                <nuxt-link class="nav-link" to="#"><i class="fa fa-linkedin"></i></nuxt-link>
              </li>
            </ul>
        </div>
    </div>
  </nav>
</div>
</template>

<style scoped>

.navbar-nav .nav-item {
  margin: 0 10px;
}

.nav-link {
  font-weight: 700;
  padding: 10px;
}

.navbar-nav .nav-item .btn {
  color: #fff;
  font-weight: 500;
  padding: 10px;
  text-transform: capitalize;
  border: none;
}

.navbar-nav .nav-item .btn:hover {
  color: #fff;
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
</style>