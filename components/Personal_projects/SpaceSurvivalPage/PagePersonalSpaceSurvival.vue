<template>
    <div id="PagePersonalSpaceSurvivalContainer">
        <Header/>
        <div id="PagePersonalSpaceSurvivalTitle">Space Survival</div>
        <div id="PagePersonalSpaceSurvivalDescription"><p>Vertical scrolling arcade video game where different enemies will appear above the screen. As time goes by, more variety of ships will appear and faster.</p>
            <p>Survive and get the most points possible with 3 lives.</p>
            <p>There are nine types of enemies:</p>
            <p>&emsp; - <span style="color:#ff8485" >Pink</span> Triangle: Very slow rectilinear movement.</p>
            <p>&emsp; - <span style="color:#580000" >Garnet Red</span> Triangle: Fast rectilinear movement.</p>
            <p>&emsp; - <span style="color:#f9fb63" >Light Yellow</span> Triangle: Slow rectilinear movement with slow firing.</p>
            <p>&emsp; - <span style="color:#b75400" >Orange</span> Triangle: Fast rectilinear movement with slow firing.</p>
            <p>&emsp; - <span style="color:#330097" >Strong Blue</span> Triangle: Fast rectilinear movement with rapid fire.</p>
            <p>&emsp; - <span style="color:#69ff00" >Loose Green</span> Triangle: Slow rectilinear movement with slow shotgun fire.</p>
            <p>&emsp; - <span style="color:#797979" >Gray</span> Triangle: Zig Zag movement with rapid fire.</p>
            <p>&emsp; - <span style="color:#174300" >Strong Green</span> Triangle: Zig Zag move with rapid shotgun fire.</p>
            <p>&emsp; - <span style="color:#ff0000" >Red</span> Circle: Zig Zag movement with shot to all sides.</p>
            <p>Some possible future improvements would be:</p>
            <p>&emsp; - Add music and sound effects.</p>
            <p>&emsp; - Add more enemies.</p>
            <p>&emsp; - Create models for the enemies so that they are not triangles.</p>
            <p>&emsp; - The game when dying, ends very abruptly, maybe add a screen that show the final score.</p>
            <p>&emsp; - The user's scores are saved or even create a database for store those of all players and display them with another menu option.</p>
        </div>
        <div id="PagePersonalSpaceSurvivalTechnologies">
            <img src="@/static/tecnologias/unity.png" />
            <img src="@/static/tecnologias/csharp.png" />
        </div>
        <div id="PagePersonalSpaceSurvivalImages">
            <img src="@/static/spaceSurvival1.png" />
            <img src="@/static/spaceSurvival2.png" />
            <img src="@/static/spaceSurvival3.png" />
            <img src="@/static/spaceSurvival4.png" />
            <img src="@/static/spaceSurvival5.png" />
            <img src="@/static/spaceSurvival6.png" />
        </div>
    </div>
</template>

<style>

body {
    background-color: #444;
}

#PagePersonalWordleTitle {
    background-color: #333;
    color: white;
    font-size: 6vw;
    text-align: center;
    padding: 9vh 0 2vh 0;
}

#PagePersonalWordleDescription {
    color: white;
    font-size: 1.5vw;
    text-align: justify;
    padding: 2vh 5% 2vh 5%;
}

#PagePersonalWordleTechnologies {
    text-align: center;
}

#PagePersonalWordleTechnologies img {
    width: 7vw;
    height: 7vw;
    padding: 2vh 2.5% 2vh 2.5%;
}

#PagePersonalWordleImages {
    text-align: center;
}

#PagePersonalWordleImages img {
    height: 30vw; 
    width: auto;
    padding: 2vh 2.5% 2vh 2.5%;
}

</style>


<script>
import Header from '../../Header.vue';
import InProcess from '../../InProcess.vue';

export default {
    name: "PagePersonalSpaceSurvival",
    components: { InProcess, Header }
}
</script>