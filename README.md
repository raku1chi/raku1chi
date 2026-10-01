<div align="center">

# raku1chi

<!-- スマホでは 1 行が画面幅を超えると途中で折り返され、その直後の <br> で「す。」だけの行ができてしまうため、1 行を全角 22 文字以内に収めている -->
仕事では Python を中心に、<br>
主にバックエンドの開発をしています。

個人開発では、公的データやオープンデータ、<br>
好きなものを題材に、<br>
「調べる・比べる・眺める」が気持ちよくできる<br>
Web サービスを作っています。

データを集めるところから、<br>
設計・API・画面・公開後の運用まで、<br>
一通り手を動かすのが好きです。

<br>

<!-- アイコンとバッジを <picture> で囲んでいるのは、GitHub が画像に自動で付ける「画像ファイルを開くだけのリンク」を付けないため -->
<p>
  <picture><img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/python/python-original.svg" width="36" height="36" alt="Python" title="Python" /></picture>&nbsp;
  <picture><img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/fastapi/fastapi-original.svg" width="36" height="36" alt="FastAPI" title="FastAPI" /></picture>&nbsp;
  <picture><img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/typescript/typescript-original.svg" width="36" height="36" alt="TypeScript" title="TypeScript" /></picture>&nbsp;
  <picture><img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/react/react-original.svg" width="36" height="36" alt="React" title="React" /></picture>&nbsp;
  <picture><img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/cloudflare/cloudflare-original.svg" width="36" height="36" alt="Cloudflare" title="Cloudflare" /></picture>&nbsp;
  <picture><img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="36" height="36" alt="AWS" title="AWS" /></picture>
</p>

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
        <picture><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></picture>
        <picture><img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB" /></picture>
        <picture><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /></picture>
        <picture><img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white" alt="Hono" /></picture>
        <picture><img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" /></picture>
      </p>
      <p><sub>EDINET・厚生労働省・国税庁のオープンデータを法人番号で突き合わせ、Python と DuckDB のパイプラインで指標を算出。生成したデータを R2 に置き、Cloudflare Workers 上の Hono でサーバーサイドレンダリングしています。</sub></p>
    </td>
    <td valign="top">
      <h3><a href="https://chikaba.raku1chi.dev/">ちかば</a></h3>
      <p>時間から近場のおでかけ先を探す検索サービス。駅・現在地・地図の好きな場所から、電車・バス・徒歩・自転車で◯分以内に行ける観光地・寺社・グルメと街の飲食店を、到達範囲の地図と件数を見ながら絞り込めます。</p>
      <p>
        <picture><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" /></picture>
        <picture><img src="https://img.shields.io/badge/MapLibre-396CB2?style=flat-square&logo=maplibre&logoColor=white" alt="MapLibre" /></picture>
        <picture><img src="https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3&logoColor=white" alt="D3.js" /></picture>
        <picture><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></picture>
        <picture><img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" /></picture>
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
        <picture><img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 19" /></picture>
        <picture><img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" /></picture>
        <picture><img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" /></picture>
        <picture><img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflarepages&logoColor=white" alt="Cloudflare Pages" /></picture>
      </p>
      <p><sub>試合データは GitHub Actions で毎日自動更新。ビルド時に静的 JSON へ落とし込み、サーバーレスで配信しています。</sub></p>
    </td>
    <td valign="top">
      <h3><a href="https://artmuseums.pages.dev/">ただ一枚</a></h3>
      <p>国立美術館 5 館が公開するパブリックドメイン作品を、一点ずつ静かに鑑賞するためのページ。余計な情報を削ぎ落とし、作品と向き合う時間をつくります。</p>
      <p>
        <picture><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></picture>
        <picture><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" /></picture>
        <picture><img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflarepages&logoColor=white" alt="Cloudflare Pages" /></picture>
      </p>
      <p><sub>所蔵作品総合目録から Python でデータを収集・整形し、軽量な静的サイトとして公開しています。</sub></p>
    </td>
  </tr>
</table>

<br>

## Stack

<!-- AWS と Playwright のバッジのロゴは、Devicon（techicons.dev と同じアイコン）の SVG を埋め込んだもの。AWS は文字色を白に変えている（Copyright (c) 2015 konpa, MIT License: https://github.com/devicons/devicon/blob/master/LICENSE） -->

| | |
|:--|:--|
| **Backend / Data** | <picture>![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)</picture> <picture>![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)</picture> <picture>![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)</picture> <picture>![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)</picture> <picture>![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)</picture> <picture>![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)</picture> <picture>![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)</picture> |
| **Frontend** | <picture>![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)</picture> <picture>![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)</picture> <picture>![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)</picture> <picture>![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)</picture> <picture>![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)</picture> <picture>![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=flat-square&logo=maplibre&logoColor=white)</picture> |
| **Infra / Ops** | <picture>![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)</picture> <picture>![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflarepages&logoColor=white)</picture> <picture>![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNyAyNi4xIDEyNi42IDc1LjgiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0zNi40IDUzLjZxMCAyLjQuNCAzLjguNSAxLjUgMS40IDNsLjMgMXEwIC42LS44IDEuM0wzNSA2NC40bC0xIC40cS0uOCAwLTEuMy0uNmwtMS41LTItMS4zLTIuNWExNiAxNiAwIDAgMS0xMi40IDUuOXEtNS40IDAtOC40LTMtMy4yLTMuMS0zLjItOC4yIDAtNS4zIDMuOS04LjYgMy44LTMuMyAxMC4zLTMuM2EzMyAzMyAwIDAgMSA5LjMgMS4ydi0zcTAtNC44LTItNi44VDIwLjUgMzJxLTIuMiAwLTQuNS41TDExLjUgMzRsLTIuMi43cS0uOSAwLS45LTEuNHYtMnEwLTEgLjMtMS41VDEwIDI5cTIuMi0xLjEgNS4zLTEuOXQ2LjYtLjhxNy41IDAgMTEgMy40IDMuNSAzLjUgMy41IDEwLjR2MTMuNlpNMTkuMyA2MHEyIDAgNC4zLS43YTkgOSAwIDAgMCA0LTIuN3ExLTEuMiAxLjUtMi43dC40LTMuN3YtMS43bC0zLjktLjgtNC0uMnEtNC4xIDAtNi4yIDEuN1QxMy4zIDU0cTAgMyAxLjYgNC41IDEuNCAxLjUgNC40IDEuNU01MyA2NC42cS0xLjIgMC0xLjYtLjR0LS45LTEuN0w0MC43IDMwbC0uNC0xLjdxMC0xIDEtMWg0LjJxMS4yLS4xIDEuNi40dC45IDEuNmw3IDI3LjkgNi42LTI3LjlxLjMtMS4yLjgtMS42dDEuNy0uNWgzLjRxMS4yIDAgMS42LjUuNi40LjggMS42bDYuNyAyOC4yIDcuMy0yOC4ycS4zLTEuMi44LTEuNnQxLjctLjVoMy45cTEgMCAxIDF2LjhsLS40IDEtMTAuMSAzMi42cS0uNCAxLjItLjkgMS42dC0xLjYuNGgtMy42cS0xLjIgMC0xLjctLjR0LS44LTEuN2wtNi41LTI3LjEtNi41IDI3cS0uMyAxLjQtLjggMS44dC0xLjcuNFptNTQuMSAxLjFhMjggMjggMCAwIDEtMTEuMy0yLjRxLTEuMS0uNi0xLjMtMS4ybC0uMy0xLjJ2LTIuMXEwLTEuMyAxLTEuM2wuNy4xcS41LjEgMSAuNGEyMyAyMyAwIDAgMCA0LjcgMS41cTIuNi41IDUgLjUgNCAwIDYuMi0xLjQgMi4yLTEuNSAyLjItNCAwLTEuNy0xLjItMy0xLjEtMS4xLTQuMi0yLjFsLTYuMS0ycS00LjctMS4zLTYuOC00LjJhMTAgMTAgMCAwIDEtMS0xMC44IDExIDExIDAgMCAxIDMuMS0zLjRxMS45LTEuNSA0LjQtMi4yYTE4IDE4IDAgMCAxIDguMS0uNmwyLjcuNSA0LjIgMS40cS45LjUgMS4zIDF0LjQgMS41djJxMCAxLjItMSAxLjNsLTEuNi0uNXEtMy42LTEuNy04LjEtMS43LTMuNiAwLTUuNiAxLjJ0LTIgMy44YTQgNCAwIDAgMCAxLjMgM3ExLjMgMSA0LjYgMi4zbDYgMS45cTQuNSAxLjUgNi41IDQgMiAyLjYgMiA1LjkgMCAyLjctMS4xIDQuOS0xLjIgMi4xLTMuMSAzLjctMiAxLjUtNC43IDIuMy0yLjkgMS02IDFtMCAwIi8%2BPHBhdGggZmlsbD0iI2Y5MCIgZD0iTTExOCA3My4zYy00LjQuMS05LjcgMS4xLTEzLjYgMy45LTEuMi45LTEgMiAuMyAxLjkgNC41LS42IDE0LjUtMS44IDE2LjIuNSAxLjggMi4zLTIgMTEuNi0zLjYgMTUuOC0uNSAxLjMuNiAxLjggMS43LjggNy40LTYuMiA5LjMtMTkuMiA3LjgtMjEuMS0uNy0xLTQuNC0xLjgtOC44LTEuOE0xLjYgNzZjLS45IDAtMS4zIDEuMi0uMyAyYTkzIDkzIDAgMCAwIDYyLjYgMjRjMTcuMyAwIDM3LjQtNS41IDUxLjMtMTUuNyAyLjItMS43LjMtNC4zLTItMy4yQTEyNSAxMjUgMCAwIDEgMS41IDc1LjkiLz48L3N2Zz4%3D)</picture> <picture>![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)</picture> <picture>![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)</picture> <picture>![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)</picture> <picture>![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)</picture> |
| **Testing / Tooling** | <picture>![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)</picture> <picture>![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)</picture> <picture>![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)</picture> <picture>![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)</picture> <picture>![Playwright](https://img.shields.io/badge/Playwright-2D4552?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjcuMyAyNC4xIDExMC41IDgyLjgiPjxwYXRoIGZpbGw9IiMyRDQ1NTIiIGQ9Ik00My43IDcwLjlhMTcgMTcgMCAwIDAtOC42IDUuMyAxOCAxOCAwIDAgMSA3LTMuOHE0LjgtMS4zIDguMS0uNHYtMS44cS0yLjgtLjItNi41LjdtLTguOC0xNC42LTE1LjQgNCAuOCAxIDEzLTMuNXMtLjIgMi40LTEuOCA0LjVjMy0yLjMgMy40LTYgMy40LTZtMTIuOCAzNkMyNiA5OCAxNC43IDczIDExLjMgNjBxLTIuMy05LTIuNS0xMy40di0uOHEtMS42IDAtMS41IDIuMy4yIDQuNSAyLjQgMTMuNWMzLjUgMTMgMTQuOSAzOCAzNi40IDMyLjFxNy0yIDExLTYuNS0zLjcgMy40LTkuNCA1bTQtNTEuM3YxLjVoOC41bC0uNS0xLjV6Ii8%2BPHBhdGggZmlsbD0iIzJENDU1MiIgZD0iTTYyIDUzLjZjMy45IDEuMSA1LjkgMy44IDcgNi4xbDQuMiAxLjJzLS42LTguMi04LTEwLjNjLTctMi0xMS4zIDMuOC0xMS45IDQuNiAyLTEuNCA1LTIuNiA4LjgtMS42bTMzLjggNi4yYy03LTItMTEuMyAzLjktMTEuOCA0LjYgMi0xLjQgNS0yLjYgOC43LTEuNiAzLjggMS4xIDUuOSAzLjggNyA2LjFsNC4yIDEuMnMtLjYtOC4yLTgtMTAuM20tNC4yIDIxLjctMzUuMy05LjhzLjQgMiAxLjkgNC40bDI5LjcgOC4zYzIuNC0xLjQgMy43LTIuOSAzLjctMi45bS0yNC40IDIxLjNjLTI4LTcuNS0yNC42LTQzLjEtMjAtNjBhMTAxIDEwMSAwIDAgMSA1LjMtMTUuNVE1MSAyNi45IDUwIDI5cS0yLjcgNS4yLTYgMTYuOGMtNC41IDE2LjktNy44IDUyLjQgMjAgNjAgMTMuMyAzLjQgMjMuNS0yIDMxLjEtMTAuM2EyOSAyOSAwIDAgMS0yOCA3LjIiLz48cGF0aCBmaWxsPSIjRTI1NzRDIiBkPSJNNTEuNyA4NHYtNy4ybC0yMCA1LjZzMS42LTguNiAxMi0xMS41cTQuNy0xLjIgOC0uNVY0MWgxMHEtMS42LTUuMS0zLTcuN2MtMS41LTMtMy0xLTYuNCAxLjgtMi40IDItOC40IDYuMy0xNy41IDguN2E0NyA0NyAwIDAgMS0xOS42IDEuM2MtNC4zLS44LTYuNi0xLjctNi40IDEuNnEuMiA0LjUgMi41IDEzLjRjMy40IDEzIDE0LjggMzggMzYuNCAzMi4yUTU2IDg5LjkgNjAgODMuOXpNMTkuNSA2MC4ybDE1LjQtNHMtLjUgNS45LTYuMiA3LjQtOS4yLTMuNC05LjItMy40Ii8%2BPHBhdGggZmlsbD0iIzJFQUQzMyIgZD0iTTEwOS40IDQxLjNBNjEgNjEgMCAwIDEgODQgMzkuN2E2MSA2MSAwIDAgMS0yMi43LTExLjNjLTQuNC0zLjYtNi4zLTYuMi04LjItMi4zcS0yLjcgNS4xLTYgMTYuN2MtNC41IDE2LjktNy45IDUyLjUgMjAgNjAgMjggNy40IDQyLjgtMjUgNDcuMy00MnEzLTExLjYgMy4zLTE3LjRjLjMtNC4zLTIuNy0zLTguMy0ybS01Ni4xIDE0czQuNC02LjkgMTEuOC00LjdjNy41IDIgOCAxMC4zIDggMTAuM3pNNzEuNSA4NkM1OC40IDgyIDU2LjMgNzEuNyA1Ni4zIDcxLjdsMzUuMyA5LjhzLTcuMSA4LjMtMjAuMSA0LjVNODQgNjQuNXM0LjQtNi45IDExLjgtNC43YzcuNSAyIDggMTAuMyA4IDEwLjN6Ii8%2BPHBhdGggZmlsbD0iI0Q2NTM0OCIgZD0ibTQ0LjggNzguNy0xMyAzLjdzMS40LTggMTEtMTEuMmwtNy40LTI3LjYtLjYuMmE0NyA0NyAwIDAgMS0xOS42IDEuM2MtNC4zLS44LTYuNi0xLjctNi40IDEuNnEuMiA0LjUgMi41IDEzLjRjMy40IDEzIDE0LjggMzggMzYuNCAzMi4ybC42LS4yek0xOS41IDYwLjNsMTUuNC00cy0uNSA1LjktNi4yIDcuNC05LjItMy40LTkuMi0zLjQiLz48cGF0aCBmaWxsPSIjMUQ4RDIyIiBkPSJtNzIgODYuMS0uNS0uMUM1OC40IDgyIDU2LjMgNzEuNyA1Ni4zIDcxLjdsMTguMiA1IDkuNy0zN0g4NGE2MSA2MSAwIDAgMS0yMi43LTExLjNjLTQuNC0zLjYtNi4zLTYuMi04LjItMi4zYTk1IDk1IDAgMCAwLTYgMTYuN2MtNC41IDE2LjktNy45IDUyLjUgMjAgNjBoLjZ6TTUzLjQgNTUuM3M0LjQtNi45IDExLjgtNC43YzcuNSAyIDggMTAuMyA4IDEwLjN6Ii8%2BPHBhdGggZmlsbD0iI0MwNEI0MSIgZD0ibTQ1LjQgNzguNS0zLjUgMXExLjIgNy4xIDQuNiAxM2wxLjItLjIgMy0xYTM3IDM3IDAgMCAxLTUuMy0xMi44TTQ0LjEgNDZhODkgODkgMCAwIDAtMyAyNmwyLjYtMSAuNi0uMWMtLjgtMTAuMyAxLTIwLjggMi44LTI4bDEuNS01LTIuNiAxLjV6Ii8%2BPC9zdmc%2B)</picture> <picture>![Biome](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=white)</picture> |

