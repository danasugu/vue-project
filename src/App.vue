<template>
<div>
    <h1 class="text-4xl">Create Items</h1>
  <div class="m-2 p-2 bg-gray-200">
  <input class="bg-blue-200 p-2 m-2 rounded" type="text" v-model="newItem" />
  <button class="ml-5 p-2 bg-pink-300 rounded" @onclick="storeItem">Save</button>
  </div>
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
