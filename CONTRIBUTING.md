# 🤝 Contributing to ZIN

Thanks for your interest in contributing to **ZIN** — a minimalist, zero-boilerplate HTML engine. Whether you're here to write code, improve docs, fix typos, or report bugs — you're welcome here.



## 📁 Project Structure

This GitHub organization (`zin-engine`) contains multiple repositories:

- [`core`](https://github.com/zin-engine/core): Main Go-based ZIN engine
- `docs` (coming soon): Official documentation site
- `examples`: Sample projects built with ZIN
- `zin-engine`: Landing zone with overview and philosophy



## 🛠️ How to Contribute

### 1. 🍴 Fork + Clone
Start by forking the relevant repo (usually [`core`](https://github.com/zin-engine/core)), then clone it to your machine:

```bash
git clone https://github.com/your-username/core
cd core
````

### 2. 📦 Install & Set Up (For `core`)

Make sure you have Go installed (`go version`) — ZIN runs on Go.

```bash
go build -o zin main.go
./zin
```

### 3. 🌱 Create a Branch

Always create a new branch for your changes.

```bash
git checkout -b feature/your-feature-name
```



## 🧠 Ways to Contribute

### 🧑‍💻 Code Contributions

* New features (e.g., new `<zin />` tag handlers)
* Bug fixes
* Performance improvements
* Refactors (be mindful!)

### 📚 Docs & Guides

* Fix typos or unclear language
* Improve explanations in `zin-tags.md` or `All-About-Zin.md`
* Submit tutorials or usage examples

### 🪲 Bug Reports / Issues

* File issues in the relevant repo
* Include clear steps to reproduce
* Paste related `<zin />` snippet if possible
* Add your OS, Go version, and any logs

### ❓ Ask Questions / Request Features

* Open a “Discussion” (if enabled)
* Or use Issues with the `[question]` or `[feature-request]` label



## 📐 Coding Style

* Use idiomatic Go (`gofmt` is your friend)
* Avoid external dependencies unless necessary
* Comment where it helps future readers
* Keep feature flags/config optional and minimal



## ✅ Submitting a Pull Request

1. Make sure your branch is up to date with `main`
2. Push your changes:

   ```bash
   git push origin feature/your-feature-name
   ```
3. Go to GitHub and create a Pull Request (PR)
4. Fill out the PR template if available
5. Be patient — we’ll review it with care ❤️



## ❤️ Code of Conduct

ZIN is built by and for indie devs, tinkerers, and curious builders.
Please be respectful, helpful, and constructive in all interactions.
We’re all here to learn and build cool stuff.



## 🧵 Stay in the Loop

We’re working on adding:

* Discussions tab
* Twitter/X updates
* Blog or newsletter (eventually)

For now, keep watching the repos or follow the creator for updates.


**Thanks again for helping ZIN grow!**
Your input means a lot — even a small typo fix helps move things forward 🚀
