<template>
<div>
    <button  v-on:click ="click()" >click </button>
    <button v-on:mouseover= "hover('this is over')" >mouse hover</button>
</div>
</template>



<script>
export default {

methods:{
 click(){
     alert("click event work")
 },
  hover(data){
  alert(data)
  }



}

}
</script>