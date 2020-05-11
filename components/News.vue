<template>
<div>
  <div class="news-container">
    <div><img src="img/image 57.png" class="news-items-image" />
      <div class="news-date">
        30.12.2020
      </div>
      <div  class="news-txt">
        Добрые дела в предверии Нового Года и Рождества
      </div>
    </div>
    <div><img src="img/image-56.png" class="news-items-image" />
      <div class="news-date">
        30.12.2020
      </div>
      <div  class="news-txt">
        РБПИ Групп инвестирует 7.2 млрд рублей в <br/>строительство двух свиноводческих комплексов в Нижегородской области
      </div>
    </div>

    <div><img src="img/image 58.png" class="news-items-image" />
      <div class="news-date">
        30.12.2020
      </div>
      <div class="news-txt">
        Проект строительства свинокомплекса в <br/>Большемурашкинском районе Нижегородской области получил статус приоритетного
      </div>
    </div>
    
    

    <div><img src="img/image 57.png" class="news-items-image" />
      <div class="news-date">
        30.12.2020
      </div>
      <div  class="news-txt">
        Добрые дела в предверии Нового Года и Рождества
      </div>
    </div>
    <div><img src="img/image-56.png" class="news-items-image" />
      <div class="news-date">
        30.12.2020
      </div>
     <div  class="news-txt">
        РБПИ Групп инвестирует 7.2 млрд рублей в <br/>строительство двух свиноводческих комплексов в Нижегородской области
      </div>
    </div>

    <div><img src="img/image 58.png" class="news-items-image" />
      <div class="news-date">
        30.12.2020
      </div>
      <div  class="news-txt">
        Проект строительства свинокомплекса в <br/>Большемурашкинском районе Нижегородской области получил статус приоритетного
      </div>
    </div>
   </div>
   <div style="text-align:center; margin-top:26px;">
     <button class="contacts-button">
          <span class="contacts-button-text">Все новости</span>
    </button>
   </div>
</div>
</template>

<style>
  .news-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  .news-container > div {
    margin-bottom: 40px;
  }

  .news-items-image {
      display: inline-block;
      max-width:100%;
      height: auto;
  }
    @media(max-width: 1270px) {
    .news-container {
      justify-content: space-around;
    }
  }
  @media(max-width: 850px) {
    .news-container {
      justify-content: center;
    }
  }
  .news-date {
    font-family: Rubik; 
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 17px;
    color: #38AE00;
    margin-top: 26px;
    margin-bottom: 23px;
  }
  .news-txt {
    font-family: Rubik; 
    font-size: 18px;
    max-width: 425px;
    font-weight: 300;
    font-size: 18px;
    line-height: 24px;
    color: rgba(74, 74, 74, 0.8);
  }

</style>
