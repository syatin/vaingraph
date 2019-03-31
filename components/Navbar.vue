<template>
  <nav
    class="vaingraph-navbar navbar navbar-expand-md navbar-dark bg-dark fixed-top"
  >
    <div class="container" sytle="position:relative;">
      <a class="vaingraph-logo navbar-brand" href="index.html">VAINGRAPH</a>
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
            <a class="nav-link active" href="ranking.html"
              ><i class="vg-vain-crystal"></i>&nbsp;ランキング</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="herolist.html"
              ><i class="vg-heroes"></i>&nbsp;ヒーロー</a
            >
          </li>
          <li class="nav-item dropdown">
            <a
              id="dropdown"
              class="nav-link dropdown-toggle"
              href="#"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              ><i class="vg-academy-2"></i>&nbsp;その他</a
            >
            <div class="dropdown-menu" aria-labelledby="dropdown">
              <a class="dropdown-item" href="#">その他の統計</a>
              <a class="dropdown-item" href="about.html">このサイトについて</a>
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
