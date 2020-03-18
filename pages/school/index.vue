<template>
  <div>
      <b-container fluid>
        <div class="content-sect mb-7  ">
            <div class="heading">Search for a school</div>
            <form action="" class="user-search-form">
              <div class="row">
                <div class="col-md-5">
                    <div class="form-group">
                        <input type="text" class="form-control" id="search-name" placeholder="School Name">
                    </div>
                </div>
                <div class="col-md-5">
                    <div class="form-group">
                        <input type="text" class="form-control" id="search-school" placeholder="Location">
                    </div>
                </div>
                <div class="col-md-2">
                    <button type="submit" class="btn btn-danger btn-block">Search</button>
                </div>
              </div>
            </form>
            <hr>

            <h3 class="sub-heading">Results for search of "<span id="searched-entity">University of Uyo</span>"</h3>
            <section id="result-section">
              <div class="">
                    <div class="">
                        <div class="result">
                         <schoolPost id="1" thumbnail="../assets/img/pple.jpg" title="University of Uyo" 
                         previewText=" Lorem ipsum dolor sit amet consectur adipisicing elit. 
                         Placeat, aliquammoles tiae "/>
                         <schoolPost id="2" thumbnail="" title="University of Uyo" 
                         previewText=" Lorem ipsum dolor sit amet consectur adipisicing elit. 
                         Placeat, aliquammoles tiae "/>
                         <schoolPost id="3" thumbnail="" title="University of Uyo" 
                         previewText=" Lorem ipsum dolor sit amet consectur adipisicing elit. 
                         Placeat, aliquammoles tiae "/>
                          
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
<script >
import schoolPost from '@/components/schoolPost/schoolPost'
export default{
   components: {
     schoolPost: schoolPost
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
