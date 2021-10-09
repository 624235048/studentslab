<template>
  <div id="app">
    <Students v-bind:students1="students" />
  </div>
</template>


<script>
import Students from "./components/Students.vue";

export default {
  name: "App",
  components: {
    Students,
  },
  data() {
    return {
      students: [
        {
          studentId: "624235048",
          FistName: "Warinthon",
          LastName: "Kongjan",
          weight: 62,
          height: 175,
          picture:
            "https://raw.githubusercontent.com/624235048/imges/main/1.jpg",
        },
        {
          studentId: "624235049",
          FistName: "Suban",
          LastName: "Noksang",
          weight: 65,
          height: 172,
          picture:
            "https://raw.githubusercontent.com/624235048/imges/main/2.jpg",
        },
        {
          studentId: "624235051",
          FistName: "Yada",
          LastName: "banlatah",
          weight: 62,
          height: 165,
          picture:
            "https://raw.githubusercontent.com/624235048/imges/main/3.jpg",
        },
        {
          studentId: "624235052",
          FistName: "Wanasree",
          LastName: "sahasantiwarakul",
          weight: 70,
          height: 175,
          picture:
            "https://raw.githubusercontent.com/624235048/imges/main/4.jpg",
        },
        {
          studentId: "624235053",
          FistName: "Sofwan",
          LastName: "Chemusa",
          weight: 65,
          height: 180,
          picture:
            "https://raw.githubusercontent.com/624235048/imges/main/5.jpg",
        },
      ],
    };
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
