<template>
  <div>
    <b-container fluid>
      <div class="content-sect">
                <div class="">
                    <div class="container">
                        <div class="heading">
                            <h2>My Profile</h2>
                        </div>
                        <section class="">
                            <form role="form" action="">
                            <div class="row">
                            <div class="col-md-6">
                            <div class="form-group">
                            <label for="name">Name:</label>
                            <input type="fName" class="form-control" id="fullName">
                            </div>
                            <div class="form-group">
                            <label for="email">Email address:</label>
                            <input type="email" class="form-control" id="email">
                            </div>
                            <div class="form-group">
                            <label for="phone">Phone:</label>
                            <input type="tel" class="form-control" id="phoneNo">
                            </div>
        
                            <div class="heading">
                            <h3>Change Password</h3>
                            </div>
        
                            <div class="form-group">
                            <label for="pwd">Old Password:</label>
                            <input type="password" class="form-control" id="oldPassword">
                            </div>
        
                            <div class="form-group">
                            <label for="pwd">New Password:</label>
                            <input type="password" class="form-control" id="newPassword">
                            </div>
        
                            <div class="form-group">
                            <label for="pwd">Confirm Password:</label>
                            <input type="password" class="form-control" id="confirmPassword">
                            </div>
        
                            </div>
                            <div class="col-md-6">
                            <div class="avatar-container pb-5 text-center">
                            <div id="image-box" class="text-center">
                            <img src="http://ssl.gstatic.com/accounts/ui/avatar_2x.png" class="custom-avatar img-circle img-thumbnail" alt="avatar">  
                            </div>
        
                            <input type="file" id="avatar" class="text-center center-block file-upload">
        
                            </div>
                            <div class="school-info card">
                            <div class="form-group">
                            <label for="location">Location:</label>
                            <input type="text" class="form-control" id="location">
                            </div>
                            <div class="form-group">
                            <label for="location">School:</label>
                            <select class="form-control" id="sel1">
                            <option>School</option>
                            <option>Covenant-University</option>
                            <option>University of Uyo</option>
                            <option>Michael Okpara University Of Agriculture</option>
                            <option>Akwa Ibom state University</option>
        
                            </select>
                            </div>   
                            <div class="form-group">
                            <label for="interest">Interest:</label>
                            <input type="text" class="form-control" id="MyInterest">
                            </div>
                            <button type="submit" class="btn btn-danger pull-right">Submit</button>
                            </div>
                            </div>
        
                            </div>
                          </form>
                        </section>
                    </div>
                </div>
            </div>
    </b-container>
  </div>
</template>
<script >
export default{
  layout: 'logout',
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
  .school-info {
    padding: 20px;
}
.heading h1, .heading h2 {
    font-weight: bold;
}
</style>