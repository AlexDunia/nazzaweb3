<template>
    <main>
    <div className="container">
      <div className="popupositionwithdraw"> 
      <div className="popupwrapperwithdraw"> 
      <div className="popupwithdraw" id="popupwhitewithdraw">

        <div className="mainpopnavigationwithdraw"> 

<div className="arrowback"> 
  <i class="fa-solid fa-arrow-left"></i>
</div>

<div className="mainpopuptextwithdraw"> 
<h2> Account destination </h2> 
  </div>

</div>

<div>

<select v-model="selected" className="awdselect" value="Please Select Bank" placeholder="enter">
  <option > Please Select Bank </option>
  <option> Access bank </option>
  <option> United Bank of Africa (UBA)</option>
  <option> Zenith bank </option>
  <option> Fidelity bank </option>
</select>

    <input className="awdinput" placeholder="Account Number" type="number"> <br/>
    <input className="awdinput" placeholder="Account Name" type="text">
</div>
    <div> 
      <button className="withdrawbtn"> Select Bank and Account </button>
    </div>
        <!-- <div className="popuptextwithdraw">
            <h2> How much do you want to withdraw? </h2> 
            <p> accumsan dolor dignissim adipiscing diam <br/> eros Duis augue duis dolor </p>
            <div className="popupinputwithdraw">
            <input type="checkbox" id="checkbox" v-model="checked" placeholder="I understand"/>
           <label for="checkbox">I understand </label> <br/> <br/> 
           <button> Proceed </button> 
          </div>
        </div>  -->


        </div>
        </div>
        </div>
  
      <div className="vkbg">
        <div className="vkflex"> 
  
        <div className="vk">
         <h1>  Verify KYC </h1>
         <p> We need some information to complete your account verification </p>
        </div>
  
        <div className="vktwo">
         <i class="fa-solid fa-arrow-right fa-lg"></i>
        </div>
  
      </div>
  
      </div>
  
      <!-- Wallet Balance -->
  
      <div className="wbbg">
  
        <div className="wb">
         <h1>  Wallet Balance  </h1>
         <p> $0.00 </p>
        </div>
  
  
      </div>
  
         <!-- End of Wallet Balance -->
  
        <!-- Card -->
        <div className="cardflex"> 
  
        <div className="pink">
          <img src="../assets/Images/firstarrow.png">
          <div className="cardtext">
          <h2> Sell Cryptocurrency </h2> 
          <p> Sell crypto currency with your local currency </p>
        </div> 
        </div> 
  
        <div className="pink" id="blue">
          <img src="../assets/Images/secondarrow.png">
          <div className="cardtext">
            <h2> Buy Cryptocurrency </h2> 
            <p> Buy crypto currency with your local currency </p>
        </div> 
  
        </div> 
  
        <div className="pink" id="grey">
          <img src="../assets/Images/thirdarrow.png">
          <div className="cardtext">
            <h2> Tickets </h2> 
          <p> Redeem transaction </p>
        </div> 
         
        </div> 
        
      </div> 
  
      <!-- Transactions -->
      <div className="thead">
  
      <div className="theadtext" id="tht">
        <h3> Crypto </h3>
      </div> 
  
      <div className="theadtext">
        <h3> Number </h3>
      </div> 
  
      <div className="theadtext" id="prc">
        <h3> Price </h3>
      </div> 
  
      <div className="theadtext" id="td">
        <h3> Transaction Date </h3>
      </div> 
  
       <div className="theadtext">
        <h3> Network </h3>
      </div> 
      
    </div> 
  
    <!-- Main transactions styling -->
    <div className="maintransactionsflex">
  
   <div className="cf"> 
    <div className="coinflex">
    <div>
      <img src="../assets/Images/btc.png">
    </div> 
    <div className="mybtc">
      <h3> Bitcoin </h3>
    </div> 
    <div className="mybtcstatus">
      <h3> Sell </h3>
    </div> 
  </div> 
  </div>
  
  <!-- second -->
  <div className="mt">
    <h3> 1.6btc </h3>
  </div> 
  
  <div className="mt"> 
    <h3> #23,000 </h3>
  </div>
  
  <div className="mt">
    <h3> 27th Jun, 2022, 22:30 pm </h3>
  </div> 
  
  <div className="mt"> 
    <h3 className="ty"> BNB </h3>
  </div>
  
  </div>
  
  <!-- Main transactions styling -->
  <div className="maintransactionsflex">
  
  <div className="cf"> 
   <div className="coinflex">
   <div>
     <img src="../assets/Images/btc.png">
   </div> 
   <div className="mybtc">
     <h3> Lite coin</h3>
   </div> 
   <div className="mybtcstatus">
     <h3> Sell </h3>
   </div> 
  </div> 
  </div>
  
  <!-- second -->
  <div className="mt">
   <h3> 1.6btc </h3>
  </div> 
  
  <div className="mt"> 
   <h3> #23,000 </h3>
  </div>
  
  <div className="mt">
   <h3> 27th Jun, 2022, 22:30 pm </h3>
  </div> 
  
  <div className="mt"> 
   <h3 className="ty"> BNB </h3>
  </div>
  
  </div>
  
  
    </div>
  
  
  </main>
  </template>
  
  <style src="../assets/style/withdrawdestination.css"> 
  </style>
  
  <script>
  export default {
  
  data() {
    return{
     
    }
  }
  }
  </script>
  