<template>
 <div class="footer">
  <div>
    <v-row>
     <v-col lg="3" md="12" sm="12">
      <div class="logo">
        <img
         class="footer-logo" 
         src="~/assets/Images/logo.svg" 
         alt="logo"
        />
        <p class="tagline">live borderless</p>
      </div>
     </v-col>
     <v-col lg="3" md="12" sm="12">
      <div class="terms-txt">
        <p class="footer-text mt-10">Terms and Conditions</p>
      </div>
     </v-col>
     <v-col lg="3" md="12" sm="12">
      <div class="privacy-txt">
        <p class="footer-text mt-10">Privacy Policy</p>
      </div>
     </v-col>
     <v-col lg="3" md="12" sm="12">
         <div class="footer-icons mt-4">
             <a href="https://twitter.com/ayagigs">
                <img src="~/assets/Images/Twitter.png" alt="icon">
             </a>
             <a href="http://web.facebook.com/myayagigs">
                <img src="~/assets/Images/Facebook.png" alt="icon">
             </a>
             <a href="https://www.linkedin.com/company/ayagigs/">
                <img src="~/assets/Images/Linkedin.png" alt="icon">
             </a>
             <a href="">
                <img src="~/assets/Images/Telegram.png" alt="icon">
             </a>
         </div>
     </v-col>
    </v-row>
  </div>
  <div>
    <v-divider class="w-100 divider mt-2"></v-divider>
  </div>
  <div>
    <p class="rights-reserve mt-8">
      © Aya 2021. 
    </p>
  </div>
    
 </div>
</template>
<style scoped>
.footer{
    background-color: #0080FA;
    height: auto;
    padding: 4rem 5rem;
    height: 250px;
    width: 100%;
}
.footer-text{
    font-family: 'Axiforma';
    font-style: normal;
    font-weight: 500;
    font-size: 15px;
    text-align: center;
    color: #FFFFFF;
}
.footer-icons{
    display: flex;
    justify-content: space-between;
}
.v-divider {
    border-color: #FFFFFF !important; 
    opacity: 0.43;
}
.rights-reserve{
    font-family: 'Axiforma';
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    text-align: center;
    color: #FFFFFF;
}
.tagline{
  text-transform: uppercase;
  font-family: Axiforma;
  font-style: normal;
  font-weight: 500;
  font-size: 11px;
  letter-spacing: 0.5px;
  color: #FFFFFF;
}

/* Mobile responsiveness */
@media (max-width: 360px){
    /* .footer{
        width: 100%;
    } */
}
@media (min-width: 340px) and (max-width: 960px){
  .footer{
      text-align: center;
      height: auto;
      width: 100%;
      padding: 0;
  }
  .logo{
      margin: 3rem 0 0 0;
      width: 100%;
   
  }

  .terms-txt{
      width: 100%;
  }
  .privacy-txt{
      width: 100%;
  }
  
  .footer-icons{
      width: 100%; 
  }
  .rights-reserve{
      margin: 0 auto;
  }
}

/* medium and larger screens */
/* @media (min-width: 768px) and (max-width: 1024px) {
    .footer{
      text-align: center;
      height: auto;
      width: 100%;
  }
  .footer-logo{
    margin: 0 0 0 0;
  }

} */

</style>