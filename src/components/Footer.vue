<template>
    <div class="container">
        <div class="footer">
            <div class="left">
                <div class="footer-logo">
                    <img src="../../src/assets/house-logo.png" alt="Header logo" width="35px">
                    <span class="header-title">Ink. House</span>
                </div>
                <div class="footer-contact">
                    <span>+7 (999) 543-54-54</span><br>
                    <span>Мастерская</span>
                </div>
            </div>
            <div class="footer-nav">
                <div class="reprod-nav">
                    <span>Репродукции</span>
                    <span>Франция</span>
                    <span>Германия</span>
                    <span>Англия</span>
                </div>
                <div class="new-nav">
                    <span>Новинки</span>
                    <span>2021</span>
                    <span>2020</span>
                </div>
                <div class="about-nav">
                    <span>О нас</span>
                    <span>Художники</span>
                    <span>Менеджеры</span>
                </div>
            </div>
            <div class="right">
                <div class="social-links">
                    <img src="../../src/assets/fb.png" alt="Facebook logo">
                    <img src="../../src/assets/ig.png" alt="Instagram logo">
                    <img src="../../src/assets/yt.png" alt="Youtube logo">
                </div>
                <div class="footer-rights">
                    <span>Ink. House ®</span><br>
                    <span>All rights reserved</span>
                </div>
            </div>
        </div>
    </div>

</template>

<style>
.footer {
    max-width: 1110px;
    height: 168px;
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

.left, .right {
    margin-top: 23px;
}

.footer-contact {
    margin-top: 35px;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 23px;
    color: #2C2D35;
}

.footer-contact span:last-child {
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 23px;
    color: #86928B;
}

.footer-logo {
    display: flex;
    align-items: center;
}

.footer-logo img {
    margin-right: 8px;
}

.footer-title {
    font-style: normal;
    font-weight: 700;
    font-size: 20px;
    line-height: 23px;
    color: #598D66;
}

.footer-nav {
    margin-top: 23px;
    display: flex;
    gap: 50px
}

.footer-nav span {
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 23px;
    color: #86928B;
}

.footer-nav span:first-child {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 23px;
    color: #2C2D35;
}

.reprod-nav {
    display: flex;
    flex-direction: column;
    gap: 6px;
}

.new-nav {
    display: flex;
    flex-direction: column;
    gap: 6px;
}

.about-nav {
    display: flex;
    flex-direction: column;
    gap: 6px;
}

.social-links {
    display: flex;
    gap: 30px;
}

.footer-rights {
    margin-top: 10px;
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 23px;
    color: #86928B;
}

@media (max-width: 768px) {
    .footer {
        max-width: 690px;

    }

    .footer-title {
        font-style: normal;
        font-weight: 700;
        font-size: 20px;
        line-height: 23px;
    }

    .footer-nav span {
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
    }
}

@media (max-width: 576px) {
    .footer {
        max-width: 510px;
        flex-direction: column;
        justify-content: space-evenly;
    }

    .footer-logo {
        align-self: center;
    }

    .footer-nav {
        align-self: center;
        border-top: #c3d1c6 1px solid;
        padding-top: 10px;
    }

    .footer-title {
        font-style: normal;
        font-weight: 700;
        font-size: 20px;
        line-height: 23px;
    }

    .footer-nav span {
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
    }
}

@media (max-width: 320px) {
    .footer {
        max-width: 290px;
    }

    .footer-logo {

    }

    .footer-nav {

    }

    .footer-title {

    }

    .footer-nav span {

    }
}
</style>
