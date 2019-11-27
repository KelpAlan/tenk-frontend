<template>
    <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand>
            <Logo />
        </b-navbar-brand>
        <b-navbar-nav class="ml-auto">
            <b-nav-item>
                <router-link to="/">Home</router-link>
            </b-nav-item>
            <b-nav-item>
                <router-link to="/about">About</router-link>
            </b-nav-item>
        </b-navbar-nav>
    </b-navbar>
</template>

<script>
import Logo from "@/components/Header/Logo.vue"
export default {
    name: "Header",
    components: {
        Logo,
    }
}
</script>

<style scoped>
#header {
    background-color: #6afcb3;
    text-align: left;
    display: flex;
}

router-link {
    color: white
}

</style>