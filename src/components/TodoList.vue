<script>
export default {
    props: {
        todos: {
            type: Array
        }
    }
}
    
</script>

<template>
    <div>
        <p v-for="(todo, index) in todos" :key="index">{{ todo }}</p>
    </div>
</template>   