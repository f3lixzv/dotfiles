# 🏠 My Dotfiles

My personal Arch Linux configuration managed with **GNU Stow**.

Built around a minimal Wayland desktop with **Niri** and **DankMaterialShell**.

## ✨ What's Included

| Package             | Description                          |
| ------------------- | ------------------------------------ |
| `niri`              | Niri compositor configuration        |
| `DankMaterialShell` | DankMaterialShell configuration      |
| `kitty`             | Kitty terminal configuration & theme |
| `fastfetch`         | Fastfetch configuration              |
| `btop`              | btop configuration & theme           |
| `cava`              | Cava visualizer configuration        |
| `qt6ct`             | Qt6 configuration & theme            |
| `gtk-3.0`           | GTK 3 theme configuration            |
| `gtk-4.0`           | GTK 4 theme configuration            |
| `vesktop`           | Vesktop Discord theme                |

## 📦 Installation

Clone the repository:

```bash
git clone git@github.com:f3lixzv/dotfiles.git ~/dotfiles
cd ~/dotfiles
```

Install GNU Stow:

```bash
sudo pacman -S stow
```

Then stow the configurations:

```bash
stow */
```

That's it. The configurations will be symlinked into `~/.config`.

## 🔄 Updating

After changing a configuration:

```bash
cd ~/dotfiles
git add .
git commit -m "Update configs"
git push
```

## 🖥️ Setup

* **OS:** Arch Linux
* **Compositor:** Niri
* **Shell:** DankMaterialShell
* **Terminal:** Kitty
* **Visualizer:** Cava
* **System monitor:** btop
* **Fetch:** Fastfetch
* **Discord client:** Vesktop
* **Config management:** GNU Stow

---

*Personal configuration files for my Arch Linux setup.*
