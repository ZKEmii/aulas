<template>
    <div>
        <h1>About</h1>
        <router-link to="/">Go to Home</router-link>
        {{ id }}
    </div>
</template>

<script>

export default {
    name: 'AulasAbout',
    computed:{
        id(){
            return this.$route.params.id
        }
    }
}
</script>