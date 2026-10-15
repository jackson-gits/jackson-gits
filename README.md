<div align="center">

<img src="./header.svg" width="560" alt="Jackson Raj A | software developer, AI engineer" />

</div>

```python
# about.py
class Jackson:
    name      = "Jackson Raj A"
    role      = "Software Developer / AI Engineer"
    based_in  = "Chennai, India"
    education = "B.E. Computer Science Engineering, Saveetha Engineering College"
    strengths = ["secure backend design", "full-stack (MERN + TypeScript)", "AI agent safety testing"]
    building  = "mule-account ring detection for UPI scams  # IBM Z Datathon 2026"
    open_to   = ["entry-level software engineering", "trainee roles", "internships"]
```

<br>

### Projects

**Bodilicious**: e-commerce platform, built solo for a freelance client<br>
Took it from requirements to deployment on its own. It handles the full order lifecycle, including COD, cancellations and returns/refunds. Payments follow a Quote → Init → Verify flow with HMAC-SHA256 signature checks, so prices can't be tampered with. Emails, notifications and Shiprocket logistics syncing run as background jobs on Redis + BullMQ, with retries and exponential backoff.<br>
`React` `TypeScript` `Node.js` `Express` `MongoDB` `Redis` `Razorpay`

<br>

**Creuset**: a security gate for AI agents<br>
Fail-closed by design. Before an agent ships, it has to pass 26 adversarial tests (prompt injection, tool misuse, jailbreaks, policy and scope violations), scored by deterministic rules plus an LLM judge using median-of-N sampling. Agents run in a locked-down Docker sandbox with a single allowlisted egress proxy. Deploys are blue-green, and a traffic monitor rolls back automatically in about 2.5 seconds when it detects anomalies.<br>
`Python` `FastAPI` `Docker`

<br>

**UPI mule-account ring detection**: in progress<br>
Detecting rings of mule accounts that move scam money through UPI. Built for the IBM Z Datathon 2026.

<!-- When a repo is public, link its name above, e.g. **[Creuset](https://github.com/jackson-gits/<repo-name>)** -->

<br>

### Stack

**Languages**
<br>
<img src="https://skillicons.dev/icons?i=java,py,js,ts,cpp,c,dart&theme=dark" alt="languages" />

**Frontend**
<br>
<img src="https://skillicons.dev/icons?i=react,vite,html,css,bootstrap&theme=dark" alt="frontend" />

**Backend & databases**
<br>
<img src="https://skillicons.dev/icons?i=nodejs,express,django,fastapi,mongodb,mysql,redis&theme=dark" alt="backend" />

**Infra & tools**
<br>
<img src="https://skillicons.dev/icons?i=docker,aws,cloudflare,git,github,figma,vscode&theme=dark" alt="tools" />

<br>

### Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jackson-gits/jackson-gits/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jackson-gits/jackson-gits/output/github-snake.svg" />
  <img alt="contribution graph" src="https://raw.githubusercontent.com/jackson-gits/jackson-gits/output/github-snake.svg" />
</picture>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=jackson-gits&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF" />
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=jackson-gits&show_icons=true&hide_border=true" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=jackson-gits&layout=compact&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" />
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jackson-gits&layout=compact&hide_border=true" />
</picture>

### Contact

[LinkedIn](https://www.linkedin.com/in/jackson-raj-417321290) · [Email](mailto:jacksonraj0711@gmail.com)
