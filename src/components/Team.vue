<template>
    <div class="team">
        <div class="image">
            <img class="i1" src="../../src/assets/frame.png" alt="">
            <img class="i2" src="../../src/assets/arm.png" alt="">
        </div>
        <div class="content">
            <span class="t1">Наша команда</span>
            <p class="t2">Значимость этих проблем настолько очевидна, что базовый вектор развития позволяет оценить
                значение
                экспериментов, поражающих по своей масштабности и грандиозности. Мы вынуждены отталкиваться от того, что
                консультация с широким активом.</p>
            <div class="people">
                <img src="../../src/assets/team-1.png" alt="" width="80px" height="80px">
                <img src="../../src/assets/team-2.png" alt="" width="80px" height="80px">
                <img src="../../src/assets/team-3.png" alt="" width="80px" height="80px">
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
.team {
    max-width: 1110px;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 70px;
    display: flex;
    min-height: 440px;
    padding-left: 5vw;
    padding-right: 5vw;
}

.content {
    display: flex;
    flex-direction: column;
    gap: 25px;
    height: fit-content;
    align-self: center;
}

.people {
    display: flex;
    gap: 30px;
}

.image {
    position: relative;
    width: 500px;
    height: 500px;
}

.i1 {
    position: absolute;
    height: 361px;
    width: 445px;
    left: 0px;
    top: 100px;

}

.i2 {
    position: absolute;
    width: 269px;
    height: 397px;
    left: 45px;
    top: 30px;
}

.t1 {
    max-width: 281px;
    max-height: 44px;
    font-weight: 500;
    font-size: 40px;
    line-height: 110%;
    color: #2C2D35;
}

.t2 {
    max-width: 635px;
    max-height: 108px;
    font-weight: 500;
    font-size: 18px;
    line-height: 150%;
    color: #2C2D35;
}

@media (max-width: 1200px) {
    .team {
        flex-direction: column;
    }

    .content {
        align-self: flex-start;
        width: 100%;

    }

    .t2 {
        max-width: none;
        max-height: none;
    }
}

@media (max-width: 600px) {
    .image {
        width: 290;
        height: 400px;
    }
    .i1 {
        height: 234.65px;
        width: 290px;
    }

    .i2 {
        width: 175.3px;
        height: 258.05px;
        top: 45px;
        left: 30px;
    }
}
</style>
