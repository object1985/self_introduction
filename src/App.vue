<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Profile></Profile>
  <Skill></Skill>
  <MyValues></MyValues>
  <OfferInformation></OfferInformation>
</template>

<script>
import Profile from "./components/Profile.vue";
import Skill from "./components/Skill.vue";
import MyValues from "./components/MyValues.vue";
import OfferInformation from "./components/OfferInformation.vue";

export default {
  name: "App",
  components: {
    Profile,
    Skill,
    MyValues,
    OfferInformation,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
