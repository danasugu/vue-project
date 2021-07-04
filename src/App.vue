<template>
<div>
    <h1 class="text-4xl">Create Items</h1>
  <div class="m-2 p-2 bg-gray-200">ds</div>
  <input type="text" v-model="newItem" />
</div>

</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      newItem:'',
      items:[],
      }
    }
  };
</script>

<style></style>
