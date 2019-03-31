<template>
  <nav
    class="vaingraph-navbar navbar navbar-expand-md navbar-dark bg-dark fixed-top"
  >
    <div class="container" sytle="position:relative;">
      <nuxt-link class="vaingraph-logo navbar-brand" to="/"
        >VAINGRAPH</nuxt-link
      >
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#globalMenu"
        aria-controls="globalMenu"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div id="globalMenu" class="collapse navbar-collapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <nuxt-link class="nav-link active" to="/ranking"
              ><i class="vg-vain-crystal"></i>&nbsp;ランキング</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/herolist"
              ><i class="vg-heroes"></i>&nbsp;ヒーロー</nuxt-link
            >
          </li>
          <li class="nav-item dropdown">
            <nuxt-link
              id="dropdown"
              class="nav-link dropdown-toggle"
              to="/"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              ><i class="vg-academy-2"></i>&nbsp;その他</nuxt-link
            >
            <div class="dropdown-menu" aria-labelledby="dropdown">
              <nuxt-link class="dropdown-item" to="/">その他の統計</nuxt-link>
              <nuxt-link class="dropdown-item" to="about"
                >このサイトについて</nuxt-link
              >
            </div>
          </li>
        </ul>
      </div>

      <div class="language-select-wrapper">
        <div class="language-select">
          <img src="~/assets/img/lang-ja.gif" alt="日本語" />
        </div>
      </div>
    </div>
  </nav>
</template>
