<div align="center">

<!-- ANIMATED TYPING HEADER -->
<a href="https://github.com/Punit49">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=26&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=900&height=110&lines=%241+sudo+whoami;%3E+Software+Engineer+%7C+TypeScript+%2B+React+%2B+PostgreSQL;%3E+I+turn+coffee+into+production+deploys;%3E+while(!success)+%7B+debug()%3B+%7D" alt="Typing SVG" />
</a>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:58A6FF&height=180&section=header&text=PUNIT&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Engineer%20%7C%20Builder%20%7C%20Lifelong%20Debugger&descAlignY=58&descSize=18" width="100%"/>

</div>

<!-- STATUS BAR -->
<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/Punit49?label=Follow&style=for-the-badge&color=58A6FF&labelColor=0d1117)](https://github.com/Punit49?tab=followers)
![Profile Views](https://komarev.com/ghpvc/?username=Punit49&label=Profile+Views&color=58A6FF&style=for-the-badge&labelColor=0d1117)
[![LeetCode](https://img.shields.io/badge/LeetCode-therealpunit-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0d1117)](https://leetcode.com/u/therealpunit)
![Status](https://img.shields.io/badge/status-shipping-brightgreen?style=for-the-badge&labelColor=0d1117)

</div>

<br/>

<!-- QUICK NAV -->
<div align="center">

`[` [About](#-catabout_mejson) `]` &nbsp;`[` [Philosophy](#-manifesto) `]` &nbsp;`[` [Stack](#-top--o-cpu--tech-i-run-on) `]` &nbsp;`[` [Workflow](#-mydevworkflowyml) `]` &nbsp;`[` [LeetCode](#-ping-leetcodecom) `]` &nbsp;`[` [Stats](#-git-log---stat---authorpunit) `]` &nbsp;`[` [Snake](#-contribution_snakegif) `]`

</div>

<br/>

## `> cat about_me.json`

```json
{
  "name": "Punit",
  "role": "Software Engineer",
  "location": "India",
  "stack": {
    "languages": ["TypeScript", "JavaScript", "SQL"],
    "frontend": ["React", "HTML5", "CSS3"],
    "backend": ["Node.js", "REST APIs"],
    "database": ["PostgreSQL"],
    "tools": ["Git", "GitHub", "VS Code", "Docker"]
  },
  "focus_areas": [
    "production-grade full-stack systems",
    "secure payment & webhook integrations",
    "role-based access & multi-tenant architecture",
    "real-time browser APIs (WebRTC / WebSockets)",
    "system design for scale"
  ],
  "currently_learning": ["cloud infra & deployment strategy", "distributed systems"],
  "philosophy": "boring technology, exciting outcomes",
  "fun_fact": "has strong opinions about tabs vs spaces (spaces, obviously)"
}
```

<br/>

## `> ./manifesto.sh`

<table width="100%">
<tr>
<td width="33%" valign="top" align="center">

### 🧠
**Think in systems**

Every feature is a node in a larger graph. I trace the blast radius before I write the first line.

</td>
<td width="33%" valign="top" align="center">

### 🔒
**Security is not optional**

Idempotency keys, signature verification, circuit breakers — resilience is a feature, not an afterthought.

</td>
<td width="33%" valign="top" align="center">

### 🚀
**Ship, then sharpen**

Working code today beats perfect code next sprint. I iterate in the open and refactor with intent.

</td>
</tr>
<tr>
<td width="33%" valign="top" align="center">

### 📖
**Read before you write**

Every framework, library, and API has an origin story. I read the docs before I fight the stack trace.

</td>
<td width="33%" valign="top" align="center">

### 🧩
**Own the whole stack**

Frontend state, backend contracts, database schema — I hold the entire picture in my head, not just my layer.

</td>
<td width="33%" valign="top" align="center">

### 🧭
**Debug like a detective**

No guessing. Reproduce, isolate, hypothesize, verify. The bug always leaves a trail.

</td>
</tr>
</table>

<br/>

## `> top -o cpu` — tech I run on

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,react,nodejs,postgres,html,css,git,github,vscode,figma,docker,linux,vercel&theme=dark" />

</div>

<br/>

<div align="center">

| Layer | Tools |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Frontend** | ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **Tooling** | ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) |

</div>

<br/>

## `> ./my_dev_workflow.yml`

```yaml
name: punit-dev-loop
on: [new_problem]

jobs:
  understand:
    steps:
      - read: requirements twice
      - ask: "what breaks this?"
      - sketch: data flow before code flow

  build:
    steps:
      - write: smallest working version
      - test: edge cases, not just happy path
      - commit: small, atomic, meaningful messages

  harden:
    steps:
      - add: error boundaries & fallbacks
      - add: logging that future-me will thank present-me for
      - review: "would I approve this PR from a stranger?"

  ship:
    steps:
      - deploy: with a rollback plan
      - monitor: don't ship and disappear
      - iterate: based on real usage, not assumptions
```

<br/>

## `> cat coding_journey.log`

```diff
+ [learning]     started with the fundamentals — HTML, CSS, JS, the classics
+ [leveling up]  moved into React, learned to think in components & state
+ [going deep]   picked up TypeScript for type-safety across large codebases
+ [full-stack]   added PostgreSQL & Node.js to own the entire request lifecycle
+ [production]   shipped features that real users depend on daily
+ [scaling]      now studying system design & infra to build for scale
! [ongoing]      still reading docs at 1am when something "should just work"
```

<br/>

## `> ping leetcode.com`

<div align="center">

<img src="https://leetcard.jacoblin.cool/therealpunit?theme=dark&font=Fira%20Code&ext=heatmap" alt="Punit's LeetCode stats"/>

</div>

<div align="center">

[![LeetCode Profile](https://img.shields.io/badge/View_Full_Profile-therealpunit-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/therealpunit)

</div>

<br/>

## `> git log --stat --author="Punit"`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Punit49&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="165"/>
<img src="https://streak-stats.demolab.com?user=Punit49&theme=tokyonight&hide_border=true" height="165"/>

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Punit49&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165"/>

</div>

<br/>

## `> ./contribution_snake.gif`

<div align="center">

<!-- Renders automatically once the GitHub Action below is enabled -->
<img src="https://raw.githubusercontent.com/Punit49/Punit49/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

<br/>

## `> cat contact.sh`

```bash
#!/bin/bash
echo "Open to interesting problems, good engineering conversations, and collaboration."
echo "Best way to reach me → GitHub profile / issues / discussions."
exit 0
```

<br/>

<div align="center">

### `> echo "thanks for reading this far"`

*Still compiling... always learning, always shipping.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:0d1117&height=100&section=footer" width="100%"/>

</div>
