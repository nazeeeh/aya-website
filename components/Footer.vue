<template>
 <div class="footer">
  <div>
    <v-row>
     <v-col>
        <img
         class="footer-logo" 
         src="~/assets/Images/logo.svg" 
         alt="logo"
        />
     </v-col>
     <v-col>
         <p class="footer-text mt-10">Terms and Conditions</p>
     </v-col>
     <v-col>
         <p class="footer-text mt-10">Privacy Policy</p>
     </v-col>
     <v-col>
         <div class="footer-icons mt-4">
             <a href="">
                <img src="~/assets/Images/Twitter.png" alt="icon">
             </a>
             <a href="">
                <img src="~/assets/Images/Facebook.png" alt="icon">
             </a>
             <a href="">
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
      © Aya 2021. All Rights Reserved. 
    </p>
  </div>
    
 </div>
</template>
<style scoped>
.footer{
    background-color: #0080FA;
    width: 100%;
    height: 250px;
    padding: 4rem 5rem;
    margin-top: 5rem;
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
</style>