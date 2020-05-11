<template>
<div class="video-root">
    <div class="video-root-image">
        <img src="img/image-101.png">
        <div class="darken-background"/>
        <div class="video-overlay">
            <div>
                <div class="video-watch-text">
                    Посмотрите 30-минутный фильм о нашем производстве и команде увлеченных своим делом людей.
                </div>
                <div class="video-title">Экскурсия на ферму XXI века</div>
            </div>
            <img src="img/image-45.svg" class="video-title-img"/>
        </div>
    </div>
</div>
</template>

<style>
.video-root {
    background-color: #EEF2F3;
    color: white;
    width:100%;
    display:flex;
    justify-content: center;
    padding-top: 80px;
    padding-bottom: 80px;
    padding-left:21%;
    padding-right:21%;
}
@media(max-width: 800px) {
    
}
.video-root-image {
    position: relative;
}

.video-root-image img {
    max-width: 100%;
    height: auto;
}

.video-overlay {
    position: absolute;
    width: 100%;
    height: 100%;
    display: flex;
    top: 0px;
    padding: 40px;
    font-size: 20px;
}

.video-overlay div {
    display: flex;
    justify-content: space-between;
    flex-flow: column;
    font-family: Rubik;
    text-shadow: 3px 3px 3px rgba(0, 0, 0, 0.55);
}

.video-watch-text {
    width: 50%;
}

.video-title {
    font-size: 2em;
}

.video-title-img {
    align-self: flex-end;
    justify-self: end;
}

@media(max-width: 1000px) {
    .video-root {
        padding: 20px;
    }
    .video-overlay {
        padding: 10px;
        font-size: 3vw;
    }
    .video-watch-text {
        width: 100%;
    }
    .video-title-img {
        width: 100px;
        height: auto;
    }
}

</style>
