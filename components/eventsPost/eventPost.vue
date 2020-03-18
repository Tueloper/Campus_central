<template>
  <li class="">
      <div class="row  ml-0 events-listing bxs">
        <div class="col-md-4 col-4 text-center events-listing-text">
          <h5>{{day}} </h5>
          <p>{{month}}</p>
          <nuxt-link :to="/post/ + id" class="btn btn-danger mt-3">Read More</nuxt-link>
          
        </div>
        <div class="col-md-8 col-8 events-listing-content pt-3">
          <h5>{{title}}</h5>
          <p>{{previewText}}</p>
        </div>
      </div>
    </li>
</template>
<style scoped>

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
.events-listing-content h5 {
    font-size: 22px;
    font-weight: bold;
}
.events-listing-text p {
    font-size: 21px;
    text-align: center;
    font-weight: normal;
    margin: 0;
}
</style>

<script>
export default {
  name: 'eventPost',
  props: {
    id: {
      type: String,
      required: true
    },
    day:{
      type:String,
      required:true
    },
    month:{
      type:String,
      required:true
    },
    title:{
      type:String,
      required: true
    },
    previewText:{
      type:String,
      required: true
    }
  }
}
</script>