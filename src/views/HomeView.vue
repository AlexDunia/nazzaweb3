<script setup>
import Bg from '../assets/Images/pattern.png'
</script>

<template>
  <main>
    <div className="heroflex">

      <div>
        <h1 className="mainheroh1"> Easy and  Secure way To 
       Buy,Sell and Trade Crypto </h1> 
       <p className="mainherop"> Nazza is an easy, convenient and secure means to convert assets <br/> 
        between cryptocurrencies, fiat and other currencies, that buys and holds <br/>
       cryptocurrency for value appreciation. </p>

       <div className="wlflex"> 

        <div className="wlbtn">
        <input required="" type="text" id="email" name="email" class="form-field" placeholder="Enter your Email"> 
       </div> 

        <div className="wlbtn">
        <button> Join the waiting list </button>
       </div> 

         </div>
       
       <!-- <button className="bluebtn"> Get Started </button>
       
      <div className="storeimgflex">  

       <div className="storeimg">
        <img src="../assets/Images/gp.png">
       </div> 


       <div className="storeimg appstore">
        <img src="../assets/Images/appstore.png">
       </div> 

      </div> -->

      </div>

      <div className="heroimg"> 
        <img src="../assets/Images/phone.png"> 
      </div>

    </div> 

    <!-- Second -->
    <div className="whybg"> 

    <div className="whymain">

      <div className="whymainh"> 
        <h2> Why <span className="bluespan">Nazza </span> is reliable </h2> 
      </div>

      <!-- Flex box side -->
      <div className="whyflex">

      <div className="why"> 
      <h4> <span className="darkbluespan"> Nazza is </span>  <span className="bluespan"> easy to use </span>  </h4> 
      <p> Everyone enjoys using an easy-to-use platform, 
        so offering you seamless services that you can 
        use without having to exert much effort is our
         top priority.</p> 
      </div>

      <div className="why"> 
      <h4> <span className="darkbluespan"> Nazza is </span> <span className="bluespan"> secure </span> </h4> 
      <p> We are confident in saying that your 
        cryptocurrency is in the right hands 
        because our secure platform is 
        trusted by millions of people around 
        the world. </p> 
      </div>

      <div className="why"> 
      <h4> <span className="darkbluespan"> Nazza is </span>  <span className="bluespan"> very fast </span>  </h4> 
      <p> We are confident in saying that your 
        cryptocurrency is in the right hands 
        because our secure platform is 
        trusted by millions of people around 
        the world. </p> 
      </div>

    </div> 

    </div> 

  </div>

  <br/> 

  <!-- Third -->
  <div className="thirdbg"> 

  <div className="thirdflex">

<div>
  <h1 className="mainheroh"> Buy, Sell and Trade Crypto <br> across all borders. </h1> 
  <p className="mainherop"> Buy, Sell and Trade Crypto <br> across all borders. </p>
  <button className="bluebtn"> Join the waiting list </button>

</div>

<div className="buysellimg"> 
  <img src="../assets/Images/buysell.png"> 
</div>

</div> 
</div>

<!-- News letter -->
<div>

  <div className="nlbg"> 
    <h1> Join the waiting list </h1>
    <p> Be the first to know when we launch </p>
      <form className="example"> 
  
      <input placeholder="Enter Email addresss" className="myinput"/> 

      <button className="mysub"> Join the waiting list </button>
      </form>
    </div>

  <!-- <div className="nlbg"> 
    <h1> Sign up for our weekly newsletter </h1>
    <p> Stay informed with the latest updates to buy, sell and store your crypto </p>
      <form className="example"> 
  
      <input placeholder="Enter Email addresss" className="myinput"/> 

      <button className="mysub"> Subscribe for free </button>
      </form>
    </div> -->

</div>
  

<!-- Footer -->
<div className="footerbg" :style="{ backgroundImage: 'url(' + image + ')' }"> 

  <div className="fwlimgflex">

  <div className="fwlimg">
      <img src="../assets/Images/ig.png"> 
  </div>

  <div className="fwlimg">
      <img src="../assets/Images/twitter.png"> 
  </div>

  <div className="fwlimg">
      <img src="../assets/Images/fb.png"> 
  </div>

  <div className="fwlimg">
      <img src="../assets/Images/yt.png"> 
  </div>


  <div className="fwlimg">
      <img src="../assets/Images/li.png"> 
  </div>

</div> 

<div className="fwltextflex">

<div>
  <h4> help@mynazza.com </h4>
</div> 

<div>
  <h4> @2022. Nazza Inc </h4>
</div> 
</div> 

  <!-- <div className="footerflex"> 

  <div className="footerone">
    <img src="../assets/Images/hashpaylogowhite.png"> 
  <li>  Pay@hashpay.ng  </li>
  <li>  	&#169; 2022. Hashpay Inc  </li>
  </div> 
   
  <div className="footertwo">
  <h4> Product </h4>
  <li> <a> Buy Crypto </a> </li>
  <li> <a> Sell Crypto </a> </li>
  </div> 

  <div className="footertwo">
  <h4> Company </h4>
  <li> <a> About us </a> </li>
  <li> <a> About the founder </a> </li>
  <li> <a> Privacy policy </a> </li>
  <li> <a> Terms of service </a> </li>
  <li> <a> Anti Money laundering </a> </li>
  </div> 

  <div className="footertwo">
  <h4> Community </h4>
  <li className="footerlink"> <a> Twitter </a> </li>
  <li className="footerlink"> <a> Instagram </a> </li>
  <li className="footerlink"> <a> Facebook </a> </li>
  <li className="footerlink"> <a> Linkedin </a> </li>
  </div> 

</div> -->

</div>

</main>
</template>

<style src="../assets/style/home.css"> 
</style>

<script>
export default {
props: ['myproducts'],
data() {
  return{
     image: Bg
  }
}
}
</script>
