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
<a href="https://github.com/liy77/mikasa/releases/tag/nightly-2026-11-23">
<img src="https://img.shields.io/badge/latest-nightly--2026--11--23-111111?style=for-the-badge" alt="Latest release nightly-2026-11-23"/>
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
### [nightly-2026-11-23](https://github.com/liy77/mikasa/releases/tag/nightly-2026-11-23)

<sub>Published 2026-11-23</sub>

**Release notes**

- `mikasa-*` — toolchain CLI (transpile / run / update / vm)
- `cforge-*` — legacy alias of `mikasa` (same binary)
- `astra-*` — Astra interpreter (instant `.mika` run)
- `mikasa-lsp-*` — language server
- **Linux x86_64** — `*-linux-x86_64`
- **Windows x86_64** — `*-windows-x86_64.exe`

**Commits in this release**

- [`eeaeb1a`](https://github.com/liy77/mikasa/commit/eeaeb1a1fe41aafedf4d715897fa3c552682d7eb) Ship a full cross-platform nightly SDK in the Release workflow.
- [`a8b73fa`](https://github.com/liy77/mikasa/commit/a8b73fa248b60bc6cd7e51f813e3a9a5e576e3d2) Fix the test runner to rebuild Astra and refresh README examples.
- [`079f9df`](https://github.com/liy77/mikasa/commit/079f9df0ebcda26f8db356db7003463a649d0fed) Add Mikasa language test suite and a single runner.
- [`e0c93ae`](https://github.com/liy77/mikasa/commit/e0c93ae8cdddd5ebfedd4c8b1fb430f086f75f32) Ship Mikasa file imports, Astra wasm ergonomics, and split TODOs.
- [`f8f4050`](https://github.com/liy77/mikasa/commit/f8f4050b6225123ae88fbf6a6fdd1446e8e76192) Warn about deprecated names in the editor, not only at run time.
- [`644f589`](https://github.com/liy77/mikasa/commit/644f589eb76970a146b63eb915e459e1a748707b) Rename examples/copper to examples/mikasa and translate the Portuguese.
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
