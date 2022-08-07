<template>
    <div id="my-component">
        
            <h1>This is my component</h1>
            <h2>{{ subtitle }}</h2>
        
    </div>
</template>

<script>
export default {
    name: "MyComponent",
    data() {
        return {
            subtitle:  "I'm the subtitle of my component"
        }
    }
}
</script>