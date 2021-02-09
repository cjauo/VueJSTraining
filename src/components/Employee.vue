<template>
<div class = "flex flex-col justify-center items-center h-screen">
    <div class ="flex-wrap bg-gray-100 text-left p-10 w-1/2">
        <label class="w-full font-sans font-bold text-indigo-400 text-4xl">Organization / </label>
        <label class="w-full font-sans font-bold text-black text-4xl"> Muzarik PLC Toy-O'Kon</label>
   
        <div class=" flex-wrap bg-white border border-collapse border-gray-300 rounded-t-sm mt-5">
            <div class = "flex pt-6 pl-6 pr-6 ml-2">
                <label class ="w-full font-sans font-bold text-yellow-500"> Basic Information </label>
            </div>
            <!-- Form -->
            <div class="flex flex-wrap p-6">
                <div class = "md:w-1/2 w-full lg:w-1/4 p-2">
                    <label class="w-full font-sans font-normal text-xl">First Name </label>
                    <input type="text" class ="border border-collapse border-black w-full">
                </div>
                <div class = "md:w-1/2 w-full lg:w-1/4 p-2 text-left">
                    <label class="w-full font-sans font-normal text-xl">Last Name </label>
                    <input type="text" class ="border border-collapse border-black w-full">
                </div>
                <div class = "md:w-1/2 w-full lg:w-1/4 p-2 text-left">
                    <label class="w-full font-sans font-normal text-xl">Email </label>
                    <input type="text" class ="border border-collapse border-black w-full">
                </div>
                <div class = "md:w-1/2 w-full lg:w-1/4 p-2 text-left">
                    <label class="w-full font-sans font-normal text-xl">Department </label>
                    <select class ="border border-collapse border-black w-full">
                        <option>CCSE</option>
                        <option>COB</option>
                    </select>
                </div>
            <!-- Form -->
            
            </div>
        </div>
        <!-- button -->
        <div class="flex justify-end items-end bg-gray-200">
            <button type="submit" class="bg-indigo-700 border border-collapse border-red-400 text-white font-sans pl-4 pr-4 pt-2 pb-2 m-4 rounded-md"> Update</button>
        </div>
        
    </div>
    
</div>
</template>

<script>
export default {
  name: 'Employee'
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
input{
    padding: 4px;
    border-radius: 5px;
}
select{
    padding: 6px;
    border-radius: 5px;
}
</style>
