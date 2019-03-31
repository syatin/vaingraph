<template>
  <main class="page-container" role="main">
    <div class="page-header">
      <div class="page-header-content container">
        <h1>Hero Ranking</h1>
        <p class="page-header-sub">条件で絞り込んでヒーローを比較</p>
      </div>
      <div class="fog"></div>
    </div>

    <div class="hero-filter">
      <div class="container">
        <form>
          <div class="form-row">
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
                <option value="9" selected>9 以上</option>
                <option value="8">8 以上</option>
                <option value="7">7 以上</option>
                <option value="6">6 以上</option>
                <option value="5">5 以上</option>
                <option value="4">4 以上</option>
              </select>
            </div>
            <div class="col">
              <select class="form-control" name="region">
                <option value="all">全地域</option>
                <option value="cn">CN</option>
                <option value="ea">EA</option>
                <option value="eu">EU</option>
                <option value="na">NA</option>
                <option value="sg">SEA</option>
              </select>
            </div>

            <div class="col-3">
              <select class="form-control" name="position">
                <option value="100">100試合以上</option>
                <option value="200" selected>200試合以上</option>
                <option value="500">500試合以上</option>
                <option value="1000">1000試合以上</option>
                <option value="2000">2000試合以上</option>
              </select>
            </div>
          </div>
        </form>
      </div>
    </div>

    <div class="container">
      <div class="hero-stat-menu btn-group" role="group">
        <button type="button" class="btn btn-light w-25">
          <i class="vg-captain"></i
          ><span class="d-none d-lg-inline"> キャプテン</span>
        </button>
        <button type="button" class="btn btn-light w-25">
          <i class="vg-jungler"></i
          ><span class="d-none d-lg-inline"> ジャングル</span>
        </button>
        <button type="button" class="btn btn-light w-25">
          <i class="vg-top-lane"></i
          ><span class="d-none d-lg-inline"> Top</span>
        </button>
        <button type="button" class="btn btn-primary w-25">
          <i class="vg-mid-lane"></i
          ><span class="d-none d-lg-inline"> Mid</span>
        </button>
        <button type="button" class="btn btn-light w-25">
          <i class="vg-bot-lane"></i
          ><span class="d-none d-lg-inline"> Bot</span>
        </button>
      </div>
    </div>

    <div class="container">
      <h3><i class="vg-mid-lane"></i> Midレーン</h3>
      <div class="table-responsive">
        <table class="table table-sm table-striped table-hover table-bordered">
          <thead>
            <tr>
              <th scope="col" rowspan="2">#</th>
              <th scope="col" rowspan="2" style="min-width:140px;">
                ヒーロー
              </th>
              <th scope="col" rowspan="2" style="min-width:60px;">ビルド</th>
              <th scope="col" rowspan="2" style="min-width:70px;">
                ピック率
              </th>
              <th scope="col" rowspan="2" style="min-width:70px;">勝率</th>
              <th class="text-center" scope="col" colspan="5">
                試合時間別の勝率
              </th>
            </tr>
            <tr>
              <th scope="col" style="min-width:60px;">〜15分</th>
              <th scope="col" style="min-width:60px;">15〜20分</th>
              <th scope="col" style="min-width:60px;">20〜25分</th>
              <th scope="col" style="min-width:60px;">25〜30分</th>
              <th scope="col" style="min-width:60px;">30分〜</th>
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
              <td>CP</td>
              <td>64.8 %</td>
              <td>57.0 %</td>
              <td>54%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">2</th>
              <td>
                <nuxt-link to="/hero"
                  ><img
                    class="hero-icon-sm rounded-circle border"
                    src="~/assets/img/heroes/magnus.png"
                    alt="magnus"
                  />
                  マグナス</nuxt-link
                >
              </td>
              <td>CP</td>
              <td>13.2 %</td>
              <td>54.9 %</td>
              <td>54%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">3</th>
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
              <td>CP</td>
              <td>39.0 %</td>
              <td>54.2 %</td>
              <td>54%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">4</th>
              <td>
                <nuxt-link to="/hero"
                  ><img
                    class="hero-icon-sm rounded-circle border"
                    src="~/assets/img/heroes/ringo.png"
                    alt="ringo"
                  />
                  リンゴ</nuxt-link
                >
              </td>
              <td>CP</td>
              <td>4.2 %</td>
              <td>51.4 %</td>
              <td>54%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">5</th>
              <td>
                <nuxt-link to="/hero"
                  ><img
                    class="hero-icon-sm rounded-circle border"
                    src="~/assets/img/heroes/varya.png"
                    alt="varya"
                  />
                  ヴァーリア</nuxt-link
                >
              </td>
              <td>CP</td>
              <td>16.4 %</td>
              <td>51.2 %</td>
              <td>54%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">6</th>
              <td>
                <nuxt-link to="/hero"
                  ><img
                    class="hero-icon-sm rounded-circle border"
                    src="~/assets/img/heroes/malene.png"
                    alt="malene"
                  />
                  マレン</nuxt-link
                >
              </td>
              <td>CP</td>
              <td>9.2 %</td>
              <td>50.2 %</td>
              <td>54%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">7</th>
              <td>
                <nuxt-link to="/hero"
                  ><img
                    class="hero-icon-sm rounded-circle border"
                    src="~/assets/img/heroes/samuel.png"
                    alt="samuel"
                  />
                  サムエル</nuxt-link
                >
              </td>
              <td>CP</td>
              <td>14.8 %</td>
              <td>47.7 %</td>
              <td>35%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">8</th>
              <td>
                <nuxt-link to="/hero"
                  ><img
                    class="hero-icon-sm rounded-circle border"
                    src="~/assets/img/heroes/vox.png"
                    alt="vox"
                  />
                  ヴォックス</nuxt-link
                >
              </td>
              <td>CP</td>
              <td>16.4 %</td>
              <td>43.5 %</td>
              <td>35%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
            <tr>
              <th scope="row">9</th>
              <td>
                <nuxt-link to="/hero"
                  ><img
                    class="hero-icon-sm rounded-circle border"
                    src="~/assets/img/heroes/skye.png"
                    alt="skye"
                  />
                  スカイ</nuxt-link
                >
              </td>
              <td>CP</td>
              <td>4.0 %</td>
              <td>42.1 %</td>
              <td>45%</td>
              <td>58%</td>
              <td>56%</td>
              <td>53%</td>
              <td>50%</td>
            </tr>
          </tbody>
        </table>
      </div>
      <p class="alert alert-secondary">
        ピック率が低いヒーローは勝率が偏っている可能性があります。<br />特に試合時間別の勝率はデータ数が不足しがちです。
      </p>
    </div>
  </main>
</template>
