<h1 align="center">Hi, I'm Ahmed Mkacher</h1>
<h3 align="center">Software Engineer at Imperia AI — Backend & DevOps</h3>

Software Engineer at [Imperia AI](https://chatti.tn/about), building [chatti.tn](https://chatti.tn). Focused on Backend and DevOps — distributed systems, background workers, caching layers, and reversible deploys that hold up at scale. Open to new opportunities.

<details open>
<summary><b>Backend</b> — core stack</summary>

<br>

<p>For backend work, these are the technologies I reach for, and the choice depends on the job at hand. At chatti, the serving path is TypeScript on Bun, with Elysia handling requests, Effect carrying the heavier workflows, and TanStack Query with ElectricSQL keeping client data in sync.</p>

<p>We use Postgres as the database, which we talk to through Drizzle as the ORM, behind oRPC typesafe contracts used instead of traditional REST APIs and validated primarily by Effect Schema, with Zod reserved for AI SDK tool schemas, built with Vite in a Turborepo and pnpm workspace and covered by Vitest, with PostHog keeping the product observable. Redis serves as the caching layer for hot paths, while Python covers light scripting and the analysis pipeline. This same stack and flow I use for most of my projects.</p>

<table border="0" cellspacing="0" cellpadding="6">
  <tr>
    <td valign="middle"><b>Languages:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=typescript,python,golang&perline=3&radius=40" width="120" alt="Backend Languages" title="TypeScript, Python, Go" /></td>
  </tr>
  <tr>
    <td valign="middle"><b>Runtimes:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=nodejs,bun&perline=2&radius=40" width="78" alt="Backend Runtimes" title="Node.js, Bun" /></td>
  </tr>
  <tr>
    <td valign="middle"><b>Frameworks:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=tanstack,elysia,effect&perline=3&radius=40" width="120" alt="Backend Frameworks" title="TanStack, Elysia, Effect" /></td>
  </tr>
  <tr>
    <td valign="middle"><b>Tools:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=turborepo,vite,vitest,oxc,pnpm,redis,drizzle,postgresql,supabase,convex,posthog,aisdk,rabbitmq,upstash,orpc&perline=5&radius=40" width="204" alt="Backend Tools" title="Turborepo, Vite, Vitest, Oxc, pnpm, Redis, Drizzle, PostgreSQL, Supabase, Convex, PostHog, AI SDK, RabbitMQ, Upstash, oRPC" /></td>
  </tr>
</table>
</details>

<details>
<summary><b>Systems</b> — lower-level</summary>

<br>

<p>Outside of work, I usually reach for Bash and C when tinkering on my own machine. Bash covers light work and scripting, C is for the critical stuff where I want to see what the machine is actually doing.</p>

<table border="0" cellspacing="0" cellpadding="6">
  <tr>
    <td valign="middle"><b>Languages:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=c,bash&perline=2&radius=40" width="78" alt="Systems Languages" title="C, Bash" /></td>
  </tr>
</table>
</details>

<details>
<summary><b>DevOps</b> — ship it, keep it up</summary>

<br>

<p>I've run all of these in different environments. I lean self-hosted first, so Dokploy is my default for shipping small Docker images, with Kubernetes where workloads need to scale across nodes. AWS is comfortable ground too — CloudFront, S3, EC2, and the rest of the ecosystem when managed services fit better. GitHub Actions runs the CI/CD pipeline behind every release, so each change is tested, traceable, and reversible through Git and GitHub. Boring releases: ship often, roll back fast.</p>

<table border="0" cellspacing="0" cellpadding="6">
  <tr>
    <td valign="middle"><b>Tools:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=docker,kubernetes,amazonwebservices,dokploy,cloudflare&perline=5&radius=40" width="204" alt="DevOps Tools" title="Docker, Kubernetes, AWS, Dokploy, Cloudflare" /> <br> <img align="center" src="https://skills.syvixor.com/api/icons?i=git,github,githubactions,googlecloud,vercel&perline=5&radius=40" width="204" alt="DevOps Tools line 2" title="Git, GitHub, GitHub Actions, Google Cloud, Vercel" /></td>
  </tr>
</table>
</details>

<details>
<summary><b>AI</b> — building with LLMs</summary>

<br>

<p>Using an agent harness in the AI era is inevitable, and so I have had my fair share. I have worked with several coding agents and harnesses, and OpenCode, Codex, Claude Code, and Grok are the ones I am most comfortable with. My setup of prompts, skills, and workflows carries over across every harness, so the tooling stays consistent wherever the work happens. When building with the AI SDK, tool schemas are defined with Zod.</p>

<table border="0" cellspacing="0" cellpadding="6">
  <tr>
    <td valign="middle"><b>Tools:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=opencode,codex,grok,claudecode&perline=4&radius=40" width="162" alt="AI Tools" title="OpenCode, Codex, Grok, Claude Code" /></td>
  </tr>
</table>
</details>

<details>
<summary><b>Socials</b> — where you can find me</summary>

<br>

<p>I am open to backend and DevOps roles, especially on teams whose distributed systems and infrastructure have to hold up under load. If that is what you are building, I would like to hear about it.</p>

<p><a href="https://linkedin.com/in/ahmad-mkacher"><img src="https://skills.syvixor.com/api/icons?i=linkedin&perline=1&radius=40" width="32" alt="LinkedIn" title="LinkedIn" /></a> <a href="https://x.com/mkacher_"><img src="https://skills.syvixor.com/api/icons?i=x&perline=1&radius=40" width="32" alt="X" title="X" /></a></p>
</details>

<details>
<summary><b>Previously used Tech, Lightly</b></summary>

<br>

<p>Earlier in my career and learning path I have worked with several technologies and languages, even if lightly. I ran through C++ for competitive programming and Qt, Java, PHP with Symfony, XAMPP stacks, Arduino tinkering, and Express services. That spread taught me how much a typesafe contract layer and boring, reversible deploys matter once more than one machine is involved. These tools stay in the background now, reached for only when legacy context or hardware-adjacent work calls for them.</p>

<p style="display: flex; flex-direction: row; flex-wrap: nowrap; gap: 12px; align-items: center;"><img src="https://skills.syvixor.com/api/icons?i=cpp,java,php,symfony,xampp,qtwidgets,arduino,expressjs,vscode,intellij&perline=10&radius=40" width="390" alt="Previously" title="C++, Java, PHP, Symfony, XAMPP, Qt, Arduino, Express.js, VSCode, JetBrains" /></p>
</details>

<details>
<summary><b>Toolbox</b> — daily drivers</summary>

<br>

<p>Day to day I edit in Zed and Neovim on Cachy (Arch btw), with Zen as the browser. Tailscale links my machines so every environment is one hop away. Nothing exotic: fast tools, keyboard-first, same setup everywhere.</p>

<table border="0" cellspacing="0" cellpadding="6">
  <tr>
    <td valign="middle"><b>Editors:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=zed,neovim&perline=2&radius=40" width="78" alt="Toolbox Editors" title="Zed, Neovim" /></td>
  </tr>
  <tr>
    <td valign="middle"><b>OS:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=cachyos,hyprland&perline=2&radius=40" width="78" alt="Toolbox OS" title="CachyOS, Hyprland" /></td>
  </tr>
  <tr>
    <td valign="middle"><b>Tools:</b></td>
    <td><img align="center" src="https://skills.syvixor.com/api/icons?i=zen,tailscale,tmux&perline=3&radius=40" width="120" alt="Toolbox Tools" title="Zen, Tailscale, tmux" /></td>
  </tr>
</table>
</details>
