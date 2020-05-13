<template>
<div>
    <div class="main-menu-root">
        <div class="main-menu-relative">
            <img src="img/PSP-logotip.png" />
            <img src="img/RBPI-Group.png" class="main-menu-img-absolute"/>
        </div>
        <div class="main-menu-li">
            <li>Компания</li>
            <li>Новости</li>
            <li>Производство</li>
            <li>Экология</li>
            <li>Карьера</li>
            <li>Сотрудничество</li>
            <li>Контакты</li>
            <div>
            <img src="img/menu_24px.png" class="img-cursor"/>
            <img src="img/24px.png" class="img-cursor"/>
            </div>
        </div>
    </div>
</div>
</template>

<style>
.main-menu-relative {
position: relative; 
cursor: pointer; 
margin-right: 3%   
}
.main-menu-img-absolute {
position:absolute; 
left:35px; 
top:30px
}
.main-menu-li {
    color:white; 
    display:flex; 
    flex-wrap: wrap; 
    list-style-type: none; 
    width: 1000px; 
    justify-content: space-between;
}
.img-cursor {
    cursor: pointer
}
.main-menu-root {
    display:flex;
    align-items: center;
    justify-content: center;
    padding-top:40px;
    font-family: Rubik;
    text-transform: uppercase;
    text-shadow: 3px 3px 3px rgba(0, 0, 0, 0.45);
}
</style>
