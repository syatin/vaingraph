<template>
  <main class="page-container" role="main">
    <div class="page-header">
      <div class="page-header-content container">
        <h1>Vainglory Heroes</h1>
        <p class="page-header-sub">ヒーローを選択して詳細を表示</p>
      </div>
      <div class="fog"></div>
    </div>

    <div class="container">
      <div class="hero-stat-menu btn-group" role="group">
        <button type="button" class="btn btn-primary w-25">全て</button>
        <button type="button" class="btn btn-light w-25">
          <i class="vg-captain"></i
          ><span class="d-none d-md-inline"> キャプテン</span>
        </button>
        <button type="button" class="btn btn-light w-25">
          <i class="vg-jungler"></i
          ><span class="d-none d-md-inline"> ジャングル</span>
        </button>
        <button type="button" class="btn btn-light w-25">
          <i class="vg-carry"></i
          ><span class="d-none d-md-inline"> キャリー</span>
        </button>
      </div>
    </div>

    <div class="container">
      <div
        class="hero-list-content d-flex justify-content-center align-content-around flex-wrap"
      >
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/adagio.png"
            alt="Adagio"
          />
          アダージオ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/alpha.png"
            alt="alpha"
          />
          アルファ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/anka.png"
            alt="Anka"
          />
          アンカ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ardan.png"
            alt="ardan"
          />
          アーダン
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/baptiste.png"
            alt="baptiste"
          />
          バティスト
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/baron.png"
            alt="baron"
          />
          バロン
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/blackfeather.png"
            alt="blackfeather"
          />
          ブラックフェザー
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/catherine.png"
            alt="catherine"
          />
          キャサリン
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/celeste.png"
            alt="celeste"
          />
          セレス
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/churnwalker.png"
            alt="churnwalker"
          />
          チャーンウォーカー
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/flicker.png"
            alt="flicker"
          />
          フリッカー
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/fortress.png"
            alt="fortress"
          />
          フォートレス
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/glaive.png"
            alt="glaive"
          />
          グレイヴ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/grace.png"
            alt="grace"
          />
          グレース
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/grumpjaw.png"
            alt="grumpjaw"
          />
          グランプジョー
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/gwen.png"
            alt="gwen"
          />
          グウェン
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/idris.png"
            alt="idris"
          />
          イドリス
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/inara.png"
            alt="inara"
          />
          イナラ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/joule.png"
            alt="joule"
          />
          ジュール
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/kensei.png"
            alt="kensei"
          />
          剣聖
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/kestrel.png"
            alt="kestrel"
          />
          ケストレル
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/kinetic.png"
            alt="kinetic"
          />
          キネティック
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/koshka.png"
            alt="koshka"
          />
          コシュカ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/krul.png"
            alt="krul"
          />
          クラル
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/lance.png"
            alt="lance"
          />
          ランス
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/lorelai.png"
            alt="lorelai"
          />
          ローレライ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/lyra.png"
            alt="lyra"
          />
          ライラ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/magnus.png"
            alt="magnus"
          />
          マグナス
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/malene.png"
            alt="malene"
          />
          マレン
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ozo.png"
            alt="ozo"
          />
          オゾ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/petal.png"
            alt="petal"
          />
          ペタル
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/phinn.png"
            alt="phinn"
          />
          フィン
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/reim.png"
            alt="reim"
          />
          ライム
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/reza.png"
            alt="reza"
          />
          レザ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ringo.png"
            alt="ringo"
          />
          リンゴ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/rona.png"
            alt="rona"
          />
          ロナ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/samuel.png"
            alt="samuel"
          />
          サムエル
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/sanfeng.png"
            alt="sanfeng"
          />
          サンポウ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/saw.png"
            alt="saw"
          />
          SAW
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/silvernail.png"
            alt="silvernail"
          />
          シルバーネイル
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/skaarf.png"
            alt="skaarf"
          />
          スカーフ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/skye.png"
            alt="skye"
          />
          スカイ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/taka.png"
            alt="taka"
          />
          タカ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/tony.png"
            alt="tony"
          />
          トニー
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/varya.png"
            alt="varya"
          />
          ヴァーリア
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/vox.png"
            alt="vox"
          />
          ヴォックス
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/yates.png"
            alt="yates"
          />
          イェーツ
        </a>
        <a class="card p-2  shadow-sm" href="hero.html">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ylva.png"
            alt="ylva"
          />
          イルバ
        </a>
      </div>
    </div>
  </main>
</template>
