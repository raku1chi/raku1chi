<div align="center">

# raku1chi

仕事では Python を中心に、主にバックエンドの開発をしています。<br>
個人開発では、公的データやオープンデータ、好きなものを題材に、<br>
「調べる・比べる・眺める」が気持ちよくできる Web サービスを作っています。<br>
データを集めるところから、設計・API・画面・公開後の運用まで、一通り手を動かすのが好きです。

<br>

<p>
  <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/python/python-original.svg" width="36" height="36" alt="Python" title="Python" />&nbsp;
  <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/fastapi/fastapi-original.svg" width="36" height="36" alt="FastAPI" title="FastAPI" />&nbsp;
  <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/typescript/typescript-original.svg" width="36" height="36" alt="TypeScript" title="TypeScript" />&nbsp;
  <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/react/react-original.svg" width="36" height="36" alt="React" title="React" />&nbsp;
  <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/cloudflare/cloudflare-original.svg" width="36" height="36" alt="Cloudflare" title="Cloudflare" />
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
| **Backend / Data** | <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/python/python-original.svg" width="40" height="40" alt="Python" title="Python" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/fastapi/fastapi-original.svg" width="40" height="40" alt="FastAPI" title="FastAPI" /> <img src="https://cdn.simpleicons.org/sqlalchemy" width="40" height="40" alt="SQLAlchemy" title="SQLAlchemy" /> <img src="https://cdn.simpleicons.org/hono" width="40" height="40" alt="Hono" title="Hono" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL" title="PostgreSQL" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/duckdb/duckdb-original.svg" width="40" height="40" alt="DuckDB" title="DuckDB" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/go/go-original.svg" width="40" height="40" alt="Go" title="Go" /> |
| **Frontend** | <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript" title="TypeScript" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/react/react-original.svg" width="40" height="40" alt="React" title="React" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/nextjs/nextjs-original.svg" width="40" height="40" alt="Next.js" title="Next.js" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/vitejs/vitejs-original.svg" width="40" height="40" alt="Vite" title="Vite" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/tailwindcss/tailwindcss-original.svg" width="40" height="40" alt="Tailwind CSS" title="Tailwind CSS" /> <img src="https://cdn.simpleicons.org/maplibre" width="40" height="40" alt="MapLibre" title="MapLibre" /> |
| **Infra / Ops** | <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/cloudflareworkers/cloudflareworkers-original.svg" width="40" height="40" alt="Cloudflare Workers" title="Cloudflare Workers" /> <img src="https://cdn.simpleicons.org/cloudflarepages" width="40" height="40" alt="Cloudflare Pages" title="Cloudflare Pages" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="40" height="40" alt="AWS" title="AWS" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/terraform/terraform-original.svg" width="40" height="40" alt="Terraform" title="Terraform" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/docker/docker-original.svg" width="40" height="40" alt="Docker" title="Docker" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/githubactions/githubactions-original.svg" width="40" height="40" alt="GitHub Actions" title="GitHub Actions" /> <picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/vercel/white" /><img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/vercel/vercel-original.svg" width="40" height="40" alt="Vercel" title="Vercel" /></picture> |
| **Testing / Tooling** | <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/pytest/pytest-original.svg" width="40" height="40" alt="pytest" title="pytest" /> <img src="https://cdn.simpleicons.org/ruff" width="40" height="40" alt="Ruff" title="Ruff" /> <img src="https://cdn.simpleicons.org/uv" width="40" height="40" alt="uv" title="uv" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/vitest/vitest-original.svg" width="40" height="40" alt="Vitest" title="Vitest" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/playwright/playwright-original.svg" width="40" height="40" alt="Playwright" title="Playwright" /> <img src="https://cdn.jsdelivr.net/npm/devicon@2.17.0/icons/biome/biome-original.svg" width="40" height="40" alt="Biome" title="Biome" /> |

