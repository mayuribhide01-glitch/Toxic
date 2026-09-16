# Toxic Wasteland — Survival

A single-file browser survival shooter built with [three.js](https://threejs.org/) (r128). Fight off waves of monsters in a neon, toxic wasteland — desktop (WASD + mouse) and mobile (touch joystick + tap-to-fire) both supported.

## Play

Just open `index.html` in a browser — no build step, no install. Or enable **GitHub Pages** for this repo (Settings → Pages → deploy from `main`) and play it straight from the hosted link.

## Controls

**Desktop**
- `WASD` — move
- Mouse — look
- Click — attack
- `1–6` / scroll — switch weapons
- `R` — reload

**Mobile**
- Left thumb — move (virtual joystick)
- Drag right side of screen — look
- `FIRE` — attack
- Tap weapon icon — switch
- `RELOAD` — reload

## Tech

- Plain HTML/CSS/JS, no build tooling
- [three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js) loaded via CDN
- Best score persisted with `localStorage`

## Project structure

```
.
├── index.html      # the entire game
├── README.md
├── LICENSE
└── .gitignore
```

## License

MIT — see [LICENSE](LICENSE).
