<template>
    <div class="container">
        <div class="header">
            <div class="header-logo">
                <img src="../../src/assets/house-logo.png" alt="Header logo" width="35px">
                <span class="header-title">Ink. House</span>
            </div>
            <div class="header-nav">
                <span>Репродукции</span>
                <span>Новинки</span>
                <span>О нас</span>
                <img class="cart" src="../../src/assets/cart.png" alt="Cart icon" width="24px">
            </div>
        </div>
    </div>

</template>

<style>
.header {
    max-width: 1110px;
    height: 100px;
    margin-left: auto;
    margin-right: auto;
    padding-left: 5vw;
    padding-right: 5vw;
    
    display: flex;
    justify-content: space-between;
}

.container {
    width: 100%;
    background-color: #E1EDE6;
}

.header-logo {
    display: flex;
    align-items: center;
}

.header-logo img {
    margin-right: 8px;
}

.header-title {
    font-style: normal;
    font-weight: 700;
    font-size: 20px;
    line-height: 23px;
    color: #598D66;
}

.header-nav {
    display: flex;
    align-items: center;
    gap: 50px
}

.header-nav span {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 23px;
    color: #2C2D35;
}

@media (max-width: 768px) {
    .header {
        max-width: 690px;

    }

    .header-title {
        font-style: normal;
        font-weight: 700;
        font-size: 20px;
        line-height: 23px;
    }

    .header-nav span {
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
    }
}

@media (max-width: 576px) {
    .header {
        max-width: 510px;
        flex-direction: column;
        justify-content: space-evenly;
    }

    .header-logo {
        align-self: center;
    }

    .header-nav {
        align-self: center;
        border-top: #c3d1c6 1px solid;
        padding-top: 10px;
    }

    .header-title {
        font-style: normal;
        font-weight: 700;
        font-size: 20px;
        line-height: 23px;
    }

    .header-nav span {
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
    }
}

@media (max-width: 320px) {
    .header {
        max-width: 290px;
    }

    .logo {

    }

    .nav {

    }

    .title {

    }

    .header-nav span {

    }
}
</style>
