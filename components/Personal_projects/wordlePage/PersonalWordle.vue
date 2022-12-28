<template>
    <div id="WordleContainer" v-on:click="toWordle">
        <div id="WordleTitle">Wordle Copy</div>
        <div id="WordleDescriptionAndImage">
            <img id="WordleImage" class="element" src="@/static/Juegos/Personales/wordle/wordle2.png" />
            <div id="WordleDescription" class="element">Challenge proposed by myself to make a copy of the famous web minigame "Wordle".</div>
        </div>
        <hr/>
    </div>
</template>

<style>

#WordleContainer:hover {
    background-color: #be00ff;
    cursor: pointer;
}

#WordleTitle {
    background-color: #be00ff;
    color: white;
    font-size: 3vw;
    text-align: center;
    padding-top: 2vh;
    padding-bottom: 2vh;
}

#WordleDescriptionAndImage {
    display: table;
    height: 100%;
}

#WordleImage {
    width: 35vw;
    padding: 2vh 5% 2vh 5%;
}

#WordleDescription {
    color: white;
    width: 60%;
    font-size: 2vw;
    text-align: center;
    line-height: 150%;
    padding: 2vh 5% 2vh 0;
}
</style>

<script>
export default {
  name: 'wordle',
  methods: {
    toWordle: function() {
        window.location.href = 'wordle';
    }
  }
}
</script>