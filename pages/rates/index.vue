<template>
  <div>
      <b-container fluid>
  
        <div class="content-sect">
            <div class="container">
                <div class="heading">
                    Rate a...
                </div>
                <div class="form-check-inline">
                    <label class="form-check-label">
                    <input type="radio" class="form-check-input" name="optradio">Lecturer
                    </label>
                </div>
                <div class="form-check-inline">
                    <label class="form-check-label">
                    <input type="radio" class="form-check-input" name="optradio">School
                    </label>
                </div>
                <div class="form-check-inline disabled">
                    <label class="form-check-label">
                    <input type="radio" class="form-check-input" name="optradio">Event
                    </label>
                </div>
                <form action="" class="user-search-form">
                    <div class="row">
                        <div class="col-md-5">
                            <div class="form-group">
                                <input type="text" class="form-control" id="search-item" placeholder="Enter Your Search">
                            </div>
                        </div>
                        <div class="col-md-5">
                            <div class="form-group">
                                <input type="text" class="form-control" id="search-item" placeholder="Enter Your Search">
                            </div>
                        </div>
                        <div class="col-md-2">
                            <button type="button" class="btn btn-danger btn-block">Search</button>
                        </div>
                    </div>
                </form>
                <hr>
                <h3>Results for search of "<span id="searched-entity">John Hopkins</span>"</h3>
                <section id="result-section">
                    <div class="">
                        <div class="row">
                            
                            <ratePost id="1" 
                            title="Mr. John Hopkins" 
                            previewText="Lecturer in Business Department in University of Uyo" />
                           
                           <ratePost id="2" 
                            title="Mr. John Hopkins" 
                            previewText="Lecturer in Business Department in University of Uyo" />
                           
                            <div class="col-md-12 text-center p-l-24">
                                <a href="#" class="btn btn-danger">Load More</a>
                            </div>
                        </div>
                        
                    </div>
                </section>
            </div>
        </div>
      </b-container>
  </div>
</template>
<script>
import ratePost from '@/components/ratePost/ratePost'
export default{
   layout: 'logout',
   components:{
       ratePost:ratePost
   }
  }
</script>
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
</style>