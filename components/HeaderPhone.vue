<template>
  <div>
    <div class="contacts-root">
      <div class="header-phone-flex">
        <div>
          <img src="img/image-96.png" />
        </div>
        <div class="contacts-hotline contacts-hotline-padding">
          <div class="contacts-hotline-bottom">Горячая линия</div>
          <div class="contacts-phone-number">8 800 455 80 90</div>
        </div>
      </div>
      <div></div>
      <div></div>
      <button class="contacts-button">
        <div class="contacts-button-relative">
        <img src="img/comment-24.svg" class="contacts-button-absolute" />
        <span class="contacts-button-txtin">Напишите нам</span>
        </div>
      </button>
      <button class="contacts-button">
        <div class="contacts-button-relative">
        <img src="img/image-962.svg" class="contacts-button-absolute"  />
        <span class="contacts-button-txtin">Контакты RBPI</span>
        </div>
      </button>
    </div>
  </div>
</template>

<style>
 .header-phone-flex {
   display:flex; 
   align-content: center;
 }
  .contacts-root {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    margin-top: 65px;
    margin-bottom: 65px;
  }
  @media (max-width: 1350px) {
  .contacts-root{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    margin-top: 65px;
    margin-bottom: 65px;
    margin-left: 20px;
  }
  }
  .contacts-buttons {
    display: flex;
    justify-content: space-between; 
    flex-wrap:wrap;
  }
  @media (max-width: 900px) {
      .contacts-button {
          margin: 10px;
      }
  }
  .contacts-button {
    width: 280px;
    height: 58px;
    border: 2px solid #38AE00;
    box-sizing: border-box;
    border-radius: 8px;
    background-color: white;
    color: #38AE00;
    font-weight: 500;
    font-size: 18px;
  }
  .contacts-button-relative {
    position: relative;
  }
  .contacts-button-absolute {
    position:absolute; 
    left:20px;
  }
  .contacts-button-txtin {
    margin-left:37px
  }
  .contacts-hotline {
    font-family: Rubik;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 20px;
  }
  .contacts-hotline-padding {
    padding-left:20px; 
  }
  .contacts-hotline-bottom {
    margin-bottom:10px
  }
  .contacts-phone-number {
    font-family: Rubik;
    font-style: normal;
    font-weight: 300;
    font-size: 32px;
    line-height: 24px;
  }
</style>