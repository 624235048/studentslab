<template>
        <div class ="liststudent">
            <h1>{{student.studentId}}</h1><br/>
            <img v-bind:src="student.picture"/><br/>
            <b>FistName:</b>{{student.FistName}} <br/>
            <b>LastName:</b>{{student.LastName}} <br/>
            <b>Weight:</b>{{student.weight}} <br/>
            <b>Height:</b>{{student.height}} <br/>
             <br/> <br/>
            
        </div>

</template>

<script>
export default {
  name: 'Student',
  components: {
   
  },
  props:["student"]
  
  
}
</script>

<style>
</style>