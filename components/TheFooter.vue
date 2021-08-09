<template>
    <footer class="footer" id="footer">
        <div class="footer__upper">
            <div class="container">
                <div class="row">
                    <div class="col col-12 d-flex justify-content-between flex-wrap">
                        <div class="footer__logo">
                            <div class="logo"><span class="logo__bold">Exp</span>Labs</div>
                        </div>
                        <div class="footer__links ml-md-auto">
                            <div class="footer__phone">
                                <a href="mailto:contact@explabs.ru">contact@explabs.ru</a>
                            </div>
                            <div class="footer__address">
                                <a href="https://vk.com/explabs">ВКонтакте</a>
                                <a href="https://instagram.com/exp.labs">Instagram</a>
                            </div>
                        </div>
                        <div class="footer__contact">
                            <a href="#" class="btn btn-primary">Связаться с нами</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer__middle">
            <div class="container">
                <nav class="footer-nav">
                    <ul class="footer-nav__menu">
                        <li>
                            <nuxt-link :to="{name: 'index'}"> Информация</nuxt-link>
                            <ul class="sub-menu">
                                <li><nuxt-link to="about-us">О нас</nuxt-link></li>
                                <li><a href="#">Контакты</a></li>
                                <li><a href="#">Проекты</a></li>
                                <li><a href="#">Команда</a></li>
                            </ul>
                        <li/>
                        <li>
                            <a href="#">Направления</a>
                            <ul class="sub-menu">
                                <li><nuxt-link to="Web">Веб-разработка</nuxt-link></li>
                                <li><a href="#">Разработка</a></li>
                                <li><nuxt-link to="Robotics">Робототехника</nuxt-link></li>
                                <li><nuxt-link to="Modeling">3D-моделирование</nuxt-link></li>
                            </ul>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
        <div class="footer__down">
            <div class="container">
                <div class="row">
                    <div class="col col-12 col-md-6 footer__copyright">
                        <p>
                            Инжиниринговый Центр Мобильных Решений &copy; 2017-2019
                        </p>
                    </div>
                    <div class="col col-12 col-md-6 footer__developer">
                        <p>
                            Во всех проблемах сайта виноват наш отдел Веб-разработки
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
</style>