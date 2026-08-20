<div align="center">

[![Terminal](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=00FF9C&background=0D111700&center=true&vCenter=true&width=700&lines=andre%40github%3A~%24+whoami;andre%40github%3A~%24+cat+experience.log;andre%40github%3A~%24+ls+-la+~%2Fprojects)](https://github.com/aaaranas)

`Andre Milan Arañas` · BS Computer Science @ **University of the Philippines Cebu** · Cebu, PH

[![Portfolio](https://img.shields.io/badge/portfolio-andre--milan--aranas.vercel.app-00FF9C?style=flat-square&logo=vercel&logoColor=black&labelColor=0D1117)](https://andre-milan-aranas.vercel.app/)
[![Email](https://img.shields.io/badge/mail-aaaranas%40up.edu.ph-00FF9C?style=flat-square&logo=gmail&logoColor=black&labelColor=0D1117)](mailto:aaaranas@up.edu.ph)
[![Status](https://img.shields.io/badge/status-not%20seeking%20internships-777777?style=flat-square&labelColor=0D1117)](#)

</div>

---

```console
andre@github:~$ whoami

  Andre Milan Arañas — frontend-leaning full-stack developer.

  I build across the stack, from bare-metal OS kernels in C and Assembly
  to local-first PWAs in Next.js. Most of what I ship is aimed at a real
  gap in the Philippines: transit routing where Google has no coverage,
  curriculum tracking for irregular students, sanitation mapping in Cebu.

  I care about the parts users never see — pure functions for anything
  scored or graded, tests where correctness is invisible to the eye,
  and capability checks instead of assumptions.

  Expected graduation ......... July 2027
  Location .................... Cebu, Central Visayas, Philippines
  Currently ................... Head of Technology @ Accelokal
                                Front-End AI Engineering Intern @ FlyRank AI
```

---

```console
andre@github:~$ cat experience.log --reverse

[2026-08 → present]  Head of Technology · Accelokal
                     Part-time · Cebu, Central Visayas · Remote

[2026-07 → present]  Front-End AI Engineering Intern · FlyRank AI
                     Internship · Front-end AI engineering

[2026-06 → 2026-08]  Web Developer Intern · eComia
                     Completed

andre@github:~$ echo $OPEN_TO_INTERNSHIPS
false   # not actively seeking — open to interesting conversations
```

---

```console
andre@github:~$ ls -la ~/projects

drwxr-xr-x  pitik            TypeScript  2026-08  local-first camera + photobooth PWA
drwxr-xr-x  frag-avenue      TypeScript  2026-08  explainable fragrance analytics
drwxr-xr-x  andre-portfolio  TypeScript  2026-07  personal developer portfolio
drwxr-xr-x  san-bidet-cebu   Dart        2026-06  crowdsourced bidet map for Cebu
drwxr-xr-x  komyut-ta-bai    TypeScript  2026-06  multimodal transport planner
drwxr-xr-x  irregskolar      JavaScript  2026-06  curriculum tracker for irregulars
drwxr-xr-x  DugOS            C / ASM     2026-05  bare-metal 32-bit operating system

total 7 public repositories
```

### `$ cat ~/projects/*/README.md --brief`

| Project | What it is | Stack |
|---|---|---|
| **[pitik](https://github.com/aaaranas/pitik)** · [live](https://pitik-orcin.vercel.app) | A nostalgic digital camera and photobooth in the browser. 37 data-driven film presets rendered twice — CSS for live preview, per-pixel canvas for export — with the tone curve baked into LUTs so a 12MP export stays fast. Booth sessions record a real speed-up clip via a WebAudio re-encode. Local-first: IndexedDB owns every photo, sync is opt-in and additive with three tested merge invariants. 207 unit + 24 Playwright tests. | Next.js · TypeScript · IndexedDB · Canvas · PWA · Supabase |
| **[frag-avenue](https://github.com/aaaranas/frag-avenue)** · [live](https://frag-avenue.vercel.app) | A fragrance wardrobe that turns longitudinal wear data into *explainable* recommendations — every score decomposed into named reasons from real numbers, no LLM narration. Modular monolith with framework-free scoring: no React, Next, or Prisma imports in the analytics layer. 242 unit + 37 Playwright tests, CI with a Postgres service container. | Next.js 15 · React 19 · Prisma · PostgreSQL · Auth.js v5 · Zod |
| **[komyut-ta-bai](https://github.com/aaaranas/komyut-ta-bai)** · [live](https://komyut-ta-bai.vercel.app) | *Asa ta, Bai?* — province-wide transit routing for Cebu, where Google has zero coverage. Dijkstra over an in-memory graph of buses, v-hires, jeepneys, and ferries, returning multi-leg plans with transfers, fare, and duration. Entirely client-side, offline-capable, with a validation pass over the dataset and unverified scraped routes flagged in the UI. | Next.js 16 · TypeScript · MapLibre GL · Serwist · Dijkstra |
| **[irregskolar](https://github.com/aaaranas/irregskolar)** · [live](https://irregskolar.vercel.app) | Upload your study-plan PDF, mark what you passed, and see what you can enroll in next — ranked by how many subjects each one unlocks. Interactive prerequisite graph, semester planner, GPA calculator, per-student isolation via Supabase RLS. | React · Vite · Supabase · React Flow · pdf.js |
| **[san-bidet-cebu](https://github.com/aaaranas/san-bidet-cebu)** · [admin](https://san-bidet-cebu-admin.vercel.app) | Crowdsourcing clean bidets across Cebu. Proximity-sorted map, four-category ratings, photo uploads, and a moderation workflow so nothing hits the map unreviewed. GIS export for anyone studying sanitation infrastructure. Ships to iOS, Android, web, and desktop from one codebase. | Flutter · Dart · Supabase · flutter_map · go_router |
| **[DugOS](https://github.com/aaaranas/DugOS)** | A freestanding 32-bit OS — no host operating system underneath. Boots via GRUB 2 in QEMU, sets up its own GDT/IDT, remaps the 8259A PIC, and follows the MINIX 3.1.0 kernel boot sequence. PS/2 keyboard driver on IRQ1, in-memory FAT file system with linked allocation, and an interactive shell with file and directory commands. Team project for CMSC 125. | C (freestanding) · NASM · GRUB 2 · QEMU · Make |
| **[andre-portfolio](https://github.com/aaaranas/andre-portfolio)** · [live](https://andre-milan-aranas.vercel.app/) | My portfolio — live repos pulled from the GitHub API, dark/light mode persisted to localStorage, scroll animations via IntersectionObserver, custom blend-mode cursor. | Next.js 16 · TypeScript · Tailwind CSS 4 |

---

```console
andre@github:~$ tree ~/.stack -L 2

~/.stack
├── frontend/
│   ├── TypeScript · JavaScript
│   ├── React · Next.js (App Router) · React 19
│   ├── Tailwind CSS · CSS custom properties
│   ├── Flutter · Dart
│   └── PWA · service workers · Canvas · MapLibre GL
├── backend/
│   ├── Node.js · Next server actions · Express
│   ├── PostgreSQL · Supabase (Auth + RLS + Storage)
│   ├── Prisma · Auth.js v5 · Zod
│   └── IndexedDB · offline-first sync
├── systems/
│   ├── C (freestanding, no libc)
│   ├── NASM x86 · i386 protected mode
│   └── GRUB 2 · QEMU · GNU Make
└── tooling/
    ├── Git · GitHub Actions
    ├── Vitest · Playwright
    ├── Docker · Vercel
    └── Linux · WSL2 · pnpm
```

---

```console
andre@github:~$ curl -s andre.contact | jq

{
  "email":     "aaaranas@up.edu.ph",
  "portfolio": "https://andre-milan-aranas.vercel.app",
  "github":    "https://github.com/aaaranas",
  "location":  "Cebu, Philippines",
  "open_to":   ["collaboration", "open source", "good conversations"]
}

andre@github:~$ exit
```
