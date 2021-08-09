<template>
<div class="wrap">
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <a class="navbar-brand" href="/"><span class="font-weight-bold">Exp</span>Labs</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="#navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <ul class="navbar-nav ml-auto smooth-scroll">
                    <li class="nav-item">
                    <a data-scroll="" class="nav-link"><nuxt-link to="#">Проекты</nuxt-link></a>
                    </li>
                    <li class="nav-item">
                    <a data-scroll="" class="nav-link"><nuxt-link to="#">Новости</nuxt-link></a>
                    </li>
                    <li class="nav-item">
                    <a data-scroll="" class="nav-link"><nuxt-link to="KNX">KNX</nuxt-link></a>
                    </li>
                    <li class="nav-item">
                    <a data-scroll="" class="nav-link"><nuxt-link to="about-us">Об ИЦМР</nuxt-link></a>
                    </li>
                    <li class="nav-item">
                    <a data-scroll="" class="nav-link"><nuxt-link to="#">Сотрудники</nuxt-link></a>
                    </li>
                </ul>
            </div>
            </div>
        </nav>
        <section class="page-header page-header--light">
            <div class="container">
                <div class="row">
                    <div class="col-12 col-lg-10">
                        <h1>Тренинг центр KNX</h1>
                        <p class="lead">
                        На базе РТУ МИРЭА в Инжинириговом Центре Мобильных Решений создан сертифицированный тренинг центр KNX.
                        </p>
                <nav aria-label="breadcrumb">
                    <ol class="breadcrumb">
                        <li class="breadcrumb-item" aria-current="page"><a href="/index.html">Главная</a></li>
                        <li class="breadcrumb-item active" aria-current="page">Тренинг центр KNX</li>
                    </ol>
                </nav>
                </div>
                    <div class="col-12 col-lg-3 ml-lg-auto">
                    <img class="illustration illustration--offcanvas" src="~assets/img/illustrations/presentation.svg" alt="presentation">
                    </div>
                </div>
            </div>
        </section>
    </header>

        <section class="section section--light benefits">
            <div class="container">
            <div class="row section__heading">
                <div class="col-12">
                    <h1>Что дает этот курс</h1>
                </div>
            </div>

            <div class="row">
                <div class="col-12 col-lg-4">
                <div class="card card--feature">
                    <div class="card-body">
                        <div class="card__heading">
                        <h5 class="card-title">Персональный сертификат&nbsp;«KNX&nbsp;Partner»</h5>
                        <img class="card__icon" src="~assets/img/icons/icons8-certificate-100.png" alt="certificate">
                        </div>
                            <p class="card-text">
                            Позволяет выполнять работы по установке и пуско-наладке систем автоматизации KNX на территории
                            Евросоюза
                            </p>
                    </div>
                </div>
                </div>
                <div class="col-12 col-sm-6 col-lg-4">
                <div class="card card--feature">
                    <div class="card-body">
                        <div class="card__heading">
                        <h5 class="card-title">Материалы и учебные пособия</h5>
                        <img class="card__icon" src="~assets/img/icons/icons8-opened-folder-100.png" alt="opened-folder">
                        </div>
                            <p class="card-text">
                            Позволяет выполнять работы по установке и пуско-наладке систем автоматизации KNX на территории
                            Eвросоюза
                            </p>
                    </div>
                </div>
                </div>
                <div class="col-12 col-sm-6 col-lg-4">
                <div class="card card--feature">
                    <div class="card-body">
                        <div class="card__heading">
                            <h5 class="card-title">Скидки на программное обеспечение</h5>
                            <img class="card__icon" src="~assets/img/icons/icons8-discount-100.png" alt="discount">
                        </div>
                            <p class="card-text">
                            Позволяет выполнять работы по установке и пуско-наладке систем автоматизации KNX на территории
                            Евросоюза
                            </p>
                    </div>
                </div>
                </div>
            </div>
            </div>
        </section>

        <section class="section section--light program">
            <div class="container">
                <div class="row section__heading">
                    <div class="col-12">
                    <h1>Программа курса</h1>
                    </div>
                </div>

            <div class="row">
                <div class="col-12">
                    <div class="timeline">
                        <div class="timeline__item">
                        <h5>Понедельник</h5>
                            <div class="text">
                            <ul class="list-unstyled">
                                <li>Аргументы в пользу использования технологии KNX</li>
                                <li>Коммуникация в протоколе KNX</li>
                            </ul>
                            </div>
                        </div>
                        <div class="timeline__item">
                        <h5>Вторник</h5>
                            <div class="text">
                            <ul class="list-unstyled">
                                <li>Топология в протоколе KNX</li>
                                <li>Имплементация телеграмм в KNX</li>
                            </ul>
                            </div>
                        </div>
                        <div class="timeline__item">
                        <h5>Среда</h5>
                            <div class="text">
                            <ul class="list-unstyled">
                                <li>Шинные устройства в KNX</li>
                                <li>Задачи инсталляции в KNX</li>
                            </ul>
                            </div>
                        </div>
                        <div class="timeline__item">
                        <h5>Четверг</h5>
                            <div class="text">
                            <ul class="list-unstyled">
                                <li>Особенности Power Line KNX</li>
                                <li>Разработка проекта</li>
                                <li>Повторение пройденного материала</li>
                            </ul>
                            </div>
                        </div>
                        <div class="timeline__item">
                        <h5>Пятница</h5>
                            <div class="text">
                            <ul class="list-unstyled">
                                <li>Экзамен</li>
                            </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            </div>
        </section>
</div>
</template>

<script>

export default 
{
}
</script>

<style lang="scss" scoped>

</style>
