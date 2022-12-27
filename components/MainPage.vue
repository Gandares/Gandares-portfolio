<template>
  <div id=MainPageContainer>
    <Header/>
    <SetUpImage/>
    <AboutMe/>
    <ProfessionalProjects/>
    <PersonalProjects/>
  </div>
</template>

<style>

#MainPageContainer{
  padding: 0;
  margin: 0;
}
</style>

<script>
import Header from './Header.vue';
import PersonalProjects from './PersonalProjects.vue';
import ProfessionalProjects from './ProfessionalProjects.vue';
import SetUpImage from './SetUpImage.vue';
import AboutMe from './AboutMe.vue';

export default {
    name: "MainPage",
    components: { PersonalProjects, Header, SetUpImage, AboutMe, ProfessionalProjects }
}
</script>