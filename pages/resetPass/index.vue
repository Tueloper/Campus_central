<template>
<b-container fluid>
  <div class="content-sect mb-7 ">
     <div class="row">
          <div class="col-md-3">

          </div>
          <div class="col-md-6 my-5">
              <h3 class="forgotPassword">Reset Password</h3>
              <form action="" method="post">
                <div class="form-group">
                  <input type="password" name="password" id="myPassword"  class="form-control" placeholder="New Password">
                </div>
                <div class="form-group">
                  <input type="password" name="password" id="myPasswordConfirm"  class="form-control" placeholder="Confirm Password">
                </div>
                <input type="button" value="Update Password" class="btn btn-danger btn-block">
      
              </form>
              
          </div>
          <div class="col-md-3">
              
          </div>
      </div>
  </div>
</b-container>
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
<script>
  
</script>