<h1 align="center">
  <img src="https://raw.githubusercontent.com/athxrvx/Velocity-Mono/refs/heads/main/velocity-title.png" alt="Velocity Title" width="480">
</h1>

<p align="center"><i>
  Made for all-nighters.<br>
  Best works with monochrome or muted color schemes.
</i></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/athxrvx/Velocity-Mono/refs/heads/main/velocity-showcase.png" alt="Font Showcase" width="800">
</p>


## 📄 About

This repository contains only a custom [`private-build-plans.toml`](./private-build-plans.toml) file used to generate a personalized build of [Iosevka](https://github.com/be5invis/Iosevka) — a highly customizable and elegant monospace typeface.


## ⚙️ How to Build This Font

> You’ll be cloning the **official Iosevka repo**, dropping in this config, and building your own fonts locally.

### Step 1: Clone the Iosevka repo

```bas
git clone https://github.com/be5invis/Iosevka.git
cd Iosevka
````

### Step 2: Copy this custom build plan

```bash
curl -O https://raw.githubusercontent.com/athxrvx/velocity-mono/main/private-build-plans.toml
```

You can also download it manually and place it in the root of the Iosevka folder.

### Step 3: Install dependencies

```bash
npm install
```

### Step 4: Build the font

```bash
npm run build -- ttf::Velocity
```
