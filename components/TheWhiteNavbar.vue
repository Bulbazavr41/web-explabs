<template>
<div>
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
</div>
</template>

<script>
export default {}
</script>

<style lang="scss">
$dark: #242424;
.navbar {
  .navbar-brand {
    font-family: 'Exo 2', 'Exo', sans-serif;
    font-size: 2.25rem;
  }
}
</style>