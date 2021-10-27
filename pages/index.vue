<template>
  <div>
    <v-row justify="center" align="center">
       <v-col lg="6" md="8" sm="12">
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
          <v-btn depressed class="btn-1" x-large>Get access</v-btn>
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
    <v-row>
      <div class="row-reversedss">
        <v-col lg="6" md="8" sm="12">
        <img
          class="left-section-image"
          src="/image_002.png" 
          alt="image"
          />
      </v-col>
      <v-col lg="6" md="8" sm="12">
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
      </div>
    </v-row>
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
            <p class="p-text-3">
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
            <p class="p-text-3">
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
  data() {
    return { backgroundImg, backgroundImg2}
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
/* .orbit-image{
  position: absolute;
  top: 0;
  left: 20px;
} */
.header-image{
  width: 700px;
  height: 922px;
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
    border: 1px soild red;
    margin: 0 0 0 5rem;
    /* display: none; */
    width: 500px;
  }
  .sub-heading-text{
    width: 450px;
  }
  .paragraph-2{
    width: 454px;
  }
  .left-section-image{
    width: 480px;
    height: 500px;
    margin-top: 4rem;
  }
  .bg{
    width: 480px;
  }
  .third-section{
    position: absolute;
    width: 20%;
    top: -7%;
    left: 5%;
  }
  .freelancers{
    margin: 15rem 0 0 3rem;
    width: 100%;
  }
  .sub-head-text{
    font-size: 20px;
  }
  .p-text-3{
    font-size: 14px;
  }
  .business-image{
    position: absolute;
    top: 50%;
    left: 30%;
  }
  .business{
    margin:  20rem 0 0 3rem;
    width: 5%;
  }
  .fourth-section{
    margin: 0 2rem;
  }
  .input-box{
    width: 100%;
  }
  .fourth-image{
    margin-top: 5rem;
    width: 480px;
    height: 500px;
  }
  .fifth-section{
  /* border: 1px solid red; */
  background-size: cover;
  height: 800px;
  width: 480px; 

  /* min-height: 100%;
  min-width: 1024px; */
  /* padding: 20rem 20rem; */
  margin: 10rem auto 0 auto;
  background-repeat: no-repeat;
}
  .p-text-5{
    width: 276px;
  }
  .eclipse{
    width: 20px;
  }
}
@media (max-width: 480px) {
    .row-reverse{
    display: flex;
    flex-direction: column-reverse;
  }
  }
</style>
