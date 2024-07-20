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
        <h1> Let's setup your profile! </h1>
        <br/> 
        <!-- <p> Hate contact forms? <a href="google.com">  support@hashpay.com </a> </p> -->
    </div> 
      <div className="formgroup">
        <p className="warningforform"> Please make sure the details are correct as they will be used to verify your identity. </p> 
        <!-- <label for="email" className="emailbg"> Full Name </label> <br/> -->
       <input required="" type="text" id="email" name="Name" class="form-field" placeholder="Name"> <br/><br/>
       <input required="" type="text" id="username" name="username" class="form-field" placeholder="Username"> <br/><br/>
       <input required="" type="text" id="username" name="username" class="form-field" placeholder="password"> 
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
      <div className="require"> 
      <p className="pmc"> Password must contain </p> 
      <p> <i class="fa-solid fa-check"></i> At least 8 characters </p>
      <p> <i class="fa-solid fa-check"></i> At least one uppercase character </p>
      <p> <i class="fa-solid fa-check"></i> At least one number </p>
      <p> <i class="fa-solid fa-check"></i> At least one number or special character (i@#&$) </p>
      <button className="btncontact" type="submit"> Confirm </button>
    </div>
    </div>
    <!-- <div> 
      <button  type="submit">Sign Up</button>
    </div> -->


</main>
</template>

<style src="../assets/style/profile.css"> 
</style>

<script>
export default {

data() {
  return{
   
  }
}
}
</script>
