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
        <a class="btn btn-sm btn-info shadow-sm" href="ranking.html"
          >ヒーローランキング</a
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
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/celeste.png"
                  alt="celeste"
                />
                セレス</a
              >
            </td>
            <td>Mid</td>
            <td>CP</td>
            <td>40%</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/ardan.png"
                  alt="ardan"
                />
                アーダン</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/ozo.png"
                  alt="ozo"
                />
                オゾ</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">4</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/baptiste.png"
                  alt="baptiste"
                />
                バティスト</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">5</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/petal.png"
                  alt="petal"
                />
                ペタル</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">6</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/flicker.png"
                  alt="flicker"
                />
                フリッカー</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">7</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">8</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">9</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</a
              >
            </td>
            <td>Captain</td>
            <td>実用</td>
            <td>35%</td>
          </tr>
          <tr>
            <th scope="row">10</th>
            <td>
              <a href="hero.html"
                ><img
                  class="hero-icon-sm rounded-circle border"
                  src="~/assets/img/heroes/skaarf.png"
                  alt="skaarf"
                />
                スカーフ</a
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
            <td><a href="hero.html">セレス</a></td>
            <td>40%</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td><a href="hero.html">アーダン</a></td>
            <td>35%</td>
          </tr>
        </tbody>
      </table>
    </div>
  </main>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
