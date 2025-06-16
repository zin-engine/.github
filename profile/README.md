
```
 ________  ___  ________      
|\_____  \|\  \|\   ___  \    
 \|___/  /\ \  \ \  \\ \  \   
     /  / /\ \  \ \  \\ \  \  
    /  /_/__\ \  \ \  \\ \  \ 
   |\________\ \__\ \__\\ \__\
    \|_______|\|__|\|__| \|__|

```

**ZIN** – Zone-based Interactive Notation.
*Make static HTML dynamic without frameworks or boilerplate.*

### 🧠 What is ZIN?

**ZIN is a minimal templating engine and file server** that lets you build dynamic-feeling websites using only `.html` files and custom `<zin ... />` tags.

No frameworks, no npm installs, no bundling — just plain HTML with a little power added by the **ZIN engine** (written in Go).

### ⚙️ Key Features

- Use `.html` files as your only source of truth
- Add dynamic data with custom `<zin>` tags
- Render from JSON, CSV, `.txt`, MySQL or Google Sheets
- File-based includes and loops with `<zin ForEach />`, `<zin Map />`, etc.
- Optional templating like `template.html`
- Smart 404/500 handling, `.env` support, and `.zinignore` equivalent
- Zero-client exposure — all rendering is server-side
- Runs on port 9001 by default — just point NGINX or your browser


### 🛠️ Repos in This Org

| Repo                                         | Description                                                     |
| -------------------------------------------- | --------------------------------------------------------------- |
| [`core`](https://github.com/zin-engine/core) | The Go source code for the ZIN engine. Compiles into `zin.exe`. |
| `docs` (coming soon)                         | Usage, tag reference, guides, and CLI help.                     |
| `examples` (coming soon)                     | Sample projects built using ZIN.                                |
| `templates` (optional)                       | Starter templates or site skeletons.                            |


### 💻 Why Use ZIN?

* You're tired of spinning up React/Vue/Svelte just to show a list.
* You want to keep things in `.html` but still use loops, includes, or data.
* You love minimal tools that *just work* without config hell.
* You want static output with server-rendered power — like a mini Next.js, but with zero overhead.

### 📦 Install & Get Started

Check installation guides for your OS:

* [🪟 ZIN on Windows](guide/zin-on-windows.md)
* [🐧 ZIN on Ubuntu/Linux](guide/zin-on-ubuntu.md)
* [🍎 ZIN on macOS](guide/zin-on-macos.md)

### 🧩 Learn the Tags

Full tag reference coming soon at:
📄 `zin-tags.md`

Includes everything from:

* `<zin time />`
* `<zin include />`
* `<zin forEach />`
* `<zin readFile />`
* `<zin mysql />`
* `<zin gviz />`
* and more...


### 🤘 Behind-the-Scenes: How ZIN Happened

> *This project started as a personal tool for building static sites without the bloat of modern frameworks. Just serve `.html`, inject a few dynamic values like time and data, and go.
> What began as “Bro Code” turned into ZIN — a fully capable engine with support for real-time data, templating, and powerful rendering.
> Now it’s open-source, growing, and made to be hacked on.*
> → [Read the full dev story](All-About-Zin.md)


### 🤝 Contribute

Pull requests welcome!
Check out [`CONTRIBUTING.md`](CONTRIBUTING.md) to get started.


### 📄 License

MIT — do what you want. Just don’t make something evil.


> Zin is not a framework.
> It’s **your old-school HTML**, just... smarter.
