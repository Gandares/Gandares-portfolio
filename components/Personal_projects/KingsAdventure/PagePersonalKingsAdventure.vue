<template>
    <div id="PagePersonalKingsAdventureContainer">
        <Header/>
        <div id="PagePersonalKingsAdventureTitle">King Adventure</div>
        <div id="PagePersonalKingsAdventureDescription"><p>King Adventure is a platform video game created principally to explore the mechanics of this kind of games.</p>
            <p>The game map is composed of 2 zones, the tutorial and the cave.</p>
            <p>&emsp; - The first part explains the controls and have a low difficulty. At some point of this first stage, there are a few boxes blocking the way, forcing the player to follow the path going up. Once the user reach the top, there is a sanctuary where is a chest that contains a sword (that being used to destroy the boxes).</p>
            <p>&emsp; - Once the player destroys the boxes, the entrance to the cave is clear and start the second stage of the video game, the tutorial was clear and now the user have to use all the knowledge and abilities obtained. The cave has a medium difficulty and some obstacles to pass through to reach the end.</p>
            <p>The mechanics that I wanted to explore in this game were:</p>
            <p>&emsp; - Checkpoints.</p>
            <p>&emsp; - Respawn.</p>
            <p>&emsp; - Moving platforms.</p>
            <p>&emsp; - Destroyable boxes.</p>
            <p>&emsp; - Movement (A little rough)</p>
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