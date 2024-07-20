<script setup>
import Bg from '../assets/Images/pattern.png'
</script>

<template>
  <main>
    <div className="nzazabgcontact"> 
      <img src="../assets/Images/pt2.png">
    </div> 
    

    <div className="loginform">

        <div className="nlogo"> 
      <img src="../assets/Images/nazzamain.png">
    </div>

      <div className="contactus">
        <h1> Create your account </h1>
        <br/> 
        <!-- <p> Hate contact forms? <a href="google.com">  support@hashpay.com </a> </p> -->
    </div> 
      <div className="formgroup">
        <!-- <label for="email" className="emailbg"> Full Name </label> <br/> -->
       <input required="" type="text" id="email" name="email" class="form-field" placeholder="nazzapay@gmail.com"> 
      </div>
      <!-- <br/>
      <br/>
      <div className="formgroup">
        <label for="email" className="emailbg"> Email Address </label> <br/>
        <input required="" type="text" id="email" name="email" class="form-field"> 
      </div>
      <br/>
      <br/>
      <div className="formgroupp">
        <label for="email" className="emailbg"> Message </label> <br/>
        <textarea required="" type="text" id="email" name="email" class="form-field"/> 
      </div> -->
      <button className="btncontact" type="submit"> Create account </button>
      <p> Have an account? <a href="google.com">  Sign in </a> </p>
    </div>
    <!-- <div> 
      <button  type="submit">Sign Up</button>
    </div> -->


</main>
</template>

<style src="../assets/style/enteremail.css"> 
</style>

<script>
export default {

data() {
  return{
   
  }
}
}
</script>
