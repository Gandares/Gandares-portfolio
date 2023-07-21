<template>
    <div id="AboutMeContainer">
        <div id="ImageandTitle">
            <div class="element" style="width: 37%;"><img id="TitleImage" src="@/static/info.png" /></div>
            <div class="element" id="AboutMeTitle">About Me</div>
        </div>
        <div id="ImageandDescription">
            <div class="element"><img id="DescriptionImage" src="@/static/Positivo.png" /></div>
            <div class="element" id="AboutMeDescription">My name is Óscar González García, I am from Spain and I am 26 years old. I am graduated in Computer Engineering and master's degree in Videogame Development at the University of La Laguna. I love the world of computing and I would like to dedicate myself to it, specifically in the field of the master's degree.</div>
        </div>
    </div>
</template>

<style>
#AboutMeContainer {
    padding: 0;
    margin-top: -2vh;
}

#ImageandTitle {
    display: table;
    width: 100%;
    height: 100%;
    background-color: #333;
}

#AboutMeTitle {
    float: left;
    font-size: 6vw;
    background-color: #333;
    color: white;
    padding-top: 3vh;
    padding-bottom: 3vh;
}

#TitleImage {
    float: right;
    margin-right: 10px;
    width: 12%;
}

#ImageandDescription {
    display: table;
    height: 100%;
    background-color: #444;
}

.element {
    display: table-cell;
    vertical-align: middle;
}

#AboutMeDescription {
    margin-left: 10px;
    text-align: center;
    font-size: 1.6vw;
    line-height: 150%;
    color: white;
    padding: 4vh 5% 4vh 5%;
}

#DescriptionImage {
    width: 20vw;
    padding: 2vh 0 2vh 2vw;
}
</style>

<script>
export default {
  name: 'AboutMe'
}
</script>