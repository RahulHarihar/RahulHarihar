<div align="center">

<a href="https://rahulharihar-portfolio.vercel.app">
  <img src="https://rahulharihar-portfolio.vercel.app/og-image.jpg" alt="Rahul Harihar, Software Engineer. Building reliable systems: rls, ci/cd, ai pipelines." width="100%" />
</a>

<br/><br/>

**software engineer. ai fellow @ NewStreet Technologies, bangalore.**<br/>
<sub>i build the unglamorous parts properly: multi-tenant postgres, ci/cd, and ai pipelines with real evals.</sub>

<br/><br/>

[![portfolio](https://img.shields.io/badge/portfolio-111110?style=flat-square&logo=vercel&logoColor=e9e7e2)](https://rahulharihar-portfolio.vercel.app)
[![linkedin](https://img.shields.io/badge/linkedin-111110?style=flat-square&logo=linkedin&logoColor=e9e7e2)](https://linkedin.com/in/rahulharihar-)
[![x](https://img.shields.io/badge/@iamRahul__H-111110?style=flat-square&logo=x&logoColor=e9e7e2)](https://x.com/iamRahul_H)
[![email](https://img.shields.io/badge/work.rahul007@gmail.com-ff4a1c?style=flat-square&logo=gmail&logoColor=white)](mailto:work.rahul007@gmail.com)
[![resume](https://img.shields.io/badge/resume-111110?style=flat-square&logo=googledrive&logoColor=e9e7e2)](https://drive.google.com/file/d/1PXDVzzk4gY6r9zvo2BJ6ytLgrU4nvqlb/view?usp=drive_link)

</div>

---

### `$ whoami`

```yaml
name:      Rahul Harihar
role:      Software Engineer
now:       AI Fellowship Intern @ NewStreet Technologies
based_in:  Bangalore, IN
shipped:   a clinic system that a real practice runs on every day
believes:  evals over vibes. tests over hope.
```

---

### `$ ls ~/shipped`

| project | what it is | stack | |
|:--|:--|:--|:--|
| **CareDesk** | clinic management system for a pediatric cardiology practice. live in prod, runs the front desk + doctor's day | React · TS · Express · Prisma · Postgres 17 · AWS | `private` |
| **[ClauseAI](https://frontend-blue-three-92.vercel.app)** | drop in two contracts, get the conflicts flagged. embeddings + gemini with 3-model fallback. **0.97 F1** on hand-labeled evals | Bun · React · TS · Gemini | [code](https://github.com/RahulHarihar/ClasueAI) |
| **[Kids Heart Clinic](https://kidsheartsclinic.com)** | mobile-first clinic site on cloudflare workers. serverless booking form, turnstile + rate limiting vs spam | Workers · Resend · Turnstile | `client` |
| **[DevStrex](https://devstrex.vercel.app)** | track any coding challenge. log daily, keep the streak, share one public link | React · Node · Express · MongoDB · TS | [code](https://github.com/RahulHarihar/devstrex) |

<details>
<summary><b>▸ what's under CareDesk's hood</b> (it's private, so here's the spec)</summary>

<br/>

```diff
+ api      express + zod, prisma on postgres 17, versioned migrations
+ safety   version checks so two machines can't clobber each other's echo report edits
+ history  locked reports keep their full correction history
+ auth     doctor / receptionist roles, httponly sessions + csrf, bcrypt + rate limits
+ data     isolated per clinic. the audit log never stores patient details
+ tests    300+ (vitest, testing library, supertest) on a separate test db
+ deploy   aws ec2 behind a cloudflare tunnel. zero open inbound ports
+ ops      tagged releases, scripted rollback, nightly encrypted s3 backups with tested restores
```

</details>

---

### `$ git log --oneline career`

```
4e1c0d2 (HEAD -> main) feat: join NewStreet Technologies as AI Fellowship Intern
9b7f3a1 feat: ship CareDesk to prod for a pediatric cardiology practice
e62d0b8 docs: co-author a clustering algorithms paper (IIIE Pune, jun 2026)
2d84c6e fix: trace a prod login outage to one unset session variable (VanLoka)
7a03e55 feat: postgres rls across 11 tables + ci/cd to azure, as team lead intern (VanLoka)
c51f9e0 chore: review + merge 50+ PRs, coordinate a 5-person team
0a1b2c3 init: MCA @ KLS Gogte Institute of Technology (cgpa 8.14)
```

---

### `$ cat stack.json`

```json
{
  "languages": ["TypeScript", "JavaScript", "Python", "Java", "SQL"],
  "frontend":  ["React", "Vite", "Tailwind"],
  "backend":   ["Node.js", "Express", "Bun", "REST", "Zod"],
  "data":      ["PostgreSQL", "Prisma", "MongoDB", "MySQL"],
  "infra":     ["AWS", "Azure", "Cloudflare Workers", "GitHub Actions"],
  "testing":   ["Vitest", "Testing Library", "Supertest"],
  "ai":        ["Gemini API", "Claude", "embeddings + evals"]
}
```

---

### `$ gh pr list --author @me`

```diff
+ merged     code-a2z/paisable          auth signup validation cleanup, through full review + CI
! in review  karansinghgit/speaktype    made the audio player keyboard-accessible (W3C ARIA slider pattern)
! in review  karansinghgit/speaktype    fixed the formatModelSize threshold + added unit tests
```

<sub>[#46](https://github.com/code-a2z/paisable/pull/46) · [#185](https://github.com/karansinghgit/speaktype/pull/185) · [#149](https://github.com/karansinghgit/speaktype/pull/149)</sub>

---

### `$ cat elsewhere.txt`

```
paper       co-author, "Comparative Study on Advanced Clustering Algorithms:
            Grid-based and Graph-based Clustering" (IIIE Pune, jun 2026)
lead        won the General Championship at state-level college events
            6× wins, 2× runner-up
volunteer   tech volunteer at a national hackathon. wrote the AI/ML +
            blockchain problem statements
edu         MCA, KLS GIT (8.14) · BCA, KLS GCC (8.2)
```

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RahulHarihar&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&bg_color=111110&title_color=ff4a1c&icon_color=ff4a1c&text_color=e9e7e2" height="165" />
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RahulHarihar&hide_border=true&layout=compact&count_private=true&bg_color=111110&title_color=ff4a1c&text_color=e9e7e2" height="165" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/RahulHarihar/RahulHarihar/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RahulHarihar/RahulHarihar/output/github-snake.svg" />
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/RahulHarihar/RahulHarihar/output/github-snake.svg" />
</picture>

<sub><i>O(n) hunger, O(1) regrets</i></sub>

<br/><br/>

<sub>dms open for databases, infra, ai tooling, or a good bug story · <a href="https://rahulharihar-portfolio.vercel.app">rahulharihar-portfolio.vercel.app</a></sub>

</div>
