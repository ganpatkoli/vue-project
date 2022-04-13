<template>
    <div>
        <h1> this is first page</h1>
        <h2>{{props}}</h2>
        <h2>{{msg}}</h2>
    </div>
</template>

<script>
export default {
        name:'pagefirst',
       props : {
      msg:  String ,
    }


}
</script>>