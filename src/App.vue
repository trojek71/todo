<template>
  <div id="app">
    <h4 class="bg-primary text-white text-center p-2">
      Lista zadań użytkownika {{name}}
    </h4>  
  </div>
</template>

<script>


export default {
  name: 'app',
  data(){
    return{
      name: "Tomek"
    }
  }
  
}
</script>


