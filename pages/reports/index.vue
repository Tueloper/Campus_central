<template>
  <div>
      <b-container fluid>
        <div class="content-sect">
              <div class="container">
                      <div class="heading">
                          Report a...
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
                                  <button type="submit" class="btn btn-danger btn-block">Search</button>
                              </div>
                          </div>
                      </form>
                      <hr>

                      <h3>Results for search of "<span id="searched-entity">John Hopkins</span>"</h3>
                      <section id="result-section">
                              <div class="row ">
                                 <reportsPost  id="1" 
                                 title="Mr John Hopkin" 
                                 previewText="Lecturer in Business Department in University of Uyo" 
                                 />
                                 <reportsPost id="2" 
                                 title="Mr John Hopkin" 
                                 previewText="Lecturer in Business Department in University of Uyo" 
                                 />
                                 <reportsPost id="3" 
                                 title="Mr John Hopkin" 
                                 previewText="Lecturer in Business Department in University of Uyo" 
                                 />

                              </div>
                              <div class="row">
                                  <div class="col-md-4"></div>
                                  <div class="col-md-2">
                                      <div class="button-section text-center">
                                          <button type="button" class="btn btn-danger ">Load more</button>
                                      </div>
                                  </div>
                                  <div class="col-md-4"></div>
                              </div>
                          
                      </section>
                  </div>
        </div>
      </b-container>
  </div>
</template>
<script>
import reportsPost from '@/components/reportsPost/reportsPost'
export default{
   layout: 'logout',
   components:{
       reportsPost:reportsPost
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
</style>