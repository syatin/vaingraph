<template>
  <main class="page-container" role="main">
    <div class="container">
      <div class="eyecatch well shadow-sm">
        <h1 class="display-4">Hello, world!</h1>
        <p class="lead">サイトの目的とか簡潔に書く</p>
      </div>
    </div>

    <div class="container">
      <hr />
      <h5>勝率 Top10</h5>
      <p>
        条件：5v5、全地域、Tier9以上、200試合以上<br />
        <nuxt-link class="btn btn-sm btn-info shadow-sm" to="ranking.html"
          >ヒーローランキング</nuxt-link
        >
        で詳細な比較が出来ます。
      </p>
      <table
        class="table table-sm table-striped table-hover table-bordered"
        style="background:#fff;"
      >
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">ヒーロー</th>
            <th scope="col">ポジション</th>
            <th scope="col">ビルド</th>
            <th scope="col">勝率</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/celeste.png"
                  alt="celeste"
                />
                セレス</nuxt-link
              >
            </td>
            <td>Mid</td>
            <td>CP</td>
            <td>40%</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/ardan.png"
                  alt="ardan"
                />
                アーダン</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/ozo.png"
                  alt="ozo"
                />
                オゾ</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">4</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/baptiste.png"
                  alt="baptiste"
                />
                バティスト</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">5</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/petal.png"
                  alt="petal"
                />
                ペタル</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">6</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/flicker.png"
                  alt="flicker"
                />
                フリッカー</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">7</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">8</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">9</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">10</th>
            <td>
              <nuxt-link to="/hero"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</nuxt-link
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
        </tbody>
      </table>

      <hr />

      <h5>ピック率</h5>
      <p>※ 5v5ランク、全地域</p>
      <table class="table table-sm table-striped table-hover table-bordered">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">ヒーロー</th>
            <th scope="col">ピック率</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td><nuxt-link to="/hero">セレス</nuxt-link></td>
            <td>40%</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td><nuxt-link to="/hero">アーダン</nuxt-link></td>
            <td>35%</td>
          </tr>
        </tbody>
      </table>
    </div>
  </main>
</template>
