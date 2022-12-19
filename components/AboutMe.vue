<template>
    <div id="AboutMeContainer">
        <div id="AboutMeTitle"><img src="@/static/person-circle.svg" />About Me</div>
        <div id="AboutMeDescription"><img src="@/static/Positivo.png" />My name is Óscar González García, I am from Spain and I am 25 years old. I am graduated in Computer Engineering and master's degree in Videogame Development at the University of La Laguna. I love the world of computing and I would like to dedicate myself to it, specifically in the field of the master's degree.</div>
    </div>
</template>

<style>
#AboutMeContainer {
    padding: 0;
    margin-top: -5px;
}

#AboutMeTitle {
    text-align: center;
    width: 100%;
    font-size: 300%;
    background-color: #333;
    color: white;
    padding-top: 30px;
    padding-bottom: 30px;
}

#AboutMeTitle img {
    width: 30px;
    height: 30px;
}

#AboutMeDescription {
    text-align: justify;
    background-color: #444;
    color: white;
    padding: 50px 5% 50px 5%;
}

#AboutMeDescription img {
    width: 40%;
}
</style>

<script>
export default {
  name: 'AboutMe'
}
</script>