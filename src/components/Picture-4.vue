<template>
    <div class="card">
        <img src="../../src/assets/picture-4.png" alt="">
        <span class="t1">Луи Детуш</span>
        <span class="t2">Роза</span>
        <span class="t3">Бумага, акрил (50х80)</span>
        <span class="t4">12 000 руб</span>
        <button>В корзину</button>
    </div>
</template>

<script>

</script>

<style scoped>
.card {
    width: 310px;
    height: 690px;
    background: #E1EDE6;
    padding: 20px;

    display: flex;
    flex-direction: column;
}

.t1 {
    font-weight: 500;
    font-size: 18px;
    line-height: 21px;
    color: #86928B;
    margin-top: 20px;
}

.t2 {
    font-weight: 500;
    font-size: 30px;
    line-height: 35px;
    color: #2C2D35;
    margin-top: 10px;
}

.t3 {
    font-weight: 500;
    font-size: 18px;
    line-height: 21px;
    color: #2C2D35;
    margin-top: 5px;
}

.t4 {
    font-weight: 500;
    font-size: 24px;
    line-height: 28px;
    color: #598D66;
    margin-top: 40px;
}

button {
    background-color: #e1ede6;
    box-sizing: border-box;

    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 20px 60px;
    gap: 6px;
    border: 1px solid #598D66;

    font-weight: 500;
    font-size: 20px;
    line-height: 23px;
    color: #598D66;

    margin-top: 15px;
}

@media (max-width: 1250px) {
    .card {
        width: 290px;
        height: 690px;
    }
}

@media (max-width: 766px) {
    .card {
        width: 200px;
        height: 474px;
    }

    .t1 {
        font-weight: 500;
        font-size: 16px;
        line-height: 19px;
    }

    .t2 {
        font-weight: 500;
        font-size: 24px;
        line-height: 28px;
    }

    .t3 {
        font-weight: 500;
        font-size: 16px;
        line-height: 19px;
    }

    .t4 {
        font-weight: 500;
        font-size: 20px;
        line-height: 23px;
    }

    button {
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
        text-wrap: nowrap;
        height: 21px;
    }

    img {
        width: 200px;
        height: 250px;
    }
}

@media (max-width: 567px) {
    .card {
        width: 290px;
        height: 474px;
    }

    img {
        width: 250px;
        height: 250px;
    }

    button {
        height: 21px;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
    }
}

@media (max-width: 320px) {}
</style>