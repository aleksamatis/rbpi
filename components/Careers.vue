<template>
  <div>
    <div class="careers-root-one">
      <div style="width:100%">
        <div class="careers-header-title">
          Работайте в RBPI!
        </div>
        <div style="display: flex; justify-content: space-between; margin-top: 25px; flex-wrap: wrap">
          <div class="careers-header-text">
            Мы ищем сорудников в свои подразделения в Калининградской и Нижегородской области. Узнайте больше об
            открытых вакансиях и работе в RBPI!</div>
          <div>
            <div class="careers-learn-more">Узнайте больше</div>
            <div
              style="font-style: normal; font-weight: normal; font-size: 22px; line-height: 24px; color: #38AE00;">
              Карьера в RBPI</div>
          </div>
        </div>
      </div>
    </div>
    <div class="careers-news">
      <div class="careers-news-item">
        <div />
        <img src="img/image-99.png" />
      </div>
      <div class="careers-news-item">
        <div />
        <img src="img/image-99.png" />
      </div>
      <div class="careers-news-item">
        <div />
        <img src="img/image-99.png" />
      </div>
    </div>
    <div class="careers-partnership">
      <div class="careers-partnership-item careers-partnership-text">
        <div>
          <p style="font-style: normal; font-weight: 500; font-size: 26px; line-height: 26px;">Работайте с нами! </p>
          <p style="font-family: Rubik; font-style: normal; font-weight:300; font-size: 18px; line-height: 24px; color: rgba(74, 74, 74, 0.8);">Мы работаем с крупными и проверенными компаниями, хорошо зарекомендовавшими себя на рынке.</p>
        </div>
        <div style="justify-self: flex-end">
          <span style="font-weight: 500; font-size: 16px; line-height: 26px;">Узнайте больше</span>
          <br />
          <span style="font-weight: normal; font-size: 22px; line-height: 24px; color: #38AE00;">Сотрудничество с RBPI</span>
        </div>
      </div>
      <div style=" background: no-repeat url(img/image-61.png);" class="careers-partnership-item">
        <img src="img/image-115.svg" />
        <span style="color:white">Продажи свиней</span>
      </div>
      <div style=" background: no-repeat url(img/image-61.png); " class="careers-partnership-item">
        <img src="img/image-102.svg" />
        <span style="color:white">Закупки</span>
      </div>
      <div style=" background: no-repeat url(img/image-555.png);" class="careers-partnership-item">
        <img src="img/image-100.svg" />
        <span style="color:white">Покупка земли</span>
      </div>
    </div>
  </div>
</template>

<style>
  .careers-root-one{
    display:flex;
    justify-content: space-between; 
    margin-top:120px;
    margin-bottom:60px;       
  }

   @media(max-width: 1350px) {
    .careers-root-one{
    display:flex;
    justify-content: space-between; 
    margin-top:120px;
    margin-bottom:60px;
    margin-left: 20px;       
  }
  }

  .careers-header-title {
    font-style: normal;
    font-weight: 500;
    font-size: 26px;
    line-height: 26px;
    color: #4A4A4A;
  }

  .careers-header-text {
    font-family: Rubik;
    font-style: normal;
    font-weight: 300;
    font-size: 18px;
    line-height: 24px;
    color: rgba(74, 74, 74, 0.8);
    max-width:750px
  }

  .careers-learn-more {
    font-weight: 500;
    font-size: 16px;
    color: #4A4A4A;
  }

  .careers-news {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }  
  
  @media(max-width: 1270px) {
    .careers-news {
      justify-content: space-around;
    }
  }

  @media(max-width: 850px) {
    .careers-news {
      justify-content: center;
    }
  }

  .careers-news-item {
    position: relative;
    width: 425px;
    margin-bottom: 30px;
    padding-right: 18px;
    display: flex;
  }

  .careers-news-item img {
    height: auto;
    max-width: 100%;
    z-index: 0;
  }

  .careers-news-item div {
    z-index: -1;
    background-color: black;
    opacity: 0.05;
    width: 406px;
    height: 100%;
    position: absolute;
    top: 18px;
    left: 18px;
  }

  @media(max-width: 500px) {
    .careers-news-item div {
      display: none;
    }
  }

  .careers-partnership {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-top: 100px;
    margin-bottom:100px
  }
    @media(max-width: 800px) {
     .careers-partnership {
    display: flex;
    flex-wrap: wrap;
    /* justify-content: space-between; */
    margin-top: 20px;
    justify-content: center;

  }
  }


  .careers-partnership-item {
    background-size: cover;
    height: 260px;
    width: 311px;
    display: flex;
    flex-flow: column;
    align-items: center;
    justify-content: center;
  }
 @media(max-width: 800px) {
  .careers-partnership-item {
    background-size: cover;
    height: 260px;
    width: 311px;
    display: flex;
    flex-flow: column;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
  }
  }

  .careers-partnership-item img {
    margin-bottom: 22px;
  }

  .careers-partnership-item span {
    font-size: 22px;
    font-family: Rubik;
    line-height: 26px;
  }

  .careers-partnership-text {
    align-items: flex-start;
    justify-content: space-between
  }

</style>
