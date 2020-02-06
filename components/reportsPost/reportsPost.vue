<template>
   <div class="col-md-10 col-12 mb-3 mt-3">
      <div class="result">
         <nuxt-link :to="'//' + id">
          <div class="card result-container">
              <div class="row">
                  <div class="col-md-4 col-12">
                      <div class="image-container">
                         {{thumbnails}} <!-- <img src="img/man.png" alt="man" class="img-fluid"> -->
                      </div>
                  </div>
                  <div class="col-md-8 col-12">
                      <div class="result-info">
                          <h2 class="search-title">{{ title }}</h2>
                          <p class="search-subtitle">{{ previewText }}</p>
                      </div>
                  </div>
              </div>
          </div>
         </nuxt-link>
      </div>
  </div>
</template>
<script>
export default {
 name: 'reportsPost',
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
  .user-search-form {
    margin: 40px 0;
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
    background-color: #f31e1e;
    border-color: #f31e1e;
  }
</style>