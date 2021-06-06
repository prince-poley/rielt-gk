<template>
    <div class="home">
        <Navbar></Navbar>
        <main class="container-fluid mt-5">
            <h1>Домашняя страница</h1>
        </main>
    </div>
</template>

<script>
import Navbar from '../components/Navbar';

export default {
    name: 'Home',
    components: { Navbar },
};
</script>
