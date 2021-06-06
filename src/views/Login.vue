<template>
<main class="form-signin">
    <form>
        <h1 class="h3 mb-3 fw-normal">Вход</h1>
        <input
            type="text"
            class="form-control form-control-sm"
            id="login"
            placeholder="Логин"
            autocomplete="off"
        >
        <input
            type="password"
            class="form-control form-control-sm mt-3 mb-3"
            id="password"
            placeholder="Пароль"
            autocomplete="off"
        >
        <button class="w-100 btn btn-dark" type="submit">Войти</button>
    </form>
</main>
</template>

<script>
export default {
    name: 'Login',
};
</script>

<style scoped>
.form-signin {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 15px;
    text-align: center;
    margin-top: 300px;
}
</style>