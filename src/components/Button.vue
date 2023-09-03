<template>
    <button  :style="{backgroundColor: color,cursor :pointer}" >{{text}}</button>
</template>

<script>
    export default {
        name : 'Button',
        props:{
            text:String,
            color:String
        }
    }
</script>