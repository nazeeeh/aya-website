<template>
<div class="logo">
 <img 
    class="ayalogo"
    src="/aya_logo.svg" 
    alt="Aya logo"
  />
  <p class="tagline">live borderless</p>
</div>

</template>
<style scoped>
.ayalogo{
    width: 106px;
    height: auto;
    margin: 3rem 0 0 5rem;
}
.tagline{
  text-transform: uppercase;
   font-family: Axiforma;
  font-style: normal;
  font-weight: 700;
  font-size: 11px;
  letter-spacing: 0.5px;
  /* opacity: 0.6; */
  margin-left: 5rem;
}
@media (min-width: 340px) and (max-width: 960px){
  .ayalogo{
    margin: 3rem 0 0 2rem;
  }
  
}
/* medium and larger screens */
/* @media (min-width: 768px) and (max-width: 1024px) {
  .ayalogo{
    margin: 3rem 0 0 2rem ;
  }
} */
</style>