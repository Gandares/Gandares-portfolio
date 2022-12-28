<template>
    <div id="SpaceSurvivalContainer" v-on:click="toWordle">
        <div id="SpaceSurvivalTitle">Space Survival</div>
        <div id="SpaceSurvivalDescriptionAndImage">
            <div id="SpaceSurvivalDescription" class="element">Arcade video game where different enemies will appear above the screen and the user has to survive. As time goes by, more variety of ships will appear and faster.</div>
            <img id="SpaceSurvivalImage" class="element" src="@/static/Juegos/Personales/spaceSurvival/spaceSurvival4.png" />
        </div>
        <hr/>
    </div>
</template>

<style>

#SpaceSurvivalContainer:hover {
    background-color: #be00ff;
    cursor: pointer;
}

#SpaceSurvivalTitle {
    background-color: #be00ff;
    color: white;
    font-size: 3vw;
    text-align: center;
    padding-top: 2vh;
    padding-bottom: 2vh;
}

#SpaceSurvivalDescriptionAndImage {
    display: table;
    height: 100%;
}

#SpaceSurvivalImage {
    width: 20vw;
    padding: 2vh 5% 2vh 25%;
}

#SpaceSurvivalDescription {
    color: white;
    width: 60%;
    font-size: 2vw;
    text-align: center;
    line-height: 150%;
    padding: 2vh 0 2vh 5%;
}
</style>

<script>
export default {
  name: 'SpaceSurvival',
  methods: {
    toWordle: function() {
        window.location.href = 'SpaceSurvival';
    }
  }
}
</script>