<template>
  <div id="app">
    <h1>{{title}}</h1>
    <p v-for="item in items" :key="item">{{item}}</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      title:"this is the title",
      items:[
        "this is item 1",
        "this is item 2",
        "this is item 3",
        "this is item 4",
        "this is item 5"
      ],
      }
    }
  };
</script>

<style></style>
