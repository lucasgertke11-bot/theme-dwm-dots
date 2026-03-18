# DistroForge - DWM Dots Themes

Repositório de temas DWM (dwm-dots) para integração com o instalador Calamares do projeto DistroForge.

## Temas Inclusos

- dwm-dots

## Estrutura

```
/
├── themes/           # Arquivos dos temas DWM
├── previews/        # Imagens de preview
├── scripts/         # Scripts de instalação
```

## Instalação via Calamares

```bash
sudo ./scripts/[distro]/dwm-dots.sh
```

## Instalação Manual

```bash
git clone https://github.com/lucasgertke11-bot/theme-dwm-dots.git
cd theme-dwm-dots
sudo ./scripts/[distro]/dwm-dots.sh
```

## Dependências

Os scripts instalam automaticamente:
- dwm, dmenu
- st, picom
- rofi, feh
- nitrogen
- Nerd Fonts

## Distros Suportadas

Arch Linux, Ubuntu, Fedora, OpenSUSE, Gentoo

---
DistroForge 2026