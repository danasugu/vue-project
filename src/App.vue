<template>
  <div id="app">
    <h1>{{title}}</h1>
    <input v-model="title" type="text" />
    <p v-for="item in items" :key="item.id">ID: {{ item.id }} {{item.title}}</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      title:"this is the title",
      items:[
      {id:1, title:"this is item 1"},  
      {id:2, title:"this is item 2"},  
      {id:3, title:"this is item 3"},  
      {id:4, title:"this is item 4"},  
      {id:5, title:"this is item 5"},  
         ],
      }
    }
  };
</script>

<style></style>
