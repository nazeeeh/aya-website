<template>
  <div>
    <div class="first-section">
      <v-row >
       <v-col cols="12" md="6">
        <AyaLogo />
         <div class="text-section">
          <h3 class="header-text">
            Post Jobs, Get Gigs Make Payments Borderlessly!
          </h3>
         </div>
         <div class="paragraph">
          <p class="p-text">
            Aya is a platform that enables you to supercharge
            your business growth by getting access to vetted African freelancers, 
            powered by a cryptocurrency payments platform.
          </p>
          </div>
          <!-- modal box -->
          <v-row justify="">
              <!-- <ModalBox v-if="dialog"/> -->
          <v-btn
           @click.prevent="toggle" 
            depressed 
            class="btn-1" 
            x-large>Get access</v-btn>
    
          <v-dialog
            v-model="dialog"
           class="dialogBox"
           max-width="800px"
           
          >
          <div class="flex-display">
            <v-card class="" width="350px" hover href="https://docs.google.com/forms/d/19N1-kEHlW3RnoDhO3bhSd79vTNPIcjhi75CJoV4uYPU/edit">
              <v-card-text class="modalBtn">
                Access the Largest Pool 
                of African Freelancers from a 
                variety of professions.
              </v-card-text>
           </v-card>
           <v-card class="ml-10" width="350px" hover href="https://docs.google.com/forms/d/1KvT71tGW38it46IS7GqfZn6JRbCW90uV8KMbSpoOYCA/edit">
            <v-card-text class=" modalBtn">
              Join our Talent Pool showcase your 
                skills and get matched to companies.
            </v-card-text>
          </v-card>
          </div>
    </v-dialog>
      </v-row>
         <div class="orbit">
           <img 
            class="orbit-image"
            src="/orbit.svg" 
            alt="orbit">
         </div>
       </v-col>
      <v-col lg="6" md="8" sm="12">
        <div class="header-img">
          <img
            class="header-image" 
            src="/image_001.png" 
            alt="image"
         />
        </div>
      </v-col>
    </v-row>
    </div>
    
    <div class="reversed">
      <v-row>
        <v-col lg="6" md="6" sm="12">
          <div class="left-img">
            <img
            class="left-section-image"
            src="/image_002.png" 
            alt="image"
          />
          </div>
      </v-col>
      <v-col lg="6" md="6" sm="12">
        <img
          class="grafiti mx-6 " 
          src="/artifact.svg" 
          alt="image"
        />
        <div class="second-section">
          <h3 class="sub-heading-text">
            Get paid, using multiple stable coins 
          </h3>
        </div>
        <div class="paragraph-2">
            <p class="p-text">
              Convert your earnings to your favourite cryptocurrencies, 
              no hidden setup charges required. With all necessary functionalities 
              totally embebdded in the application, payment is seamless and made easy 
            </p>
          </div>
      </v-col>
    </v-row>
    </div>
    
    <div class="bg mt-8" :style="{backgroundImage: `url(${backgroundImg})`}">
      <v-row>
        <v-col lg="6" md="6" sm="12">
          <div class="third-section">
            <img 
            class="image-form"
            src="/image_003.png" 
            alt="image"
          />
          </div>
        </v-col>
        <v-col lg="6" md="6" sm="12">
          <div class="freelancers">
            <h3 class="sub-head-text">
              Freelancers:
            </h3>
            <p class="p-text-3 showcase">
              Showcase your skills to the world, get 
              matched with both local and international 
              companies and get paid, all hassle-free.
            </p>
            <v-btn class="btn-2" 
            href="https://docs.google.com/forms/d/1KvT71tGW38it46IS7GqfZn6JRbCW90uV8KMbSpoOYCA/edit"
            depressed x-large>
              Fill Our Talent Form
            </v-btn>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col lg="6" md="6" sm="12">
          <div class="business">
            <div class="business-text-div">
            <h3 class="sub-head-text">
              Businesses:
            </h3>
            
              <p class="p-text-3 access">
              Access the best and largest pool of African freelancers 
              to take your business to the next level, enjoy instant and
               borderless peer-to-peer cryptocurrency payments with 100% 
               Security guaranteed.
            </p>
            </div>
            <div class="btn-2-div">
              <v-btn class="btn-2 btn-2-2"
              href="https://docs.google.com/forms/d/19N1-kEHlW3RnoDhO3bhSd79vTNPIcjhi75CJoV4uYPU/edit"  
              depressed x-large>
              Fill Our Talent Requirement Form
            </v-btn>
            </div>
            
          </div>
        </v-col>
        <v-col lg="6" md="6" sm="12">
          <div class="business-image">
            <img 
             class="business-img"
             src="/image_004.png" 
             alt="image"
            />
          </div>
        </v-col>
      </v-row>
    </div>

    <div class="fourth-section">
    <v-row>
      <v-col lg="6" sm="12" md="6">
          <div class="mt-16 sub-fourth">
            <h3 class="sub-header-fourth">
             Join our Customer Discovery Program to: 
           </h3>
           <p class="p-text-4">
             Help us build a solution for you and also test 
             the earliest version of the product.
           </p>
           <div class="form">
             <form>
               <input class="input-box" type="text" placeholder="First Name" required><br><br>
               <input class="input-box" type="text" placeholder="Last Name" required><br><br>
               <input class="input-box" type="email" placeholder="Email" required><br><br>
               <v-btn type="submit" class="mt-4 btn-2" depressed x-large>
                 Submit
               </v-btn>
             </form>
           </div>
          </div>
           
        </v-col>
        <v-col lg="6" sm="12" md="6">
          <div class="fourth-img">
            <img
              class="fourth-image" 
              src="/image_005.png" 
              alt="image"
            />
          </div>
      </v-col>
    </v-row>
    </div>
      <v-row no-gutters dense class="fifth-section" :style="{backgroundImage :`url(${backgroundImg2})`}">
        <v-col>
          <div class="fifth-text-section" justify="center">
            <p class="p-text-5">
              We are creating opportunities for African digital skilled talents 
              to offer their services to the global workforce, starting from Africa.  
              Missed the button above by chance? Well lucky you, we’ve got another here. 
            </p>
            <div class="bbtn">
               <v-btn @click.prevent="toggle"  class="btn-3" depressed x-large>Get access</v-btn>
            </div>
          </div>
        </v-col>
      </v-row>
      <div>
        <img class="eclipse" src="/eclipse.svg" alt="image">
      </div>
      <div class="partnerships">
        <v-row>
          <v-col>
            <div>
              <p class="partnership-header">
                Proudly Supported <br> by:
              </p>
            </div>
            <marquee 
              direction="left"
              behavior= "scroll">
            <div class="p-grid">
              
              <div class="partners-logo">
              <img 
              class="logos"
              src="~/assets/Images/partner_001.png" 
              alt="partners"
            >
            </div>
            <div class="partners-logo">
              <img 
              class="logos"
              src="~/assets/Images/partner_002.png" 
              alt="partners"
            >
            </div>
            <div class="partners-logo">
              <img 
              class="logos"
              src="~/assets/Images/partner_004.png" 
              alt="partners"
            >
            </div>
            <div class="partners-logo">
              <img 
              class="logos"
              src="~/assets/Images/partner_003.png" 
              alt="partners"
            >
            </div>
            <div class="partners-logo">
              <img 
              class="logos"
              src="~/assets/Images/partner_005.png" 
              alt="partners"
            >
            </div>
            </div>
             </marquee>
          </v-col>
        </v-row>
      </div>
      <Footer />
  </div>
</template>
<script>
import backgroundImg from "~/assets/Images/background.png";
import backgroundImg2 from "~/assets/Images/background_02.png"

export default {
  components : {
   
  },

  data() {
    return {

      dialog: false, 
      backgroundImg, 
      backgroundImg2
      
      }
  },
  methods: {
    toggle(){
      this.dialog = !this.dialog
    }
  }
}
</script>
<style scoped>
.first-section{
  max-width: 1440px;
}
.text-section{
  margin: 10rem 0 0 5rem;
}
.header-text{
  font-family: 'Axiforma';
  font-style: normal;
  font-weight: 800;
  font-size: 48px;
  line-height: 65px;
  letter-spacing: 0.5px;
  color: #38405C;
  z-index: 100;
}
.orbit{
  position: absolute;
  top: 240px;
  left: 290px
}
.paragraph{
  margin: 2rem 0 0 5rem;
}
.p-text{
  font-family: Axiforma;
  font-style: normal;
  font-weight: 500;
  font-size: 19px;
  line-height: 35px;
  letter-spacing: 0.5px;
  color: #38405C;
  opacity: 0.6;
}
.btn-1 {
  margin: 2rem 0 0 5.5rem;
  color: #fff !important;
  background-color: #3BD6B2 !important;
  font-family: Axiforma;
  font-style: normal;
  font-size: 16px;
  line-height: 26px;
  text-transform: capitalize;
  text-align: center;
  opacity: 0.8;
  border-radius: 10px;
}
.modalBtn{
font-family: Axiforma;
font-style: normal;
font-size: 18px;
text-transform: capitalize;
padding: 30px;
color: #FFFFFF !important;
opacity: 0.8;
background: #19B490 !important;
border-radius: 16px;

}
.flex-display{
  /* width: 100px; */
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
}
.header-img{
  width: 100%;
}
.header-image{
  width: 100%;
  height: auto;
}
.reversed{
  max-width: 1440px;
  margin-bottom: 10rem;
}
.left-img{
  width: 100%;
}
.left-section-image{
  width: 100%;
  height: auto;
  border-radius: 0 50px 100px 0;
}
.second-section{
  width: 435.11px;
  margin: 0 0 3rem 3rem;
}
.sub-heading-text{
font-family: Axiforma;
font-style: normal;
font-weight: bold;
font-size: 36px;
line-height: 50px;
color: #38405C;
}
.paragraph-2{
  Width: 553px;
  margin: 0 0 0 3rem;
}
.bg{
  height: 1042px;
  max-width: 1440px;
  position: relative;
  /* margin: 5rem 0; */
}
.third-section{
  position: absolute;
  width: 20%;
  top: -7%;
  left: 18%;
}
.image-form{
  height: auto;
  width: 100%;
  /* position: absolute; */
}
.freelancers{
  margin: 5rem 0 0 -2rem;
}
.sub-head-text{
  font-family: 'Axiforma';
  font-style: normal;
  font-weight: 400;
  font-size: 30px;
  line-height: 49px;
  color: #FFFFFF
}
.p-text-3{
  font-family: 'Axiforma';
  font-style: normal;
  font-weight: 500;
  font-size: 19px;
  line-height: 35px;
  color: #FFFFFF;
  width: 471px;
}
.btn-2{
    color: #fff !important;
    background-color: #3BD6B2 !important;
    font-family: 'Axiforma';
    font-style: normal;
    font-size: 16px;
    line-height: 26px;
    text-transform: capitalize;
    text-align: center;
    opacity: 0.8;
    border-radius: 10px;
    /* transform: matrix(0.76, -0.57, 0.73, 0.77, 0, 0); */
}
.business{
  margin:  6rem 0 0 15rem;
}
.business-image{
  width: 20%;
  position: absolute;
  top: 75%;

}
.business-img{
  width: 284px;
  height: 380px;
}
.access{
  width: 100%;
}
.fourth-section{
  max-width: 1440px;
  margin: 8rem 0 0 0;
}
.sub-header-fourth{
  font-family: Axiforma;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 50px;
  color: #38405C;
  width: 435px;
  margin-left: 5rem;
}
.p-text-4{
  font-family: Axiforma;
  font-style: normal;
  font-weight: 500;
  font-size: 19px;
  line-height: 35px;
  color: #38405C;
  opacity: 0.6;
  width: 471px;
  margin: 2rem 0 3rem 5rem;
}
 .fourth-img{
    width: 100%;
  }
.fourth-image{
  width: 100%;
  height: auto;
}
.form{
  margin-left: 5rem;
}
.input-box{
  font-family: Axiforma;
  font-style: normal;
  font-weight: normal;
  font-size: 17px;
  line-height: 27px;
  letter-spacing: 0.02em;
  color: #BBCDEE;
  padding-left: 40px;

  width: 470px;
  height: 70px;
  background: #F8FCFE;
  border: 2px solid #F1F6FF;
  border-radius: 18px;
}
.fifth-section{
  max-width: 1440px;
  background-size: cover;
  height: 417px;
  width: 1240px; 
  margin: 8rem auto 0 auto;
  background-repeat: no-repeat;
}
.p-text-5{
  font-family: Axiforma;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 47px;
  width: 859px;
  text-align: center;
  color: #38405C;
  margin: 80px auto 60px auto;
}
.btn-3{
  background: #3BD6B2 !important;
  border-radius: 16px;
  font-family: 'Axiforma';
  font-style: normal;
  font-size: 16px;
  color: #FFFFFF !important;
  opacity: 0.8;
  text-transform: capitalize;
  margin: 0 auto;
}
.bbtn{
  text-align: center;
}
.eclipse{
  margin: 2rem 0 0 15rem;
  width: 20px;
}
.partnerships{
  padding: 40px 60px 0 60px;
}
.p-grid{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.partnership-header{
  font-family: Axiforma;
  font-style: normal;
  font-weight: bold;
  font-size: 30px;
  line-height: 50px;
  color: #38405C;
  margin-left: 1rem;
}

/* Mobile screen Responsitivity */
/* @media (max-width: 340px){
    .orbit{
      position: absolute;
      top: 250px;
      left: 0; 
    
  }
} */
@media (min-width: 340px) and (max-width: 960px){
  .text-section{
    margin: 5rem 0 2rem 0;
    width: 100%;
  }
  .header-text{
    font-size: 32px;
    width: 60%;
    margin: 0 2rem;
    z-index: 1;
  }
  .orbit{
    position: absolute;
    top: 260px;
    left: 0; 
  }
  .orbit-image{
    width: 200px;
  }
  .paragraph{
    margin: 0 auto;
    width: 100%;
  }
  .p-text{
    font-size: 18px;
    margin: 0 2rem;
  }
  .btn-1 {
    margin: 2rem 0 0 3rem;
  }
  .header-img{
    margin-top: 5rem;
  }
  .header-image{
    width: 100%;
    height: auto;
  }
 
  .grafiti{
    width: 90%;

  }
  .second-section{
    margin-left: 20px;
  }
  .sub-heading-text{
    font-size: 30px;
    width: 80%;
  }
  .paragraph-2{
    margin-left: -10px;
    width: 100%;
    
  }
  .left-section-image{
    width: 100%;
    height: auto;
    margin-top: 4rem;
  }
  .bg{
    margin: 0 auto;
    width: 100%;
  }
  .third-section{
    position: absolute;
    width: 100%;
    top: 0;
    left: 0;
    margin-top: -5rem;
    /* text-align: center; */
  }
  .image-form{
    width: 200px;
  }
  .freelancers{
    margin: 10rem 0 0 -11rem;
  }
  .btn-2-2{
    width: 100%;
  }
  .sub-fourth{
    width: 100%;
  }

  .sub-head-text{
    font-size: 20px;
    /* width: 100%; */
  }
  .showcase{
    font-size: 14px;
    width: 100%;
  }
  .p-text-3{
    font-size: 14px;
    /* width: 100%; */
  }
  .business-image{
    position: absolute;
    top: 43%;
    left: 0;
    width: 100%;
    /* text-align: center; */
  }
  .business-img{
    width: 230px;
    height: auto;
    margin-left: -2rem;
  }
  .business{
    margin: 15rem auto 0 auto;
    width: 88%;
  }
  .access{
    font-size: 14px;
    width: 100%;
    margin: 1rem 0;
  }
  .btn-2-div{
    text-align: center;
  }
  .fourth-section{
    margin: 6rem 0;
  }
  .sub-header-fourth{
    font-size: 30px;
    width: 100%;
    margin: 0 0;
    text-align: center;
  }
  .p-text-4{
    font-size: 18px;
    width: 100%;
    text-align: center;
    margin: 2rem 0;
  }
  .form{
    margin: 0 0 0 1rem;
  }
  .input-box{
    width: 95%;
    margin: 0 auto;
  }
  .fourth-image{
    margin-top: 5rem;
    width: 335px;
    height: auto;
  }
 
  .fifth-section{
    padding: 60px;
    background-size: cover;
    height: auto;
    width: 100%; 
    margin: 10rem 0 0 0;
    background-repeat: no-repeat;
}
  .p-text-5{
    font-size: 18px;
    width: 100%;
    margin: 50px auto 50px auto;
  }
  .eclipse{
    width: 20px;
    margin: 5rem 0 5rem 3rem;
  }
  .partnerships{
    text-align: center;
    padding: 0;
  }
}
/* medium and larger screens */
/* @media (min-width: 768px) and (max-width: 956px) {
   .text-section{
    margin: 5rem auto 2rem 2rem;
  }
  .header-text{
    font-size: 32px;
  }
  .orbit{
  position: absolute;
  top: 170px;
  left: 160px;
}
.orbit-image{
  width: 200px;
}
.paragraph{
  margin: 2rem auto;
}
.btn-1 {
  margin: 2rem 0 0 3rem;
}
.header-img{
    margin-top: 5rem;
    padding: 0;
    text-align: center;
  }
  .header-image{
    margin-left: -80px;
    width: 845px;
    height: auto;
  }
  .left-section-image{
  width: 100%;
  height: auto;
  border-radius: 0 50px 100px 0;
}
.paragraph-2{
  Width: 100%;
  margin: 0 auto;
}
.p-text{
  margin: 0 2rem;
}
.bg{
  width: 100%;
}
.third-section{
  position: absolute;
  width: 20%;
  top: -7%;
  left: 5%;
}
.business{
  margin:  10rem 0 0 1rem;
}
.fourth-section{
  margin: 10rem auto;
}
.sub-header-fourth{
  width: 90%;
  margin: 0 2rem;
}
.p-text-4{
  margin: 3rem 2rem;
  width: 90%;
}
.form{
  text-align: center;
}
.input-box{
  width: 86%;
  margin-right: 2rem;
}
.fourth-image{
  width: 765px;
  height: auto;
}
.fifth-section{
  width: 100%; 
}
.fifth-text-section{
  margin: 0 auto;
  width: 100%;
}

.p-text-5{
  width: 100%;
  margin: 80px auto;
}

} */
</style>
