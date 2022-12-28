<template>
    <div id="KingsAdventureContainer" v-on:click="toWordle">
        <div id="KingsAdventureTitle">King Adventure</div>
        <div id="KingsAdventureDescriptionAndImage">
            <img id="KingsAdventureImage" class="element" src="@/static/Juegos/Personales/kingAdventure/kingAdventure2.png" />
            <div id="KingsAdventureDescription" class="element">Platform video game about a king to have to reach a door at the end of the level. This project was made to explore how to create and program this kind of video games.</div>
        </div>
        <hr/>
    </div>
</template>

<style>

#KingsAdventureContainer:hover {
    background-color: #be00ff;
    cursor: pointer;
}

#KingsAdventureTitle {
    background-color: #be00ff;
    color: white;
    font-size: 3vw;
    text-align: center;
    padding-top: 2vh;
    padding-bottom: 2vh;
}

#KingsAdventureDescriptionAndImage {
    display: table;
    height: 100%;
}

#KingsAdventureImage {
    width: 45vw;
    padding: 2vh 0 2vh 5%;
}

#KingsAdventureDescription {
    color: white;
    width: 50%;
    font-size: 2vw;
    text-align: center;
    line-height: 150%;
    padding: 2vh 5% 2vh 0;
}
</style>

<script>
export default {
  name: 'KingAdventure',
  methods: {
    toWordle: function() {
        window.location.href = 'KingAdventure';
    }
  }
}
</script>