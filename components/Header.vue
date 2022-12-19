<template>
    <div id="HeaderContainer">
        <a href="#" id="GandaresHeader">Gandares</a>
        <a href="#AboutMeTitle" class="HeaderLinks">About Me</a>
        <a href="#" class="HeaderLinks">Professional Proyects</a>
        <a href="#" class="HeaderLinks">Personal Proyects</a>
        <a href="#" class="HeaderLinks">CV</a>
    </div>
</template>

<style>
#HeaderContainer {
    position: fixed;
    overflow: hidden;
    width: 100%;
    height: 51px;
    background-color: black;
    opacity: 0.5;
}

#GandaresHeader {
    height: 69%;
    font-size: 180%;
    padding: 8px 16px 8px 16px;
}

.HeaderLinks {
    height: 65%;
    padding: 18px 16px 0px 16px;
}

#HeaderContainer a {
    float: left;
    text-decoration: none;
    color: white;
    margin-right: 5px;
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