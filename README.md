<h1 align="center">HOLD YOUR COLOUR</h1>
Hold Your Colour is a <strong>top-down action roguelike</strong> game with <strong>deckbuilding mechanics</strong>. This project aims to deliver a dynamic and challenging experience, blending strategy and action in a vibrant setting.

---

## Table of Contents

1. [About the Project](#about-the-project)  
2. [Project Structure](#project-structure)  
3. [Conventions](#conventions)  
4. [Contributing Guidelines](#contributing-guidelines)  
5. [License](#license)  
6. [Español - Sobre el Proyecto](#español)  

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
# Conventions
## Directory Naming

    - PascalCase for all directories except addons.
        Example: Assets, Entities, Stages.

### Prefix System for File Organization

Use the prefix system `pre_{name}.{extension}`, where the prefix denotes the file's intended use. Ensure that the prefix and the file extension do not repeat.

#### 1. **Scripts (`.gd`)**
- **Prefix**: `ctl_` (controller), `mgr_` (manager), `sys_` (general system).
  - **Example**: 
    - `ctl_player.gd` (player controller).
    - `mgr_game.gd` (game manager).
    - `sys_audio.gd` (audio system).

#### 2. **Scenes (`.tscn`)**
- **Prefix**: `lvl_` (levels), `ui_` (user interface), `scn_` (generic scene).
  - **Example**: 
    - `lvl_forest.tscn` (forest level scene).
    - `ui_main_menu.tscn` (main menu scene).

#### 3. **Audio Files**
- **Prefix**: Based on the audio's purpose.
  - **`sfx_`**: For short sound effects.
    - Example: `sfx_explosion.wav`, `sfx_jump.ogg`.
  - **`bgm_`**: For background music or long loops.
    - Example: `bgm_battle_theme.mp3`, `bgm_menu_loop.ogg`.
  - **`vo_`**: For voice-overs or narration.
    - Example: `vo_intro.wav`, `vo_character1.ogg`.

#### 4. **Image Files**
- **Prefix**: Based on usage in UI, backgrounds, or sprites.
  - **`ui_`**: User interface elements.
    - Example: `ui_button.png`, `ui_cursor.png`.
  - **`bg_`**: Backgrounds.
    - Example: `bg_forest.png`, `bg_space.jpg`.
  - **`spr_`**: Sprites or character/object textures.
    - Example: `spr_player_idle.png`, `spr_enemy_attack.png`.

#### 5. **Other Types**
- **Fonts (`.ttf`)**:
  - **`ui_`**: For use in the interface.
    - Example: `ui_main_font.ttf`.

---

### **Summary of Prefixes:**

| File Type          | Prefix   | Example                       |
|--------------------|----------|-------------------------------|
| Script             | `ctl_`, `mgr_`, `sys_` | `ctl_player.gd`, `mgr_audio.gd` |
| Scene              | `lvl_`, `ui_`, `scn_`   | `lvl_01.tscn`, `ui_pause_menu.tscn` |
| Audio Effects      | `sfx_`   | `sfx_hit.wav`, `sfx_win.ogg`  |
| Background Music   | `bgm_`   | `bgm_theme.mp3`, `bgm_intro.ogg` |
| Voice-Over          | `vo_`    | `vo_narrator.wav`             |
| UI Images           | `ui_`    | `ui_button.png`               |
| Background Images  | `bg_`    | `bg_dungeon.jpg`              |
| Sprites             | `spr_`   | `spr_enemy.png`               |
| Fonts               | `ui_`    | `ui_font.ttf`                 |


### General Rules for All Files

    Self-Descriptive Naming: Every file name should clearly indicate its purpose or function.
    Consistent Prefixes or Suffixes: Add identifiers like player, enemy, or menu to make files easily searchable.

## Contributing Guidelines
### Requirements

    Install Godot Engine (recommended version: 4.3).
    Clone the repository:

    git clone <repo-url>
    cd HoldYourColour

### Getting Started

    Open the project in Godot:
        Run godot and select the Project.godot file.
    Familiarize yourself with the directory structure.
    Check the repository issues for tasks you can contribute to.

### Contributions

    Follow the conventions listed above.
    Place global scripts or helpers in the Utilities/ directory.

## License

This project is licensed under the MIT License. Feel free to use the code and assets, but please credit the Hold Your Colour team.

---
# Español

# Hold Your Colour

Hold Your Colour es un <strong>juego roguelike de acción vista superior</strong> con <strong>mecánicas de construcción de mazo</strong>. Este proyecto busca ofrecer una experiencia dinámica y desafiante, combinando estrategia y acción en un entorno vibrante.

---

## Tabla de Contenidos

1. [Sobre el Proyecto](#sobre-el-proyecto)  
2. [Estructura del Proyecto](#estructura-del-proyecto)  
3. [Convenciones](#convenciones)  
4. [Guía de Contribuciones](#guía-de-contribuciones)  
5. [Licencia](#licencia)  
6. [Inglés - About the Project](#english---about-the-project)  

---

## Sobre el Proyecto

**Tipo de Juego:** Roguelike de acción vista superior con construcción de mazo  
**Estado:** En desarrollo  
**Desarrollador Principal:** Afrokarp  
**Colaboradores:** Equipo de UNGames  
**Plataforma:** Multiplataforma (PC, posiblemente soporte móvil)  
**Motor:** [Godot Engine](https://godotengine.org/)  

---

## Estructura del Proyecto

El proyecto está organizado en directorios claros para facilitar la navegación y colaboración. La estructura es funcional, agrupando elementos según su rol en el juego.  

```plaintext
HoldYourColour/
├── addons/                # Plugins y herramientas adicionales
├── Assets/                # Recursos generales del proyecto (música, fuentes, etc.)
├── Common/                # Lógica y recursos reutilizables
├── Config/                # Preferencias y configuraciones del jugador
├── Entities/              # Elementos interactivos (jugador, enemigos, interfaz, etc.)
├── Localization/          # Archivos de traducción (futuro)
├── Stages/                # Etapas y áreas del juego
├── Utilities/             # Ayudantes y gestores
└── Localization/          # Archivos de traducción (futuro)
```
##Convenciones
###Nomenclatura de Directorios
- PascalCase para todos los directorios, excepto addons.
    Ejemplo: Assets, Entities, Stages.
Sistema de Prefijos para la Organización de Archivos

Utiliza el sistema de prefijos pre_{nombre}.{extensión}, donde el prefijo indica el uso del archivo. Asegúrate de que el prefijo y la extensión del archivo no se repitan.
1. Scripts (.gd)

    Prefijo: ctl_ (controlador), mgr_ (gestor), sys_ (sistema general).
        Ejemplo:
            ctl_player.gd (controlador de jugador).
            mgr_game.gd (gestor del juego).
            sys_audio.gd (sistema de audio).

2. Escenas (.tscn)

    Prefijo: lvl_ (niveles), ui_ (interfaz de usuario), scn_ (escena genérica).
        Ejemplo:
            lvl_forest.tscn (escena del nivel bosque).
            ui_main_menu.tscn (escena del menú principal).

3. Archivos de Audio

    Prefijo: Basado en el propósito del audio.
        sfx_: Para efectos de sonido cortos.
            Ejemplo: sfx_explosion.wav, sfx_jump.ogg.
        bgm_: Para música de fondo o bucles largos.
            Ejemplo: bgm_battle_theme.mp3, bgm_menu_loop.ogg.
        vo_: Para locuciones o narraciones.
            Ejemplo: vo_intro.wav, vo_character1.ogg.

4. Archivos de Imagen

    Prefijo: Basado en el uso en UI, fondos o sprites.
        ui_: Elementos de interfaz de usuario.
            Ejemplo: ui_button.png, ui_cursor.png.
        bg_: Fondos.
            Ejemplo: bg_forest.png, bg_space.jpg.
        spr_: Sprites o texturas de personajes/objetos.
            Ejemplo: spr_player_idle.png, spr_enemy_attack.png.

5. Otros Tipos

    Fuentes (.ttf):
        ui_: Para uso en la interfaz.
            Ejemplo: ui_main_font.ttf.

   ---

### Resumen de Prefijos:

| File Type          | Prefix   | Example                       |
|--------------------|----------|-------------------------------|
| Script             | `ctl_`, `mgr_`, `sys_` | `ctl_player.gd`, `mgr_audio.gd` |
| Escena            | `lvl_`, `ui_`, `scn_`   | `lvl_01.tscn`, `ui_pause_menu.tscn` |
| Efectos de Sonido      | `sfx_`   | `sfx_hit.wav`, `sfx_win.ogg`  |
| Musica de Fondo   | `bgm_`   | `bgm_theme.mp3`, `bgm_intro.ogg` |
| Locuciones          | `vo_`    | `vo_narrator.wav`             |
| Imágenes UI          | `ui_`    | `ui_button.png`               |
| Imagenes de fondo  | `bg_`    | `bg_dungeon.jpg`              |
| Sprites             | `spr_`   | `spr_enemy.png`               |
| Fonts               | `ui_`    | `ui_font.ttf`                 |

### Reglas Generales para Todos los Archivos
Nomenclatura Auto-Explicativa: Cada nombre de archivo debe indicar claramente su propósito o función.
Prefijos o Sufijos Consistentes: Añade identificadores como player, enemy o menu para hacer los archivos fácilmente buscables.
## Guía de Contribuciones
### Requisitos
Instala Godot Engine (versión recomendada: 4.3).
Clona el repositorio:

git clone <repo-url>
cd HoldYourColour
### Comenzando
Abre el proyecto en Godot:
    Ejecuta godot y selecciona el archivo Project.godot.
Familiarízate con la estructura de directorios.
Revisa los problemas del repositorio para encontrar tareas en las que puedas contribuir.
### Contribuciones
Sigue las convenciones listadas arriba.
Coloca scripts o ayudantes globales en el directorio Utilities/.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Siéntete libre de usar el código y los recursos, pero por favor, da crédito al equipo de Hold Your Colour.

