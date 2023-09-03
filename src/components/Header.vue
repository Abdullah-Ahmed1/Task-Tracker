<template>
    <header>
        <h1>Task Tracker {{title}}</h1>
        <Button text = "Add Task" color = "green" />
    </header>
</template>

<script>
import Button from './Button.vue'
export default{
    name : 'Header',
    props:['title'],
    components:  {
        Button
    }
}
</script>

<!-- scoped style is specfically for the this component -->
<style scoped>
    header{
        display: block;
        justify-content: space-between;
        align-items: center;
    }
</style>