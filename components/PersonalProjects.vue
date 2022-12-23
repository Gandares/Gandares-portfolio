<template>
    <div id="PersonalContainer">
        <div id="PersonalImageAndTitle">
            <div class="element" style="width: 30%;"><img id="TitleImagePersonal" src="@/static/person-circle.png" /></div>
            <div class="element" id="PersonalTitle">Personal Projects</div>
        </div>
        <div id="PersonalImageandDescription">
            <PersonalWordle/>
            <InProcess/>
        </div>
    </div>
</template>
    
<style>

#PersonalContainer {     
    padding: 0;
}

#PersonalImageAndTitle {
    display: table;
    width: 100%;
    height: 100%;
    background-color: #333;
}

#PersonalTitle {
    float: left;
    font-size: 6vw;
    background-color: #333;
    color: white;
    padding-top: 3vh;
    padding-bottom: 3vh;
}

#TitleImagePersonal {
    float: right;
    width: 15%;
    margin-right: 10px;
}

#PersonalImageandDescription {
    background-color: #444;
}

</style>
    
<script>
import PersonalWordle from './Personal_projects/wordlePage/PersonalWordle.vue';

    export default {
    name: "PersonalProject",
    components: { PersonalWordle }
}
</script>