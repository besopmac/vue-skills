<template>
    <div class="about">
        <h1>This is about page, {{ their_name }}</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta distinctio unde nostrum fugit ad ullam quam explicabo, voluptatum placeat animi!</p>
    </div>
</template>

<script>
    export default {
        name: 'Skills',
        data () {
            return {
                their_name: this.$route.params.name
            }
        }
    }
</script>
