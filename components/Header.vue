<template>
    <div id="HeaderContainer">
        <a href="#" id="GandaresHeader">Gandares</a>
        <a href="#AboutMeContainer" class="HeaderLinks">About Me</a>
        <a href="#ProfessionalContainer" class="HeaderLinks">Professional Proyects</a>
        <a href="#PersonalContainer" class="HeaderLinks">Personal Proyects</a>
        <a href="#" class="HeaderLinks">CV</a>
    </div>
</template>

<style>
#HeaderContainer {
    position: fixed;
    overflow: hidden;
    width: 100%;
    height: 8vh;
    background-color: black;
    opacity: 0.5;
}

#GandaresHeader {
    height: 4vh;
    font-size: 2.1vw;
    padding: 1.5vh 2vw 3vh 2vw;
}

.HeaderLinks {
    height: 3vh;
    font-size: 1.2vw;
    padding: 2.5vh 2vw 2.5vh 2vw;
}

#HeaderContainer a {
    float: left;
    text-decoration: none;
    color: white;
    margin-right: 1vw;
}

#HeaderContainer a:hover {
    background-color: #ddd;
    color: black;
    opacity: 1;
}
</style>

<script>
export default {
  name: 'Header'
}
</script>