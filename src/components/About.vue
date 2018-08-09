<template>
<div class="about">
    <h2> Hello {{their_name}}. This is an about page </h2>   
</div>
</template>

<script>
export default {
    data() {
        return{
            their_name: this.$route.params.name,
        }
    }
}
</script>
