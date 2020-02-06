<template>
  <nuxt-link :to="'/listOfSchool/' + id">
    <div class="row">
      <div class="col-md-10">
        <div class="card result-container">
          <div class="row">
              <div class="col-md-4">
                
                    <div class="image-container">
                      
                      <img :src="thumbnail" alt="man" class="img-fluid">
                  </div>
                  
              </div>
              <div class="col-md-8">
                  <div class="result-info">
                      <h3 class="search-title">{{ title }}</h3>
                      <p class="search-subtitle">{{ previewText }}</p>
                      <p><span><i class="fa fa-star"></i><span id="rate-no"> 0</span> </span> Rate <span class="color-m"><i class="fa fa-file"></i> <span id="report-no">0</span> Report</span></p>

                  </div>
              </div>
          </div>
        </div>
      </div>
      </div>
  </nuxt-link>
</template>
<script>
export default {
  name: 'schoolPost',
  props:{
    id:{
      type:String,
      required:true
    },
    title:{
      type:String,
      required: true
    },
    previewText:{
      type:String,
      required:true 
    },
    thumbnail:{
      type:String,
      required:true
    }
  }
}
</script>
<style scoped>

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
    background-color: #f31e1e;
    border-color: #f31e1e;
  }
  .color-m i{
    margin-left: 20px;
  }
</style>