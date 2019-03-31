<template>
  <main class="page-container" role="main">
    <div class="page-header">
      <div class="page-header-content container gamemode-5v5">
        <img
          class="page-header-icon rounded-circle border"
          src="~/assets/img/heroes/anka.png"
          alt="Anka"
        />
        <h1>Anka</h1>
        <p class="page-header-sub">
          <i class="vg-jungler"></i> Jungle / <i class="vg-top-lane"></i> Top
        </p>
      </div>
      <div class="fog"></div>
      <!-- 画像加工が面倒なのでダミー -->
    </div>

    <div class="hero-filter">
      <div class="container">
        <form>
          <div class="form-row">
            <div class="col-3">
              <select class="form-control" name="hero">
                <!-- TODO ここの選択肢の一覧を取れるAPI作る -->
                <option value="Adagio">アダージオ</option>
                <option value="Alpha">アルファ</option>
                <option value="Anka" selected>アンカ</option>
                <option value="Ardan">アーダン</option>
                <option value="Bptiste">バティスト</option>
              </select>
            </div>
            <div class="col">
              <select class="form-control" name="gamemode">
                <option value="5v5">5v5</option>
                <option value="3v3">3v3</option>
              </select>
            </div>
            <div class="col">
              <select class="form-control" name="rank">
                <option value="">ランク</option>
                <option value="10">10</option>
                <option value="9">9</option>
                <option value="8">8</option>
                <option value="7">7</option>
                <option value="6">6</option>
                <option value="5">5</option>
                <option value="4">4</option>
              </select>
            </div>
            <div class="col">
              <select class="form-control" name="region">
                <option value="">地域</option>
                <option value="cn">CN</option>
                <option value="ea">EA</option>
                <option value="eu">EU</option>
                <option value="na">NA</option>
                <option value="sg">SEA</option>
              </select>
            </div>
          </div>
        </form>
      </div>
    </div>

    <div class="container">
      <div class="hero-stat-menu btn-group" role="group">
        <button type="button" class="btn btn-primary w-25">概要</button>
        <button type="button" class="btn btn-light w-25">勝率</button>
        <button type="button" class="btn btn-light w-25">ビルド</button>
        <button type="button" class="btn btn-light w-25">相性</button>
      </div>
    </div>

    <div class="container">
      <div class="hero-stat-content">
        <div class="d-flex">
          <div class="card w-50">
            <div class="card-body">
              <h5 class="card-title">勝率</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
          <div class="card w-50">
            <div class="card-body">
              <h5 class="card-title">バンピック率</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
        </div>

        <div class="d-flex">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">勝率履歴</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
        </div>

        <div class="d-flex">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">ピック率履歴</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
