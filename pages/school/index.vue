<template>
  <div>
      <b-container fluid>
        <div class="content-sect mb-7  ">
            <div class="heading">Search for a school</div>
            <form action="" class="user-search-form">
              <div class="row">
                <div class="col-md-5">
                    <div class="form-group">
                        <input type="text" class="form-control" id="search-name" placeholder="Enter Your Search">
                    </div>
                </div>
                <div class="col-md-5">
                    <div class="form-group">
                        <input type="text" class="form-control" id="search-school" placeholder="Enter Your Search">
                    </div>
                </div>
                <div class="col-md-2">
                    <button type="button" class="btn btn-danger btn-block">Search</button>
                </div>
              </div>
            </form>
            <hr>

            <h3 class="sub-heading">Results for search of "<span id="searched-entity">University of Uyo</span>"</h3>
            <section id="result-section">
              <div class="">
                    <div class="">
                      <div class="">
                        <div class="result">
                          <div class="card result-container">
                              <div class="row">
                                  <div class="col-md-4">
                                      <div class="image-container">
                                          <img src="img/Covenant-University.jpg" alt="man" class="img-fluid">
                                      </div>
                                  </div>
                                  <div class="col-md-8">
                                      <div class="result-info">
                                          <h3 class="search-title">University of Uyo</h3>
                                          <p class="search-subtitle">Uyo, Akwa Ibom State Nigeria</p>
                                          <p><span><i class="fa fa-star"></i><span id="rate-no"> 0</span> </span> Rate <span class="pull-right"><i class="fa fa-book"></i> <span id="report-no">0</span> Report</span></p>

                                      </div>
                                  </div>
                              </div>
                          </div>
                        </div>
                      </div>
                      <div class="">
                        <div class="result">
                            <div class="card result-container">
                                <div class="row">
                                    <div class="col-md-4">
                                        <div class="image-container">
                                            <img src="img/Covenant-University.jpg" alt="man" class="img-fluid">
                                        </div>
                                    </div>
                                    <div class="col-md-8">
                                        <div class="result-info">
                                            <h3 class="search-title">Akwa ibom state University</h3>
                                            <p class="search-subtitle">Uyo, Akwa Ibom State Nigeria</p>
                                            <p><span><i class="fa fa-star"></i><span id="rate-no"> 0</span> </span> Rate <span class="pull-right"><i class="fa fa-book"></i> <span id="report-no">0</span> Report</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                      </div>
                    </div>
              </div>
            </section>
            <div class="row">
              <div class="col-md-5"></div>
              <div class="col-md-2">
                  <div class="button-section text-center">
                      <button type="button" class="btn btn-danger ">Load more</button>
                  </div>
              </div>
              <div class="col-md-5"></div>
            </div>
        </div>

      </b-container>
  </div>
</template>
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
      margin: 101px 32px 0 22px;
      border: 0px solid #ccc;
      padding: 48px;
      box-shadow: 0px 0px 3px 0px;
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