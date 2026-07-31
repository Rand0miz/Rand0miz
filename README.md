<!--
  GitHub profile README for @Rand0miz — variant 2 (terminal / phosphor)
  Repo must be named Rand0miz/Rand0miz with this file at the root.
  See SETUP.md before pushing.
-->

<div align="center">
  <img src="assets/boot.svg" width="100%" alt="myles@spruce — boot log" />
</div>

<div align="center">
  <a href="mailto:mylestechbot@gmail.com"><img src="https://img.shields.io/badge/mail-mylestechbot@gmail.com-3fb950?style=flat-square&labelColor=010409&logo=maildotru&logoColor=3fb950" alt="Email" /></a>
  <a href="https://github.com/Rand0miz?tab=repositories"><img src="https://img.shields.io/badge/ls-~%2Frepos-d29922?style=flat-square&labelColor=010409&logo=gnubash&logoColor=d29922" alt="Repositories" /></a>
  <img src="https://img.shields.io/github/followers/Rand0miz?style=flat-square&labelColor=010409&color=768390&logo=github&logoColor=768390&label=followers" alt="Followers" />
  <img src="https://komarev.com/ghpvc/?username=Rand0miz&style=flat-square&color=3fb950&label=uptime+views" alt="Profile views" />
</div>

<br>

```console
$ cat /etc/motd
```

> **Long context is a budgeting problem, not a memory problem.**
> Every token spent on filler is a token not spent on the answer.

<br>

## `$ cat about.md`

I work on **inference-time infrastructure for language models** — the layer sitting between a raw
corpus and the tokens a model actually sees. Concretely: context compilers. Read a document far
larger than the window, score it with the model's own attention, emit only the blocks carrying the
answer, and prove the needle survived.

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Rand0miz/Rand0miz/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Rand0miz/Rand0miz/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/Rand0miz/Rand0miz/output/github-contribution-grid-snake.svg" width="100%" alt="Contribution graph snake animation" />
  </picture>
</div>

<br>

## `$ tree ~/stack`

```console
~/stack
├── models/
│   ├── pytorch ················ training + inference loops
│   ├── transformers ··········· Qwen, Llama, tokenizers, generation
│   ├── cuda ··················· kernels, memory, occupancy
│   └── attention/
│       ├── sdpa ··············· default fast path
│       └── flash ·············· long-sequence regime
├── lang/
│   ├── python ················· 71.4%
│   ├── cuda+cpp ··············· 11.8%
│   ├── rust ··················· 7.9%
│   └── typescript ············· 5.2%
├── infra/
│   ├── docker · linux · git
│   └── github-actions
└── principles/
    ├── measure_compression_AND_recall.md
    ├── a_benchmark_you_cant_reproduce_is_a_screenshot.md
    └── the_baseline_is_not_optional.md

6 directories, 15 files
```

<br>

## `$ git log --stat --author=Rand0miz`

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Rand0miz&hide_border=true&background=010409&stroke=21262d&ring=3fb950&fire=d29922&currStreakLabel=3fb950&currStreakNum=e6edf3&sideNums=e6edf3&sideLabels=768390&dates=768390" alt="Streak" />
</div>

<br>

## `$ ls -la ~/projects`

```console
drwxr-xr-x  spruce    context compiler · 422 KB in, 4 blocks out, needle intact
drwxr-xr-x  Valkyrie     API diven local file storage and retrival solution.
-rw-r--r--  .plan        sub-1% compression without losing the answer span
```

<div align="center">
  <a href="https://github.com/Rand0miz/spruce"><img src="https://img.shields.io/badge/repo-spruce-3fb950?style=flat-square&labelColor=010409&logo=github&logoColor=3fb950" alt="spruce" /></a>
  <img src="https://img.shields.io/github/languages/top/Rand0miz/spruce?style=flat-square&labelColor=010409&color=d29922" alt="spruce top language" />
  <img src="https://img.shields.io/github/stars/Rand0miz/spruce?style=flat-square&labelColor=010409&color=768390" alt="spruce stars" />
  <img src="https://img.shields.io/github/last-commit/Rand0miz/spruce?style=flat-square&labelColor=010409&color=768390&label=last%20push" alt="spruce last commit" />
</div>

<div align="center">
  <a href="https://github.com/Rand0miz/Valkyrie"><img src="https://img.shields.io/badge/repo-Valkyrie-3fb950?style=flat-square&labelColor=010409&logo=github&logoColor=3fb950" alt="Valkyrie" /></a>
  <img src="https://img.shields.io/github/languages/top/Rand0miz/Valkyrie?style=flat-square&labelColor=010409&color=d29922" alt="Valkyrie top language" />
  <img src="https://img.shields.io/github/stars/Rand0miz/Valkyrie?style=flat-square&labelColor=010409&color=768390" alt="Valkyrie stars" />
  <img src="https://img.shields.io/github/last-commit/Rand0miz/Valkyrie?style=flat-square&labelColor=010409&color=768390&label=last%20push" alt="Valkyrie last commit" />
</div>

<br>

## `$ ps aux | grep myles`

```console
PID   STAT  COMMAND
2847  R     spruce --target-compression 0.004 --preserve-answer-span
2848  R     bench --needle-recall --report-baseline
2849  S     read  papers/long-context/*.pdf
2850  S     mail  mylestechbot@gmail.com   # open to inference-infra conversations
```

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=900&color=3FB950&center=true&vCenter=true&width=780&height=36&lines=%24+spruce+--compile+book.txt+--blocks+4;%5B+ok+%5D+compression_fraction+%3D+0.006;%5B+ok+%5D+needle+intact;%24+_" alt="terminal" />
</div>

<div align="center">
  <sub><code>exit 0</code></sub>
</div>
