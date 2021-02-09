<template>
  <div class="bg-gray-100 flex-col justify-center items-center border-black w-1/2">
    <div class="flex flex-col items-start justify-start">
      <!-- label and input -->
      <label class="text-black text-l mt-4 ml-4">Department</label>
      <input type="text" class=" border-black m-4 p-1">
    </div>

    <div class='flex items-end justify-end bg-gray-200 p-2'>
      <!-- button -->
      <button class="bg-purple-600 text-white p-2 m-1">Create Department</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
