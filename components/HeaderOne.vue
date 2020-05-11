<template>
  <div>
    <div class="header-root">
      <div>
         <div>
          <h2 style="font-weight: 300; font-size: 32px; line-height: 52px; padding-top:14%;">Группа компаний RBPI
            занимается воспроизведением, <br>
            выращиванием и откормом свиней на собственных свиноводческих комплексах
            в Калининградской и Нижегородской областях.</h2>
        </div>
        <div style="display:flex; padding-top:4%; padding-bottom:10%;flex-wrap:wrap; justify-content:space-between; width:59%">
          <div style="display:flex; align-items: center; font-weight: 300; font-size: 22px;">Подробнее о RBPI <img src="img/image-119.png" style="margin-left:20px; margin-top:5px"/></div>
          <div style="display:flex; align-items: center; font-weight: 300; font-size: 22px;">Посмотрите фильм о нас <img src="img/image-45.png " style="margin-left:20px; margin-top:5px" /></div>
        </div>
        <div class="media-wrap-headerOne">
          <div style="border-left:1px solid white">
            <div style="display:flex; align-items:center;">
              <span class="item-header">Производство</span>
              <img src="img/image-115.png" class="img-header"/>
            </div>
            <div style="font-size: 16px; line-height: 24px; margin-left:20px; max-width:400px">RBPI занимается воспроизведением,
              выращиванием и откормом свиней на собственных свиноводческих комплексах.</div>
          </div>
          <div style="border-left:1px solid white">
            <div style="display:flex; align-items:center;">
            <span class="item-header">Экология</span>
            <img src="img/image-118.png" class="img-header"/>
            </div>
            <div style="font-size: 16px; line-height: 24px; margin-left:20px; max-width:400px">Экологически чистое производство — очень
              важные и очень значимые задачи для группы компаний RBPI.</div>
          </div>
          <div style="border-left:1px solid white">
            <div style="display:flex; align-items:center;">
            <span class="item-header">Сотрудничество</span>
            <img src="img/image-114.png" class="img-header"/>
            </div>
            <div style="font-size: 16px; line-height: 24px; margin-left:20px; max-width:400px">Мы работаем с крупными и
              проверенными компаниями, хорошо зарекомендовавшими себя на рынке.</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>

  .header-main-text {
    font-family: Rubik;
    font-weight: 300;
    font-size: 32px;
    line-height: 52px;
    padding-top:14%;
  }
  .header-root {
    text-shadow: 3px 3px 3px rgba(0, 0, 0, 0.45);
    min-height:916px;
    color: white;
  }
  .media-wrap-headerOne {
    display: flex;
    justify-content: space-between;
  }
  @media (max-width: 1400px) {
    .media-wrap-headerOne {
      display: flex;
      flex-wrap: wrap;
    }
  }
  .item-header {
    font-weight: 300; 
    font-size: 26px;
    margin-left:20px;
    margin-right: 20px;
  }
  .img-header {
    object-position: 0px 3px;
  }

</style>
