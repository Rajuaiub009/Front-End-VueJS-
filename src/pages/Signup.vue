<template>
      <div class="container mt-5">
  <div class="row justify-content-center">
    <div class="col-md-6">
      <div class="card">
        <div class="card-header">
          <h4 class="mb-0">Signup</h4>
        </div>
        <div class="card-body">
          <form>
            <div class="form-group">
              <label for="fname">Firstname</label>
              <input type="text" class="form-control" id="fname" name="fname" placeholder="Enter firstname" required>
            </div>
            <div class="form-group">
              <label for="lname">Lastname</label>
              <input type="text" class="form-control" id="lname" name="lname" placeholder="Enter lastname" required>
            </div>
            <div class="form-group">
              <label for="username">Username</label>
              <input type="text" class="form-control" id="username" name="username" placeholder="Enter username" required>
            </div>
            <div class="form-group">
              <label for="password">Password</label>
              <input type="password" class="form-control" id="password" name="password" placeholder="Enter password" required>
            </div>
            <div class="form-group">
              <label for="confirmPassword">Confirm Password</label>
              <input type="password" class="form-control" id="confirmPassword" name="confirmPassword" placeholder="Confirm your password" required>
            </div> <br>
            <button type="submit" class="btn btn-primary btn-block">Sign Up</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default{
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Signup',
    

}
</script>