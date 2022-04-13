<template>
    <h1 v-if="ifstate" >hello world</h1>
    <button v-on:click= "Display()" >conditnal state</button>
</template>

<script>

export default {   
 data(){
return  {show:true}
 },
method :{
    Display(){
        this.show =true
    }
}

}
</script>