<template>
    <div>
        
        <div v-bind:key="student.studentId" v-for="student in students1">
            <Student v-bind:student="student"/>
        </div>


    </div>
</template>

<script>
import Student from './Student.vue'
export default {
  name: 'Students',
  components: {
   Student
  },
  props:["students1"]
  
}
</script>

<style>
</style>