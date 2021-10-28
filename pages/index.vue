<template>
  <div>
     
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
                skillsand get matched to companies.
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
    <div class="reversed">
      <v-row>
        <v-col lg="6" md="8" sm="12">
        <img
          class="left-section-image"
          src="/image_002.png" 
          alt="image"
          />
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
        <v-col>
          <div class="third-section">
            <img 
            class="image-form"
            src="/image_003.png" 
            alt="image"
          />
          </div>
        </v-col>
        <v-col>
          <div class="freelancers">
            <h3 class="sub-head-text">
              Freelancers:
            </h3>
            <p class="p-text-3 showcase">
              Showcase your skills to the world, get 
              matched with both local and international 
              companies and get paid, all hassle-free.
            </p>
            <v-btn class="btn-2" depressed x-large>
              Fill Our Talent Form
            </v-btn>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col>
          <div class="business">
            <h3 class="sub-head-text">
              Businesses:
            </h3>
            <p class="p-text-3 access">
              Access the best and largest pool of African freelancers 
              to take your business to the next level, enjoy instant and
               borderless peer-to-peer cryptocurrency payments with 100% 
               Security guaranteed.
            </p>
            <v-btn class="btn-2" depressed x-large>
              Fill Our Talent Requirement Form
            </v-btn>
          </div>
        </v-col>
        <v-col>
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
    <v-row>
      <v-col>
         <div class="fourth-section">
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
      <v-col>
        <img
          class="fourth-image" 
          src="/image_005.png" 
          alt="image"
        />
      </v-col>
    </v-row>
      <v-row no-gutters dense class="fifth-section mr-10" :style="{backgroundImage :`url(${backgroundImg2})`}">
        <v-col>
          <div class="fifth-text-section" justify="center">
            <p class="p-text-5">
              We are creating opportunities for African digital skilled talents 
              to offer their services to the global workforce, starting from Africa.  
              Missed the button above by chance? Well lucky you, we’ve got another here. 
            </p>
            <div class="bbtn">
               <v-btn class="btn-3" depressed x-large>Get access</v-btn>
            </div>
          </div>
        </v-col>
      </v-row>
      <div>
        <img class="eclipse" src="/eclipse.svg" alt="image">
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
}
.orbit{
  position: absolute;
  top: 220px;
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
  margin: 2rem 0 0 5rem;
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
  /* transform: matrix(0.76, -0.57, 0.73, 0.77, 0, 0); */
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
/* padding: 40px; */

/* width: 405px; */

}
.flex-display{
  /* width: 100px; */
  display: flex;
  justify-content: space-between;
  margin: 0 auto;

}
.header-image{
  width: 700px;
  height: 922px;
}
.reversed{
  width: 100%;
  margin-bottom: 10rem;
}
.left-section-image{
  width: 650px;
  height: 650px;
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
  width: 1473px;
  position: relative;
  margin: 10em 0;
  /* background-image: require(url('/background.png')); */
}
.third-section{
  position: absolute;
  width: 20%;
  top: -7%;
  left: 18%;
}
.image-form{
  height: 370px;
  width: 290px;
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
  margin:  10rem 0 0 15rem;
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
.fourth-section{
  margin: 10rem 0 0 5rem;
}
.sub-header-fourth{
  font-family: Axiforma;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 50px;
  color: #38405C;
  width: 435px;
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
  margin: 2rem 0 3rem 0;
}
.fourth-image{
  width: 680px;
  height: 922px;
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
  /* border: 1px solid red; */
  background-size: cover;
  height: 417px;
  width: 1240px; 
  /* padding: 20rem 20rem; */
  margin: 10rem auto 0 auto;
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
  /* width: 20%; */
  margin: 0 auto;
  /* margin: 0 45%; */
}
.bbtn{
  text-align: center;
}
.eclipse{
  margin: 2rem 0 0 15rem;
  width: 20px;
}

/* Mobile screen Responsitivity */
@media (max-width: 480px){
  .text-section{
    margin: 5rem 0 2rem 1rem;
  }
  .header-text{
    /* width: 260px; */
    font-size: 32px;
  }
  .orbit{
    position: absolute;
    top: 170px;
    left: 150px; 
  }
  .orbit-image{
    width: 200px;
  }
  .paragraph{
    margin: 0 auto;
    width: 350px; 
  }
  .p-text{
    font-size: 18px;
    width: 350px;
  }
  .btn-1 {
    margin: 2rem 0 0 1rem;
  }
  .header-img{
    margin-top: 5rem;
    padding: 0;
    text-align: center;
  }
  .header-image{
    margin-left: -55px;
    width: 430px;
    height: 600px;
  }
  .grafiti{
    margin: 0 0 0 2rem;
    width: 370px;
  }
  .second-section{
    margin: 0 0 3rem 1rem;
  }
  .sub-heading-text{
    font-size: 30px;
    width: 400px;
  }
  .paragraph-2{
    margin: 0 1rem 5rem 1rem;
    width: 350px;
  }
  .left-section-image{
    width: 380px;
    height: auto;
    margin-top: 4rem;
  }
  .bg{
    margin: 0 auto;
    width: 100%;
   
  }
  .third-section{
    position: absolute;
    width: 20%;
    top: -7%;
    left: 5%;
  }
  .freelancers{
    margin: 15rem 0 0 -200px;
    /* width: 100%; */
  }
  .sub-head-text{
    font-size: 20px;
    width: 100%;
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
    top: 45%;
    left: 30%;
  }
  .business{
    margin:  15rem 0 0 0;
  }
  .access{
    font-size: 14px;
    width: 100%;
  }
  .fourth-section{
    margin: 6rem 0 0 0;
  }
  .sub-header-fourth{
    font-size: 30px;
    width: 400px;
    margin: 0 0 0 1rem;
  }
  .p-text-4{
    font-size: 18px;
    width: 350px;
    margin: 2rem auto;
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
    width: 100%;
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
    width: 276px;
    margin: 50px auto 50px auto;
  }
  .eclipse{
    width: 20px;
    margin: 5rem 0 5rem 3rem;
  }
}
/* medium and larger screens */
@media (min-width: 768px) and (max-width: 1024px) {
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
 
  /* text-align: center; */
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
  /* height: auto; */
}
.fifth-text-section{
  margin: 0 auto;
  width: 100%;
}

.p-text-5{
  width: 100%;
  margin: 80px auto;
}


}
</style>
