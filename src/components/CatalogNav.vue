<template>
    <div class="nav">
        <span>Репродукция</span>
        <div class="items">
            <router-link to="/">Франция</router-link>
            <router-link to="/germany">Германия</router-link>
            <router-link to="/england">Англия</router-link>
        </div>
    </div>

</template>

<script>

</script>

<style scoped>
.nav {
    margin-left: auto;
    margin-right: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    max-width: 1110px;
    padding-left: 5vw;
    padding-right: 5vw;
}

span {
    font-weight: 500;
    font-size: 40px;
    line-height: 110%;

    color: #2C2D35;
}

.items {
    display: flex;
    gap: 20px;
}

a {
    padding: 10px 20px;

    background: #D4E8D9;
    border-radius: 20px;

    font-weight: 500;
    font-size: 20px;
    line-height: 23px;

    color: #2C2D35;
    text-decoration: none;
}

a.router-link-exact-active {
    padding: 10px 20px;

    background: #376B44;
    border-radius: 20px;

    font-weight: 500;
    font-size: 20px;
    line-height: 23px;

    color: #F4F6F5;
    text-decoration: none;
}

@media (max-width: 1052px) {}

@media (max-width: 768px) {
    span {
        font-weight: 500;
        font-size: 30px;
        line-height: 110%;
    }
}

@media (max-width: 576px) {
    .nav {
        align-items: flex-start;
        flex-direction: column;
        gap: 20px;
    }

    span {
        font-weight: 500;
        font-size: 24px;
        line-height: 110%;
    }

    a {
        margin-left: 0;
        margin-right: 20px;
    }

    .items {
        overflow: scroll;
    }
}

@media (max-width: 320px) {}
</style>
