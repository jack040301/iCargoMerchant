<template>
    <div class="container login">
        <div class="center">
            <h1>Hi you are in a login page</h1>
            <a href="/profile"><button class="btn-primary p-2 btn">Login</button></a>
        </div>
    </div>
</template>

<script>
export default {
    name: 'LoginPage',
  
    methods: {
        goToHome() {
        this.$router.push('/');
        }
    }
}
</script>

<style scoped>

.login{
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
.center{
    text-align: center;
}

</style>