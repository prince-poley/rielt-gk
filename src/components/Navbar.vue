<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <div class="collapse navbar-collapse" id="navbarText">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <router-link class="nav-link" to="/">Главная</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" to="/about">Квартиры</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" to="/about">Дома</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" to="/about">Участки</router-link>
                </li>
            </ul>
        </div>
    </div>
</nav>
</template>

<script>
export default {
    name: 'Navbar',
};
</script>

<style scoped>

</style>