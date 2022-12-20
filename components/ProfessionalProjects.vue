<template>
<div id="ProfessionalContainer">
    <div id="ProfessionalImageAndTitle">
        <div class="element" style="width: 23%;"><img id="TitleImageProfessional" src="@/static/person-circle.png" /></div>
        <div class="element" id="ProfessionalTitle">Professional Projects</div>
    </div>
    <div></div>
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
    font-size: 400%;
    background-color: #333;
    color: white;
    padding-top: 30px;
    padding-bottom: 30px;
}

#TitleImageProfessional {
    float: right;
    width: 20%;
}


</style>

<script>
export default {
  name: 'ProfessionalProject'
}
</script>