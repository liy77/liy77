<table>
<tr>
<td width="68%" valign="middle">

# liy

<img src="assets/brazil.png" width="28" alt="Flag of Brazil"/> **Brazilian developer**

C/C++ · Rust · JavaScript · TypeScript · Java · Go

I write [Mikasa](https://github.com/liy77/mikasa), a language that transpiles to Rust. Astra interprets it instantly.

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2800&pause=900&color=E10600&center=false&vCenter=true&width=460&lines=C+and+C%2B%2B;Rust%2C+JavaScript%2C+TypeScript;Java+and+Go;Mikasa+%E2%86%92+Rust" alt="C and C++, Rust, JavaScript, TypeScript, Java, Go, Mikasa to Rust"/>

</td>
<td width="32%" align="center" valign="middle">

<img src="assets/mikasa-ackerman.png" width="210" alt="Mikasa Ackerman"/>

</td>
</tr>
</table>

---

<div align="center">

## Languages I work in

</div>

<table>
<tr>
<td align="center" width="50%" colspan="2">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="46" alt="C logo"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="46" alt="C++ logo"/>
<br/><b>C / C++</b>
<br/><sub>the languages I live in</sub>
</td>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" width="46" alt="Rust logo"/>
<br/><b>Rust</b>
<br/><sub>Mikasa → Rust</sub>
</td>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="46" alt="JavaScript logo"/>
<br/><b>JavaScript</b>
</td>
</tr>
<tr>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="46" alt="TypeScript logo"/>
<br/><b>TypeScript</b>
</td>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="46" alt="Java logo"/>
<br/><b>Java</b>
</td>
<td align="center" width="50%" colspan="2">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="46" alt="Go logo"/>
<br/><b>Go</b>
</td>
</tr>
</table>

---

<div align="center">

## The language

<a href="https://github.com/liy77/mikasa">
<img src="https://raw.githubusercontent.com/liy77/mikasa/master/editors/vscode/icons/mika-icon-dark.png" width="72" alt=".mika file icon"/>
</a>

### [Mikasa](https://github.com/liy77/mikasa)

A language that transpiles to Rust. Astra interprets it instantly. Formerly Copper.

<a href="https://github.com/liy77/mikasa">
<img src="https://img.shields.io/badge/project-liy77%2Fmikasa-E10600?style=for-the-badge&logo=github&logoColor=white" alt="Mikasa project"/>
</a>
<!-- MIKASA-RELEASE-BADGE:START -->
<a href="https://github.com/liy77/mikasa/releases/tag/v0.26.6">
<img src="https://img.shields.io/badge/latest-v0.26.6-111111?style=for-the-badge" alt="Latest release"/>
</a>
<!-- MIKASA-RELEASE-BADGE:END -->
<a href="https://github.com/liy77/mikasa/stargazers">
<img src="https://img.shields.io/github/stars/liy77/mikasa?style=for-the-badge&color=E10600&logo=github" alt="Mikasa stars"/>
</a>

</div>

<table>
<tr>
<td width="18%" align="center">
<img src="https://raw.githubusercontent.com/liy77/mikasa/master/assets/mikasa.png" width="78" alt="Mikasa logo"/>
</td>
<td width="32%">
<b>mikasa</b>
<br/>Transpiles <code>.mika</code> to Rust.
<br/><sub>Native speed after the first compile.</sub>
</td>
<td width="18%" align="center">
<img src="https://raw.githubusercontent.com/liy77/mikasa/master/assets/astra-logo.png" width="78" alt="Astra logo"/>
</td>
<td width="32%">
<b>astra</b>
<br/>Interprets it instantly.
<br/><sub>No compile step. Like python or node.</sub>
</td>
</tr>
</table>

```mika
import { trim } from mika

func main() {
    mut name = trim("  Ada  ")
    println("Your name is $name")
}
```

`mikasa run file.mika` · `astra run file.mika`

---

## Latest release

<!-- MIKASA-RELEASE:START -->
### [v0.26.6](https://github.com/liy77/mikasa/releases/tag/v0.26.6)

<sub>Published 2026-06-03</sub>

**Release notes**

- Copper language front-end (tokenizer, parser, LSP) + `cforge` compiler + `cstd` stdlib.
- **MUI**: `cforge run x.mui` renders a declarative UI live; `cforge -c [-r] x.mui` lowers it to a native Rust crate (`mui-codegen`).
- MUI components: reactive counter, `onKeyInput`, styling/anchors, components + cross-file imports, `app.bundle` assets, and **Video / WebView** (runtime + codegen) with cross-platform video corner `radius`.
- VS Code extension for Copper + MUI, and a MUI-based GUI installer (no Tauri).

**Commits in this release**

- [`99d761c`](https://github.com/liy77/mikasa/commit/99d761c8f02efc987caab8ba98efa498ec79a171) Ship Astra branding, GUI Icon fallbacks, and mikasa format/check.
- [`a836289`](https://github.com/liy77/mikasa/commit/a8362892bf0bee699ba376091126840fa6642bb1) Parse KSON through the LSON toolkit.
- [`c9db951`](https://github.com/liy77/mikasa/commit/c9db95107df01f87a9d0aafbfcc4fe14c084651c) Make examples idiomatic Mikasa and auto-format interpolation args.
- [`972e2f9`](https://github.com/liy77/mikasa/commit/972e2f9f0a7c1a09bfa000f17e07cc88cbae5a5c) Improve auto-borrow and add phantom T markers with run-time hints.
- [`1d8618e`](https://github.com/liy77/mikasa/commit/1d8618e7ff6e9a9c53446c36da2b466c25bb4076) Add Mikasa language features: Codable JSON, actors, async Tokio, and property sugar.
<!-- MIKASA-RELEASE:END -->

---

<div align="center">

## GitHub

<img height="165" src="https://github-readme-stats.vercel.app/api?username=liy77&count_private=true&include_all_commits=true&show_icons=true&theme=dark&hide_border=true&show_owner=true&bg_color=070708&title_color=E10600&text_color=F4F4F5&icon_color=FFFFFF" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=liy77&layout=compact&hide_border=true&bg_color=070708&title_color=E10600&text_color=F4F4F5&langs_count=6" alt="Top languages"/>

<img src="https://github-profile-trophy.vercel.app/?username=liy77&theme=dark&no-frame=true&no-bg=true&column=7&title=Followers,Stars,Commit,Repositories,PullRequest,Issues" alt="GitHub trophies"/>

<img src="https://komarev.com/ghpvc/?username=liy77&style=flat-square&color=E10600&label=profile+views" alt="profile views"/>

Copper is now Mikasa.

</div>
