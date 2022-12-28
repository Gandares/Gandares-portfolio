<template>
    <div id="PagePersonalKingsAdventureContainer">
        <Header/>
        <div id="PagePersonalKingsAdventureTitle">King Adventure</div>
        <div id="PagePersonalKingsAdventureDescription">

        </div>
        <div id="PagePersonalKingsAdventureTechnologies">
            <img src="@/static/tecnologias/unity.png" />
            <img src="@/static/tecnologias/csharp.png" />
        </div>
        <div id="PagePersonalKingsAdventureImages">
            <img src="@/static/Juegos/Personales/kingAdventure/kingAdventure1.png" />
            <img src="@/static/Juegos/Personales/kingAdventure/kingAdventure2.png" />
            <img src="@/static/Juegos/Personales/kingAdventure/kingAdventure3.png" />
            <img src="@/static/Juegos/Personales/kingAdventure/kingAdventure4.png" />
            <img src="@/static/Juegos/Personales/kingAdventure/kingAdventure5.png" />
            <img src="@/static/Juegos/Personales/kingAdventure/kingAdventure6.png" />
            <img src="@/static/Juegos/Personales/kingAdventure/kingAdventure7.png" />
        </div>
    </div>
</template>

<style>

body {
    background-color: #444;
}

#PagePersonalKingsAdventureTitle {
    background-color: #333;
    color: white;
    font-size: 6vw;
    text-align: center;
    padding: 9vh 0 2vh 0;
}

#PagePersonalKingsAdventureDescription {
    color: white;
    font-size: 1.5vw;
    text-align: justify;
    padding: 2vh 5% 2vh 5%;
}

#PagePersonalKingsAdventureTechnologies {
    text-align: center;
}

#PagePersonalKingsAdventureTechnologies img {
    width: 7vw;
    height: 7vw;
    padding: 2vh 2.5% 2vh 2.5%;
}

#PagePersonalKingsAdventureImages {
    text-align: center;
}

#PagePersonalKingsAdventureImages img {
    height: 70vh; 
    width: auto;
    padding: 2vh 2.5% 2vh 2.5%;
}
</style>


<script>
import Header from '../../Header.vue';

export default {
    name: "PagePersonalKingAdventure",
    components: { Header }
}
</script>