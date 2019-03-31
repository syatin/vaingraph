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
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/adagio.png"
            alt="Adagio"
          />
          アダージオ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/alpha.png"
            alt="alpha"
          />
          アルファ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/anka.png"
            alt="Anka"
          />
          アンカ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ardan.png"
            alt="ardan"
          />
          アーダン
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/baptiste.png"
            alt="baptiste"
          />
          バティスト
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/baron.png"
            alt="baron"
          />
          バロン
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/blackfeather.png"
            alt="blackfeather"
          />
          ブラックフェザー
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/catherine.png"
            alt="catherine"
          />
          キャサリン
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/celeste.png"
            alt="celeste"
          />
          セレス
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/churnwalker.png"
            alt="churnwalker"
          />
          チャーンウォーカー
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/flicker.png"
            alt="flicker"
          />
          フリッカー
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/fortress.png"
            alt="fortress"
          />
          フォートレス
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/glaive.png"
            alt="glaive"
          />
          グレイヴ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/grace.png"
            alt="grace"
          />
          グレース
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/grumpjaw.png"
            alt="grumpjaw"
          />
          グランプジョー
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/gwen.png"
            alt="gwen"
          />
          グウェン
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/idris.png"
            alt="idris"
          />
          イドリス
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/inara.png"
            alt="inara"
          />
          イナラ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/joule.png"
            alt="joule"
          />
          ジュール
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/kensei.png"
            alt="kensei"
          />
          剣聖
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/kestrel.png"
            alt="kestrel"
          />
          ケストレル
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/kinetic.png"
            alt="kinetic"
          />
          キネティック
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/koshka.png"
            alt="koshka"
          />
          コシュカ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/krul.png"
            alt="krul"
          />
          クラル
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/lance.png"
            alt="lance"
          />
          ランス
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/lorelai.png"
            alt="lorelai"
          />
          ローレライ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/lyra.png"
            alt="lyra"
          />
          ライラ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/magnus.png"
            alt="magnus"
          />
          マグナス
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/malene.png"
            alt="malene"
          />
          マレン
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ozo.png"
            alt="ozo"
          />
          オゾ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/petal.png"
            alt="petal"
          />
          ペタル
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/phinn.png"
            alt="phinn"
          />
          フィン
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/reim.png"
            alt="reim"
          />
          ライム
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/reza.png"
            alt="reza"
          />
          レザ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ringo.png"
            alt="ringo"
          />
          リンゴ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/rona.png"
            alt="rona"
          />
          ロナ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/samuel.png"
            alt="samuel"
          />
          サムエル
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/sanfeng.png"
            alt="sanfeng"
          />
          サンポウ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/saw.png"
            alt="saw"
          />
          SAW
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/silvernail.png"
            alt="silvernail"
          />
          シルバーネイル
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/skaarf.png"
            alt="skaarf"
          />
          スカーフ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/skye.png"
            alt="skye"
          />
          スカイ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/taka.png"
            alt="taka"
          />
          タカ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/tony.png"
            alt="tony"
          />
          トニー
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/varya.png"
            alt="varya"
          />
          ヴァーリア
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/vox.png"
            alt="vox"
          />
          ヴォックス
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/yates.png"
            alt="yates"
          />
          イェーツ
        </nuxt-link>
        <nuxt-link class="card p-2  shadow-sm" to="/hero">
          <img
            class="hero-icon rounded-circle border"
            src="~/assets/img/heroes/ylva.png"
            alt="ylva"
          />
          イルバ
        </nuxt-link>
      </div>
    </div>
  </main>
</template>
