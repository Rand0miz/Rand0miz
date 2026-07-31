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
  <img height="165" src="https://rand0miz-readme-stats.vercel.app/api?username=Rand0miz&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=010409&title_color=3fb950&icon_color=d29922&text_color=adbac7&ring_color=3fb950&custom_title=git%20log%20--stat" alt="GitHub stats" />
  <img height="165" src="https://rand0miz-readme-stats.vercel.app/api/top-langs/?username=Rand0miz&layout=compact&langs_count=8&hide_border=true&bg_color=010409&title_color=3fb950&text_color=adbac7&custom_title=cloc%20~%2F" alt="Top languages" />
</div>

<div align="center">
  <img src="https://rand0miz-profile-trophy.vercel.app/?username=Rand0miz&theme=matrix&no-frame=true&no-bg=true&column=7&margin-w=6&margin-h=6" alt="Trophies" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Rand0miz&hide_border=true&background=010409&stroke=21262d&ring=3fb950&fire=d29922&currStreakLabel=3fb950&currStreakNum=e6edf3&sideNums=e6edf3&sideLabels=768390&dates=768390" alt="Streak" />
</div>

<br>

## `$ ls -la ~/projects`

```console
drwxr-xr-x  sprucekit    context compiler · 422 KB in, 4 blocks out, needle intact
drwxr-xr-x  Valkyrie     API diven local file storage and retrival solution.
-rw-r--r--  .plan        sub-1% compression without losing the answer span
```

<div align="center">
  <a href="https://github.com/Rand0miz/sprucekit">
    <img src="https://rand0miz-readme-stats.vercel.app/api/pin/?username=Rand0miz&repo=sprucekit&hide_border=true&bg_color=010409&title_color=3fb950&icon_color=d29922&text_color=adbac7" alt="sprucekit" />
  </a>
  <a href="https://github.com/Rand0miz/Valkyrie">
    <img src="https://rand0miz-readme-stats.vercel.app/api/pin/?username=Rand0miz&repo=Valkyrie&hide_border=true&bg_color=010409&title_color=3fb950&icon_color=d29922&text_color=adbac7" alt="Valkyrie" />
  </a>
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
