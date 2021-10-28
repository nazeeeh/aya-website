<template>
<div class="logo">
 <img 
    class="ayalogo"
    src="/aya_logo.svg" 
    alt="Aya logo"
  />
</div>

</template>
<style scoped>
.ayalogo{
    width: 106px;
    height: auto;
    margin: 3rem 0 0 5rem;
}
@media (max-width: 480px) {
  .ayalogo{
    margin: 3rem 0 0 1rem;
  }
  
}
/* medium and larger screens */
@media (min-width: 768px) and (max-width: 1024px) {
  .ayalogo{
    margin: 3rem 0 0 2rem ;
  }
}
</style>