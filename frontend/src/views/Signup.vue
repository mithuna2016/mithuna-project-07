<template>
<div class="frontpage">
    
      <div class="d-flex justify-content-center ">
        <div class="card logpage"> 
          <div class="card-header">
            <h3>Sign In</h3>
            <div class="d-flex justify-content-end social_icon">
            <img alt="Vue logo" src="@/assets/logo.png" class="logophoto" >
            </div>
          </div>
          <div class="card-body">
            <form>

              <div class="input-group form-group">
                 
                <input type="text" class="form-control" placeholder="firstName">
                
              </div>

              <div class="input-group form-group">
                
                
                <input type="text" class="form-control" placeholder="lastName">
                
              </div>

              <div class="input-group form-group">

                <div class="input-group-prepend">
                  <span class="input-group-text"><i class="fas fa-user"></i></span>
                </div>
                <input type="text" class="form-control" placeholder="username">
                
              </div>
              <div class="input-group form-group">
                <div class="input-group-prepend">
                  <span class="input-group-text"><i class="fas fa-key"></i></span>
                </div>
                <input type="password" class="form-control" placeholder="password">
              </div>
              
              <div class="form-group">
                <input type="submit"  class="btn float-right login_btn">
               
              </div>
            </form>
          </div>
          
        </div>
      </div>
    </div>

</template>

<script>
export default {
    name:"Signup",
}
</script>
