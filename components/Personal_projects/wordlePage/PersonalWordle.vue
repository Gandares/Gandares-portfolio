<template>
    <div id="WordleContainer" v-on:click="toWordle">
        <div id="WordleTitle">Wordle Copy</div>
        <div id="WordleDescriptionAndImage">
            <img id="WordleImage" class="element" src="@/static/wordleImage.png" />
            <div id="WordleDescription" class="element">Challenge proposed by myself to make a copy of the famous web minigame "Wordle".</div>
        </div>
        <hr/>
    </div>
</template>

<style>

#WordleContainer:hover {
    background-color: #be00ff;
}

#WordleTitle {
    background-color: #be00ff;
    color: white;
    font-size: 3vw;
    text-align: center;
    padding-top: 20px;
    padding-bottom: 20px;
}

#WordleDescriptionAndImage {
    display: table;
    height: 100%;
}

#WordleImage {
    width: 80%;
    padding: 20px 5% 20px 5%;
}

#WordleDescription {
    color: white;
    font-size: 2vw;
    text-align: center;
    line-height: 150%;
    padding: 20px 5% 20px 0;
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