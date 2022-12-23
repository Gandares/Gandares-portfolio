<template>
<div id="ProfessionalContainer">
    <div id="ProfessionalImageAndTitle">
        <div class="element" style="width: 23%;"><img id="TitleImageProfessional" src="@/static/corporationbuildingicon.png" /></div>
        <div class="element" id="ProfessionalTitle">Professional Projects</div>
    </div>
    <div id="ProfessionalImageandDescription">
        <div style="text-align: center; padding-top: 4vh;"><img style="width: 37%" src="@/static/emptyfornow.png" /></div>
        <div style="text-align: center; padding-bottom: 4vh;"><img style="width: 37%;" src="@/static/travolta.gif" /></div>
    </div>
</div>
</template>

<style>

#ProfessionalContainer {     
    padding: 0;
}

#ProfessionalImageAndTitle {
    display: table;
    width: 100%;
    height: 100%;
    background-color: #333;
}

#ProfessionalTitle {
    float: left;
    font-size: 6vw;
    background-color: #333;
    color: white;
    padding-top: 3vh;
    padding-bottom: 3vh;
}

#TitleImageProfessional {
    float: right;
    width: 18%;
    margin-right: 10px;
}

#ProfessionalImageandDescription {
    background-color: #444;
}

</style>

<script>
export default {
  name: 'ProfessionalProject'
}
</script>