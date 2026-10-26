<div align="center">

<img src="https://github.com/lilidoxdev/lilidoxdev/raw/main/assets/banner.png" alt="Lilidox" width="100%">

# Lilidox

**Je construis des interfaces Windows qui ne ressemblent pas à Windows.**

[![Qt](https://img.shields.io/badge/Qt%20Quick-6.10-d6405e?style=flat-square)](#)
[![.NET](https://img.shields.io/badge/.NET-8-3b4252?style=flat-square)](#)
[![Python](https://img.shields.io/badge/Python-3.12-3b4252?style=flat-square)](#)
[![Windows](https://img.shields.io/badge/Windows-11-3b4252?style=flat-square)](#)

</div>

---

## En ce moment

### Winlestia — un shell Windows, pas un thème

Winlestia remplace la surface de Windows : un dock en bas, un tableau de bord au centre,
des panneaux de verre collés aux bords, et une palette Material You recalculée depuis le
fond d'écran. L'interface vient de [Caelestia](https://github.com/caelestia-dots/shell),
un shell Hyprland en QML ; le travail consiste à la faire tourner sur Windows sans la
trahir.

| | |
|---|---|
| **Frontend** | Qt Quick 6.10 / PySide6, QML hérité de Caelestia |
| **Backend** | C# 12, .NET 8, WPF + WinForms, flou DWM natif en C++ |
| **État** | 9.3.0, développement actif, dépôt privé pour l'instant |
| **Installation** | un setup autonome (runtime, Qt et Python embarqués) |

Ce que ça couvre : tableau de bord (météo, calendrier, médias, performances), dock
remplaçant la barre des tâches, espaces d'applications, commande rapide, centre de
contrôle, mélangeur audio, capture annotée avec reconnaissance de texte, presse-papiers
visuel et minuteur de focus.

---

## Ce que je fais

| Domaine | Ce que ça donne |
|---|---|
| **Shell et interfaces système** | Fenêtres sans cadre, verre réel, arrondis cohérents, transitions interruptibles |
| **Outils desktop** | Capture, presse-papiers, audio, télémétrie matérielle — des choses qui restent locales |
| **Automatisation** | Scripts et bots qui relient les services entre eux, sans surveillance constante |
| **Design d'interface** | Typographie, mouvement et matière traités comme du code, pas comme une décoration |

---

## Méthode

Je travaille par itérations courtes et vérifiées : une hypothèse, une mesure, une capture
d'écran, puis la suivante. Chaque version livrée est accompagnée de sa preuve — ce qui a
été testé, ce qui ne l'a pas été, et ce qui reste fragile. Une interface qui a l'air finie
mais qui casse au deuxième écran ne m'intéresse pas.

L'IA fait partie de la chaîne de fabrication : elle écrit, je tranche, et le résultat est
jugé à l'écran.

---

## Stack

```
Langages      C# · Python · QML · PowerShell · C++
Frameworks    .NET 8 (WPF, WinForms) · Qt Quick 6 · PySide6
Système       DWM, Win32, MPRIS, named pipes, capture d'écran, audio WASAPI
Outils        Git · Inno Setup · MSVC · Visual Studio Code
```

---

<div align="center">

*Un bureau à la fois.*

</div>
