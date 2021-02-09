<template>
    <div class="flex justify-center items-center h-screen">
        <div class="flex flex-col w-1/5">
            <div class="flex flex-wrap bg-white p-8 border border-collapse border-gray-300 rounded-t-sm">
                <!-- label and input -->
                <label class="text-xl font-sans w-full text-left ml-2">Department</label>
                <input type='text' class='border border-collapse border-gray-300 mt-4 ml-2 p-1 w-full rounded-sm'>
            </div>
            <div class = "bg-gray-100 border border-collapse border-gray-300 flex justify-end items-end p-2">
                <!-- button -->
                <button class="bg-indigo-800 text-white font-sans rounded-md p-2 m-3 border-gray-300">Create Deparment</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Department'
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
