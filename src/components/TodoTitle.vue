<template>
    <div class="title">
        <p class="title__message">{{ message }}</p>
        <p class="title__task">
            You've got
            <span>{{ taskTotal }}</span> tasks today.
        </p>
    </div>
</template>

<script lang="ts">
export default{
    data() {
        return {
            message: "Hello, nana.",
            taskTotal: 5
        }
    }    
}
</script>