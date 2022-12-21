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
import PersonalProjects from './PersonalProjects.vue';

export default {
    name: "MainPage",
    components: { PersonalProjects }
}
</script>