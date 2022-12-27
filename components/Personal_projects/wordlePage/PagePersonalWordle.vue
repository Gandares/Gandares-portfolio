<template>
    <div id="PagePersonalWordleContainer">
        <Header/>
        <div id="PagePersonalWordleTitle">Wordle Copy</div>
        <div id="PagePersonalWordleDescription"><p>This was a project made for a subject, the main idea was create a simple game using the HTML element canvas.</p>
            <p>This is a web application made with nodejs and express in the backend, and html, css y javascript in the frontend.</p>
            <p>There is no much to say about this application because it's a copy, but in the case that the lector does not know, the minigame is explained below.</p>
            <p>The main objective is guess a five letters spanish word. There is a json file with the 10836 possibles words and the program takes one randomly.</p>
            <p>The user have to write words up to a total of 6. When a word is written, the letters will be colored a single color. The colors mean:</p>
            <p>&emsp; - <span style="color:#797979">Grey</span>: The letter does not match any of the final word.</p>
            <p>&emsp; - <span style="color:#f3ff00">Yellow</span>: The final word contains that letter but it's in the wrong spot.</p>
            <p>&emsp; - <span style="color:#008c0f">Green</span>: The final word contain that letter and it's in the correct spot.</p>
            <p>Everytime the page refreshes, the program chooses another random word allowing the user to play again.</p>
        </div>
        <div id="PagePersonalWordleTechnologies">
            <img src="@/static/tecnologias/nodejs.png" />
            <img src="@/static/tecnologias/express.png" />
            <img src="@/static/tecnologias/html.png" />
            <img src="@/static/tecnologias/css.png" />
            <img src="@/static/tecnologias/javascript.png" />
            <img src="@/static/tecnologias/json.png" />
        </div>
        <div id="PagePersonalWordleImages">
            <img src="@/static/wordle1.png" />
            <img src="@/static/wordle2.png" />
        </div>
    </div>
</template>

<style>

body {
    background-color: #444;
}

#PagePersonalSpaceSurvivalTitle {
    background-color: #333;
    color: white;
    font-size: 6vw;
    text-align: center;
    padding: 9vh 0 2vh 0;
}

#PagePersonalSpaceSurvivalDescription {
    color: white;
    font-size: 1.5vw;
    text-align: justify;
    padding: 2vh 5% 2vh 5%;
}

#PagePersonalSpaceSurvivalTechnologies {
    text-align: center;
}

#PagePersonalSpaceSurvivalTechnologies img {
    width: 7vw;
    height: 7vw;
    padding: 2vh 2.5% 2vh 2.5%;
}

#PagePersonalSpaceSurvivalImages {
    text-align: center;
}

#PagePersonalSpaceSurvivalImages img {
    height: 30vw; 
    width: auto;
    padding: 2vh 2.5% 2vh 2.5%;
}

</style>

<script>
import Header from '../../Header.vue';
import InProcess from '../../InProcess.vue';

export default {
    name: "PagePersonalWordle",
    components: { InProcess, Header }
}
</script>