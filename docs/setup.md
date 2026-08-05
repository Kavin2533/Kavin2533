# 🚀 Setup & Deployment Guide

> **Premium GitHub Portfolio** by Kavin G ([@Kavin2533](https://github.com/Kavin2533))

---

## 📋 Prerequisites

- A GitHub account with username `Kavin2533`
- A **special repository** named exactly the same as your username: `Kavin2533/Kavin2533`
- Git installed locally

---

## 🗂️ Project Structure

```
Kavin2533/
├── README.md                          ← Main profile README
├── assets/
│   ├── hero.svg                       ← Aurora hero banner
│   ├── footer.svg                     ← Animated wave footer
│   ├── id-card.svg                    ← Developer ID badge
│   ├── orbit.svg                      ← Tech orbit animation
│   ├── avatar-frame.svg               ← Glowing avatar frame
│   ├── divider-1.svg                  ← Aurora divider
│   ├── divider-2.svg                  ← Liquid wave divider
│   ├── divider-3.svg                  ← Gradient bar divider
│   ├── divider-4.svg                  ← Glassmorphism divider
│   ├── divider-5.svg                  ← Neon glow divider
│   ├── background.svg                 ← Dot grid background
│   └── logo.svg                       ← KG personal logo
├── .github/
│   └── workflows/
│       └── snake.yml                  ← Snake animation workflow
└── docs/
    └── setup.md                       ← This file
```

---

## ⚡ Quick Start

### Step 1 — Create the Profile Repository

1. Go to **GitHub → New Repository**
2. Set **Repository name** to exactly: `Kavin2533`
3. Set it to **Public**
4. **Do NOT** initialize with README (you'll push yours)
5. Click **Create repository**

### Step 2 — Push Your Files

```bash
# Clone or initialize
git init
git remote add origin https://github.com/Kavin2533/Kavin2533.git

# Add all files
git add .
git commit -m "✨ feat: launch premium GitHub portfolio"
git push -u origin main
```

### Step 3 — Enable GitHub Actions (Snake Animation)

1. Go to your repository → **Settings → Actions → General**
2. Under **Workflow permissions**, select **Read and write permissions**
3. Click **Save**
4. Go to **Actions** tab → find **Generate Snake Animation**
5. Click **Run workflow** → **Run workflow** (manual trigger)

After the workflow runs successfully, a new branch called `output` will be created containing the `github-contribution-grid-snake.svg` and `github-contribution-grid-snake-dark.svg` files.

> **Note:** The snake animation in README.md references:
> `https://raw.githubusercontent.com/Kavin2533/Kavin2533/output/github-contribution-grid-snake-dark.svg`
> This URL will be valid once the workflow runs at least once.

---

## 🎨 Customization Guide

### Changing Colors

The portfolio uses an **Aurora Dark** color palette:

| Token | Hex | Usage |
|-------|-----|-------|
| `#8B5CF6` | Purple | Primary accent, gradients |
| `#6366F1` | Indigo | Secondary accent |
| `#38BDF8` | Sky Blue | Tertiary accent |
| `#34D399` | Emerald | Success, neon accents |
| `#F472B6` | Pink | Warm accent |
| `#0D1117` | Near-black | Background |
| `#161B22` | Dark gray | Card backgrounds |

To change colors, use Find & Replace in your editor:
- Replace `#8B5CF6` with your new primary color across all SVG and README files.

### Updating Personal Info

In `README.md`, update these values:
- `Kavin2533` → your GitHub username
- `Kavin G` → your full name
- Location, role, social links, project names

### Adding/Removing Tech Stack Badges

Badges are generated via [Shields.io](https://shields.io/). Format:
```
https://img.shields.io/badge/LABEL-COLOR?style=for-the-badge&logo=LOGO&logoColor=white
```

Find available logo names at [Simple Icons](https://simpleicons.org/).

---

## 🐍 Snake Animation Troubleshooting

| Issue | Fix |
|-------|-----|
| Snake not showing | Run workflow manually, wait for `output` branch to appear |
| Workflow fails | Check **Settings → Actions → Workflow permissions** → enable write access |
| Image not loading | Wait 1–2 min after workflow; GitHub caches raw file URLs |
| Snake shows wrong user | Verify `GITHUB_TOKEN` is set and `github.repository_owner` is correct |

---

## 📊 GitHub Stats Cards

The stats cards (README.md) use [github-readme-stats](https://github.com/anuraghazra/github-readme-stats).

They work automatically — no setup required. If you see errors, try refreshing a few minutes later (the service has rate limits).

To customize themes, change `&theme=tokyonight` to any supported theme:
- `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`

---

## ✅ Launch Checklist

- [ ] Repository created as `Kavin2533/Kavin2533` (exact username match)
- [ ] Repository is **Public**
- [ ] All files pushed to `main` branch
- [ ] GitHub Actions workflow permissions set to **Read and write**
- [ ] Snake workflow triggered manually at least once
- [ ] `output` branch created with snake SVGs
- [ ] Profile README rendering correctly at `github.com/Kavin2533`

---

## 🔗 Resources

- [GitHub Profile README Guide](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [Shields.io Badge Generator](https://shields.io/)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [Platane/snk — Snake Animation](https://github.com/Platane/snk)
- [Simple Icons](https://simpleicons.org/)

---

<div align="center">
  <sub>Made with ❤️ · Premium Dark Aurora Theme · © 2026 Kavin G</sub>
</div>
