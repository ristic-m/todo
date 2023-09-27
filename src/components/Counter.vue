<script>
        export default {
    data() {
        return {
        count: 0
        };
    },
    methods: {
        increaseCount() {
            this.count++;
        },
        decreaseCount() {
            this.count--;
        }
    }
    };

</script>

<template>
    <p>Counter: {{ count }}</p>
    <button @click="decreaseCount">Decrease</button>
    <button @click="increaseCount">Increase</button>
</template>