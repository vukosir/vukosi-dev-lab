# vukosi-dev

Everything I build, in one place. Sorted by what it is rather than when I made it.

Vukosi Rikhotso, student at The Independent Institute of Education.

## Layout

```
vukosi-dev/
├── README.md
├── web-projects/          Sites and browser apps
├── mobile-projects/       Android and cross-platform apps
├── python-projects/       Scripts, automation, data work
├── ai-projects/           Models, agents, anything ML
├── university-projects/   Coursework and portfolio submissions
└── mini-projects/         Weekend builds and experiments
```

Each folder has its own README explaining what lives there.

## One project per folder

Inside any category, give each project its own folder with its own README:

```
web-projects/
└── currency-converter/
    ├── index.html
    └── README.md
```

That way a project can move between categories without breaking anything, and
anyone browsing the repo can read a project's README without opening its code.

## Live demos

Anything in `web-projects/` that has an `index.html` can be served straight from
GitHub Pages. Turn Pages on for this repo (Settings, then Pages, then deploy
from `main` at root) and each project becomes reachable at:

```
https://YOURUSERNAME.github.io/vukosi-dev/web-projects/PROJECT-NAME/
```

| Project | What it does | Live |
|---|---|---|
| currency-converter | Live rates for 160+ currencies, plus a scientific calculator, equation solver and money tools | *(add link once Pages is on)* |

## Adding a project

1. Make a folder in the right category.
2. Drop the code in.
3. Write a README with what it does, how to run it, and what you learned.
4. Add a row to the table above if it has a live demo.
