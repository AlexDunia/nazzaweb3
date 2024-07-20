<script setup>
import Bg from '../assets/Images/pattern.png'
</script>

<template>
  <main>
    <div className="nzazabgcontact"> 
      <img src="../assets/Images/pattern2.png">
    </div>
    <div className="form-inlinee">
      <div className="contactus">
        <h1> Contact Us </h1>
        <p> Hate contact forms? <a href="google.com">  support@hashpay.com </a> </p>
    </div> 
      <div className="formgroup">
        <label for="email" className="emailbg"> Full Name </label> <br/>
        <input required="" type="text" id="email" name="email" class="form-field"> 
      </div>
      <br/>
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
        <!-- <button className="buttoncontact" type="submit">Sign Up</button> -->
      </div>
      <button className="btncontact" type="submit">Send</button>
      
    </div>
    <!-- <div> 
      <button  type="submit">Sign Up</button>
    </div> -->


</main>
</template>

<style src="../assets/style/contact.css"> 
</style>

<script>
export default {

data() {
  return{
   
  }
}
}
</script>
