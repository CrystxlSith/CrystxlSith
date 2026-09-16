<p align="center">
  <a href="https://joaquimpfeiffer.dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=700&lines=Seeking+a+6-month+internship+or+1-year+apprenticeship;Available+from+2027+%C2%B7+based+near+Paris;Co-founder+%26+lead+dev+%40+Glasck.gg;Student+at+42+Paris;Building+with+Claude+Code%2C+from+prototype+to+prod" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open_to-Internship_%2F_Apprenticeship_%C2%B7_2027-A855F7?style=for-the-badge" alt="Open to internship or apprenticeship" />
  <a href="https://joaquimpfeiffer.dev"><img src="https://img.shields.io/badge/Portfolio-joaquimpfeiffer.dev-22D3EE?style=for-the-badge" alt="Portfolio" /></a>
  <a href="mailto:contact@joaquimpfeiffer.dev"><img src="https://img.shields.io/badge/Email-contact%40joaquimpfeiffer.dev-7C3AED?style=for-the-badge" alt="Email" /></a>
</p>

## 👋 About me

- 🎓 Student at **42 Paris**, common core completed
- 🚀 Co-founder & lead dev of **[Glasck.gg](https://glasck.gg)**, a League of Legends esports platform in production since 2024
- 🔎 Looking for a **6-month internship** or a **1-year apprenticeship**, starting in **2027**
- 🤖 Daily **Claude Code** user (agents, subagents, workflows), from prototype to production
- 🌍 Based near Paris · French (native) · English (B2+)

## 🚀 Glasck.gg

Esports platform for League of Legends: pro match stats, ranked players, champion meta and predictions. Team of 2 devs, 1 DevOps and 1 marketer.

<table align="center">
  <tr>
    <td align="center"><h3>80M</h3>requests / month</td>
    <td align="center"><h3>360k</h3>indexed pages</td>
    <td align="center"><h3>14</h3>languages</td>
    <td align="center"><h3>187M</h3>rows in the largest Postgres table</td>
  </tr>
</table>

- **Distributed Riot API rate limiter**: Redis buckets shared across processes, user requests served before background jobs, Grafana dashboard
- **Postgres at scale**: ~50 GB reclaimed on a 90 GB table (primary key inversion, redundant indexes), hottest query from 130 ms to 3.3 ms
- **Data pipeline**: 37 BullMQ queues, batched match ingestion, a job cut from 1,240 s to 55 s
- **Production incident**: a relative link created an infinite URL space × 14 languages, crawlers flooded the app into OOM; fixed in code (404 on deep URLs, regression test) and infra (replicas, real-IP rate limiting)
- **Technical SEO**: sitemap worker, hreflang, JSON-LD, backend-driven ISR invalidation, `llms.txt` and Markdown served to AI agents

`Fastify 5` `TypeScript` `Prisma` `PostgreSQL` `Redis` `BullMQ` `OpenTelemetry` `Next.js 16` `React 19` `Tailwind 4` `Docker` `Traefik` `Prometheus` `Grafana` `Loki` `GitHub Actions`

## 🛠️ Projects

| Project | Stack | What it is |
|---|---|---|
| [ft_transcendence](https://github.com/CrystxlSith/Transcende_me_if_you_can) | TypeScript · Fastify · WebSocket | Real-time multiplayer Pong SPA: chat, tournaments, AI opponent, OAuth + 2FA, Prometheus/Grafana, ELK |
| [webserv](https://github.com/CrystxlSith/webserv) | C++98 | Non-blocking HTTP/1.1 server: single epoll loop, nginx-style config, virtual hosts, CGI, chunked, keep-alive |
| [Inception](https://github.com/CrystxlSith/Inception) | Docker | NGINX (TLS 1.3), WordPress/PHP-FPM and MariaDB, images built from Debian, Docker secrets |
| [Minishell](https://github.com/CrystxlSith/Minishell) | C | Unix shell: lexer, parser, builtins, pipes, redirections, heredoc, signals |
| [CUB3D](https://github.com/CrystxlSith/CUB3D) | C | Raycasting engine (DDA): textures, floorcasting, minimap, doors |
| **Fitz** *(private)* | TypeScript · Fastify · Drizzle · Expo | "Letterboxd for books": links a work to its editions and languages using Open Library, Wikidata and the BnF |

## 🧰 Tech stack

<p>
  <b>Languages</b><br/>
  <img src="https://skillicons.dev/icons?i=ts,c,cpp,py,bash&theme=dark" alt="Languages" />
</p>
<p>
  <b>Backend</b><br/>
  <img src="https://skillicons.dev/icons?i=nodejs,prisma,postgres,redis&theme=dark" alt="Backend" />
</p>
<p>
  <b>Frontend</b><br/>
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,figma&theme=dark" alt="Frontend" />
</p>
<p>
  <b>DevOps & tooling</b><br/>
  <img src="https://skillicons.dev/icons?i=docker,nginx,cloudflare,githubactions,ansible,prometheus,grafana,linux,git,pnpm,vitest&perline=11&theme=dark" alt="DevOps and tooling" />
</p>

## 🐍 Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CrystxlSith/CrystxlSith/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CrystxlSith/CrystxlSith/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/CrystxlSith/CrystxlSith/output/github-snake.svg" />
  </picture>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,100:A855F7&height=120&section=footer" alt="" />
</p>
