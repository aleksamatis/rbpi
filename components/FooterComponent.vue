<template>
<div class="footer-root">
  <div class="footer-color-size-txt">
      © 2005–2020 АО «Правдинское свинопроизводство»
      <br />
      По вопросам работы сайта <span class="footer-color-mail">admin@rbpi.no </span>
      <br />
      Creative Commons Attribution 4.0 International
   </div>   
   <div>
      <div>
      <span>Горячая линия</span>
      <br />
      <span class="footer-color-size-phone">8 800 300 77 00</span>
      <div>
      <img src="img/Group-131.svg">
      <img src="img/Group-132.svg">
      </div>
      </div>
   </div>
   <div>
   <div class="footer-columns-contacts">
      <div class="color-contacts">Контакты</div>
      <div class="color-contacts">Карта сайта</div>
      <div class="color-contacts">Правила сайта</div>
   </div>
   </div>
</div>
</template>

<style>
.footer-color-size-txt {
   color: #4A4A4A; 
   font-family: Rubik; 
   font-size: 14px; 
}
.footer-color-mail {
   color: #38AE00;
}
.footer-color-size-phone {
   font-weight: 500; 
   font-size: 18px; 
   line-height: 24px; 
   color: #38AE00;
}
.footer-columns-contacts {
   flex-direction:column; 
}
.color-contacts {
   color:#38AE00;
   font-weight: 500;
}
.footer-root {
   display:flex; 
   justify-content:space-between; 
   padding:50px; 
   padding-bottom:70px; 
}
 @media (max-width: 800px) {
    .footer-root {
       display:flex; 
       justify-content:space-between; 
       padding:50px; 
       padding-bottom:70px; 
       text-align: left;
       flex-direction:column;
       padding-left: 20px;
    }
  }
</style>