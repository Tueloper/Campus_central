<template>
  <div class="col-md-10">
      
      <nuxt-link :to="/readtext/ + id">
        <div class="result">
          <div class="card result-container">
              <div class="row">
                  <div class="col-md-2 col-12">
                      <div class="image-container">
                          <img src="~/assets/img/pple.jpg" alt="man" class="img-fluid">
                      </div>
                  </div>
                  <div class="col-md-10 col-12">
                      <div class="result-info">
                          <h2 class="search-title">{{title}}</h2>
                          <p>{{previewText}}</p>
                      </div>
                  </div>
              </div>
          </div>
      </div>
      </nuxt-link>
  </div>
</template>
<script>
export default {
  name: 'ratePost',
  props:{
    id:{
      type:String,
      required:true
    },
    title:{
      type: String,
      required:true
    },
    previewText:{
      type:String,
      required:true
    }
  }
}
</script>
<style scoped>
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
  a{
    color: #1b1a1a;
    text-decoration: none;
    background-color: transparent;
  }
   a:hover{
    color: #f31e1e;
    text-decoration: none;
    background-color: transparent;
  }
  .btn-danger{
    color: #fff;
    background-color: #f31e1e !important;
    border-color: #f31e1e;
  }
</style>