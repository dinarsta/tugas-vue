<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1>{{ msg }}</h1>
    <h5>
      Front End Developer
     
    </h5>
    
  </div>
</template>

<style>
.greetings h5{
    color:#395B64;
}
h1{
  color:black;
      margin-top: 100px;
}
h5{
  margin-bottom: 20px;
}
</style>