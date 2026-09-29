<div align="center">

# raku1chi

仕事では Python を中心に、主にバックエンドの開発をしています。<br>
個人開発では、公的データやオープンデータ、好きなものを題材に、<br>
「調べる・比べる・眺める」が気持ちよくできる Web サービスを作っています。<br>
データを集めるところから、設計・API・画面・公開後の運用まで、一通り手を動かすのが好きです。

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

[raku1chi.dev](https://raku1chi.dev) ・ [X](https://x.com/raku1chi)

</div>

<br>

## Works

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://kaisha-rirekisho.raku1chi.dev/">
        <img src="assets/kaisha-rirekisho.png" alt="会社の履歴書のスクリーンショット" />
      </a>
    </td>
    <td width="50%" valign="top">
      <a href="https://chikaba.raku1chi.dev/">
        <img src="assets/chikaba.png" alt="ちかばのスクリーンショット" />
      </a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3><a href="https://kaisha-rirekisho.raku1chi.dev/">会社の履歴書</a></h3>
      <p>口コミではなく公的データで、その会社で長く働けるかを確かめる転職者向けの企業データサイト。残業・休暇、定着、育児との両立、収入、会社の安定と成長の 6 つの軸で、同じ業種・規模の会社と比べた位置を出典付きで示します。</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white" alt="Hono" />
        <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" />
      </p>
      <p><sub>EDINET・厚生労働省・国税庁のオープンデータを法人番号で突き合わせ、Python と DuckDB のパイプラインで指標を算出。生成したデータを R2 に置き、Cloudflare Workers 上の Hono でサーバーサイドレンダリングしています。</sub></p>
    </td>
    <td valign="top">
      <h3><a href="https://chikaba.raku1chi.dev/">ちかば</a></h3>
      <p>時間から近場のおでかけ先を探す検索サービス。駅・現在地・地図の好きな場所から、電車・バス・徒歩・自転車で◯分以内に行ける観光地・寺社・グルメと街の飲食店を、到達範囲の地図と件数を見ながら絞り込めます。</p>
      <p>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
        <img src="https://img.shields.io/badge/MapLibre-396CB2?style=flat-square&logo=maplibre&logoColor=white" alt="MapLibre" />
        <img src="https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3&logoColor=white" alt="D3.js" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" />
      </p>
      <p><sub>OpenStreetMap・Wikipedia・GTFS-JP などのオープンデータから、Python で全国の路線・スポット・飲食店のデータを生成。RAPTOR 方式の経路探索をブラウザ内に実装し、全国どこからでも数十ミリ秒で到達範囲を計算しています。</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://washi-hero.pages.dev/">
        <img src="assets/washi-hero.png" alt="ヒーロー予想攻略のスクリーンショット" />
      </a>
    </td>
    <td width="50%" valign="top">
      <a href="https://artmuseums.pages.dev/">
        <img src="assets/artmuseums.png" alt="ただ一枚のスクリーンショット" />
      </a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3><a href="https://washi-hero.pages.dev/">ヒーロー予想攻略</a></h3>
      <p>楽天イーグルスの出場パターンをタイムラインで可視化し、イーグルストレカの「ヒーロー予想」をサポートする非公式ツール。期待値・トレンド・安定・爆発の 4 モードで選手をランキングします。</p>
      <p>
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 19" />
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
        <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflarepages&logoColor=white" alt="Cloudflare Pages" />
      </p>
      <p><sub>試合データは GitHub Actions で毎日自動更新。ビルド時に静的 JSON へ落とし込み、サーバーレスで配信しています。</sub></p>
    </td>
    <td valign="top">
      <h3><a href="https://artmuseums.pages.dev/">ただ一枚</a></h3>
      <p>国立美術館 5 館が公開するパブリックドメイン作品を、一点ずつ静かに鑑賞するためのページ。余計な情報を削ぎ落とし、作品と向き合う時間をつくります。</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
        <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflarepages&logoColor=white" alt="Cloudflare Pages" />
      </p>
      <p><sub>所蔵作品総合目録から Python でデータを収集・整形し、軽量な静的サイトとして公開しています。</sub></p>
    </td>
  </tr>
</table>

<br>

## Stack

| | |
|:--|:--|
| **Backend / Data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) |
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=flat-square&logo=maplibre&logoColor=white) |
| **Infra / Ops** | ![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white) ![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflarepages&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **Testing / Tooling** | ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black) ![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![Biome](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=white) |

