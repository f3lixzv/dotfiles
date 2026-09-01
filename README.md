# f3lixzv/dotfiles

> Personal Arch Linux configuration managed with GNU Stow.

![Desktop](assets/dotfiles.png)

---

### Environment

| Component     | Software          |
| ------------- | ----------------- |
| OS            | Arch Linux        |
| WM            | Niri              |
| Shell         | Bash + Starship   |
| Desktop shell | DankMaterialShell |
| Terminal      | Kitty             |
| Fetch         | Fastfetch         |
| Monitor       | btop              |
| Visualizer    | Cava              |
| Discord       | Vesktop           |
| Qt            | qt6ct             |

### Packages

```text
btop        cava        dms
fastfetch   gtk3        gtk4
kitty       niri        qt6ct
starship    vesktop
```

### Installation

```bash
git clone git@github.com:f3lixzv/dotfiles.git ~/dotfiles
cd ~/dotfiles
stow */
```

### Updating

Changes made through `~/.config` are reflected directly in this repository through Stow.

```bash
cd ~/dotfiles
git add .
git commit -m "Update dotfiles"
git push
```

---

<sub>Arch Linux · Niri · GNU Stow</sub>
