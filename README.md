# INRAE R-universe registry

[![name status badge](https://inrae.r-universe.dev/badges/:name)](https://inrae.r-universe.dev/)
[![registry status badge](https://inrae.r-universe.dev/badges/:registry)](https://inrae.r-universe.dev/)
[![packages status badge](https://inrae.r-universe.dev/badges/:packages)](https://inrae.r-universe.dev/packages)
[![articles status badge](https://inrae.r-universe.dev/badges/:articles)](https://inrae.r-universe.dev/articles)
[![datasets status badge](https://inrae.r-universe.dev/badges/:datasets)](https://inrae.r-universe.dev/datasets)

This repository defines the **registry of R packages published on the INRAE r-universe**  
👉 https://inrae.r-universe.dev

The r-universe provides automated building, hosting, and distribution of R packages
developed or maintained by **INRAE staff**, making them easily installable and discoverable
by the R community.

This repository does **not** contain package source code.  
It only lists the packages to be indexed and built by r-universe.

---

## 📦 What is included here?

- A single `packages.json` file defining:
  - package repositories to track
  - their source locations (GitHub, forge.inrae.fr, or any public Git repository)
- Minimal configuration required by **r-universe registries**

See r-universe documentation for details:  
https://docs.r-universe.dev/publish/set-up.html#registry-file

---

## ➕ How to add a package

Packages published on this r-universe must:

- Be **developed or maintained by INRAE staff**
- Be available in a **public Git repository**
  - GitHub
  - https://forge.inrae.fr
  - or any other publicly accessible Git repository
- Follow **r-universe recommendations** (valid DESCRIPTION, versioning, dependencies, etc.)

### Option 1 — Create an issue (recommended)

Open an issue in this repository and provide:

- Package name
- Repository URL
- Short description
- Confirmation of INRAE involvement

An administrator will review and add it if eligible.

### Option 2 — Submit a pull request

1. Fork this repository
2. Edit the `packages.json` file
3. Add your package following the existing structure
4. Open a pull request with a short justification

---

## 🏛️ Governance and scope

This r-universe is **reserved for INRAE staff projects** and follows the general rules of
the INRAE GitHub organization:

- Institutional relevance (INRAE-led or co-led)
- Proper licensing and documentation

---

## 📬 Questions or support

If you are unsure whether your package is eligible, or need help:

- Open an issue in this repository
- Or contact one of the INRAE GitHub organization administrators

---

## 📜 License

This repository only contains configuration files and metadata.  
See individual packages for their respective licenses.
