# Hold Your Colour

Hold Your Colour is a **top-down action roguelike** game with **deckbuilding mechanics**, developed by **Afrokarp** as part of **UNGames**. This project aims to deliver a dynamic and challenging experience, blending strategy and action in a vibrant setting.

---

## Table of Contents

1. [About the Project](#about-the-project)  
2. [Project Structure](#project-structure)  
3. [Conventions](#conventions)  
4. [Contributing Guidelines](#contributing-guidelines)  
5. [License](#license)  
6. [Español - Sobre el Proyecto](#español---sobre-el-proyecto)  

---

## About the Project

**Game Type:** Top-Down Action Roguelike with Deckbuilding  
**Status:** In Development  
**Lead Developer:** Afrokarp  
**Collaborators:** UNGames Team  
**Platform:** Cross-platform (PC, possibly mobile support)  
**Engine:** [Godot Engine](https://godotengine.org/)  

---

## Project Structure

The project is organized into clear directories to facilitate navigation and collaboration. The structure is functional, grouping elements based on their role in the game.  

```plaintext
HoldYourColour/
├── addons/                # Plugins and additional tools
├── Assets/                # General project resources (music, fonts, etc.)
├── Common/                # Reusable logic and resources
├── Config/                # Player preferences and settings
├── Entities/              # Interactive elements (player, enemies, UI, etc.)
├── Localization/          # Translation files (future)
├── Stages/                # Game stages and areas
├── Utilities/             # Helpers and managers
├── Localization/          # Translation files (future)
├── Stages/                # Game stages and areas
└── Utilities/             # Helpers and managers
```
## Conventions
# Directory Naming

    - PascalCase for all directories except addons.
        Example: Assets, Entities, Stages.

# File Naming

    - Scripts (.gd): Use snake_case for clarity, adding specific roles in names where applicable.
        Example: player_controller.gd, enemy_ai.gd.

    - Scenes (.tscn): Use snake_case, ensuring names reflect the purpose or role of the scene.
        Example: main_menu.tscn, level_01.tscn.

    - External Assets (audio, images, etc.): Use snake_case and include suffixes to describe their type:
        - Audio Files:
            Use suffixes like _bgm for background music, _sfx for sound effects, _vo for voice-over.
            Example: battle_theme_bgm.mp3, explosion_sfx.wav.
        - Image Files:
            Use suffixes like _icon, _bg, _sprite for specific roles.
            Example: button_icon.png, menu_bg.jpg, player_sprite.png.
        - Fonts and Text Files:
            Add _font or _txt for distinction.
            Example: game_font.ttf, credits_txt.txt.

# General Rules for All Files

    Self-Descriptive Naming: Every file name should clearly indicate its purpose or function.
    Consistent Prefixes or Suffixes: Add identifiers like player, enemy, or menu to make files easily searchable.

## Contributing Guidelines
# Requirements

    Install Godot Engine (recommended version: 4.3).
    Clone the repository:

    git clone <repo-url>
    cd HoldYourColour

# Getting Started

    Open the project in Godot:
        Run godot and select the Project.godot file.
    Familiarize yourself with the directory structure.
    Check the repository issues for tasks you can contribute to.

# Contributions

    Follow the conventions listed above.
    Place global scripts or helpers in the Utilities/ directory.

## License

This project is licensed under the MIT License. Feel free to use the code and assets, but please credit the Hold Your Colour team.
#### Español - Sobre el Proyecto

Hold Your Colour es un juego de acción roguelike con perspectiva top-down y mecánicas de deckbuilding. Desarrollado por Afrokarp como parte de UNGames, este proyecto busca ofrecer una experiencia dinámica y desafiante, combinando estrategia y acción en un entorno vibrante.
## Estructura del Proyecto

El proyecto está organizado en directorios claros para facilitar la navegación y colaboración. La estructura agrupa elementos según su función en el juego.

```plaintext
HoldYourColour/
├── addons/                # Plugins y herramientas adicionales
├── Assets/                # Recursos generales del proyecto (música, fuentes, etc.)
├── Common/                # Lógica y recursos reutilizables
├── Config/                # Configuración y datos del jugador
├── Entities/              # Elementos interactivos (jugador, enemigos, UI, etc.)
├── Localization/          # Archivos de idiomas (futuro)
├── Stages/                # Áreas y entornos del juego
└── Utilities/             # Scripts de ayuda y managers
```

## Convenciones de Nombres
# Archivos de Activos Externos (audio, imágenes, etc.)

    - Usa snake_case y agrega sufijos para describir su tipo:
        - Audio: _bgm, _sfx, _vo.
        - Imágenes: _icon, _bg, _sprite.
        - Fuentes o Textos: _font, _txt.

## Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usar el código y los recursos, pero considera dar crédito al equipo de Hold Your Colour.
