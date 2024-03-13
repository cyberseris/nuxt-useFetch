<template lang="">
    <div>
        <h1>使用者列表訊息 /users</h1>

        <!-- <h2>{{data}}</h2> -->
    </div>
</template>
<script lang="" setup>


useFetch('/api/hello').then(res=>{
        return console.log(res.data)
})


</script>
<style lang="scss">
    
</style>