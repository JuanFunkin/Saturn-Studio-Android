# Saturn Studio Android

**🇪🇸 Español** · [🇬🇧 English](#english)

Port no oficial de **Saturn Studio** para teléfonos Android, compatible con **32 bits (armeabi-v7a)** y **64 bits (arm64-v8a)**.

Saturn Studio es un editor de animaciones para Super Mario 64: permite crear animaciones, guardar proyectos y exportar los fotogramas. Este port lo adapta a pantallas táctiles: gestos para la cámara, interfaz con botones grandes, selector de archivos del sistema y una carpeta de datos propia (`com.saturnstudio`).

Este repositorio no contiene código de Saturn Studio ni de SDL2. El script `setup.sh` los descarga de sus repositorios originales (en una versión fija) y les aplica los parches y archivos de esta carpeta.

### Aviso legal
- Este proyecto **no incluye ninguna ROM ni recursos de Nintendo**. Necesitas tu propia copia legal de Super Mario 64 (US, .z64). Los recursos se extraen en tu teléfono a partir de tu ROM.
- Proyecto de fans, sin ánimo de lucro, **no afiliado ni respaldado por Nintendo**. Super Mario 64 y Mario son marcas de Nintendo.
- Es un port no oficial: no pidas soporte de esta versión a los autores de Saturn.

### Créditos
- **Saturn Studio**, de [fgetcat](https://github.com/fgetcat/saturn-studio) y colaboradores: el programa que se porta aquí.
- **Saturn**, de [Llennpie](https://github.com/Llennpie/Saturn) y colaboradores: proyecto original del que Saturn Studio es un fork.
- **sm64ex / sm64-port** y la decompilación de SM64 ([n64decomp/sm64](https://github.com/n64decomp/sm64)): base técnica de Saturn.
- **DynOS**, **Dear ImGui** (Omar Cornut) y **SDL2** ([libsdl-org](https://github.com/libsdl-org/SDL)).
- **Port a Android** (capa táctil, interfaz móvil, soporte 32/64 bits, proyecto Gradle/NDK, workflow): [TU NOMBRE].
- Código generado con ayuda de Claude (Anthropic).

### Licencias
Cada componente conserva su licencia original. Los parches y archivos nuevos de este repositorio se publican bajo [LICENCIA].

---

<a name="english"></a>
## 🇬🇧 English

Unofficial port of **Saturn Studio** for Android phones, supporting **32-bit (armeabi-v7a)** and **64-bit (arm64-v8a)**.

Saturn Studio is an animation editor for Super Mario 64: create animations, save projects and export frames. This port adapts it to touch screens: camera gestures, a UI with large buttons, the system file picker and its own data folder (`com.saturnstudio`).

This repository does not contain Saturn Studio or SDL2 code. The `setup.sh` script downloads them from their original repositories (pinned version) and applies the patches and files in this repo.

### Legal notice
- This project **includes no ROM and no Nintendo assets**. You need your own legal copy of Super Mario 64 (US, .z64). Assets are extracted on your phone from your ROM.
- Non-profit fan project, **not affiliated with or endorsed by Nintendo**. Super Mario 64 and Mario are trademarks of Nintendo.
- This is an unofficial port: please do not ask the Saturn authors for support with this version.

### Credits
- **Saturn Studio** by [fgetcat](https://github.com/fgetcat/saturn-studio) and contributors: the program being ported.
- **Saturn** by [Llennpie](https://github.com/Llennpie/Saturn) and contributors: the original project Saturn Studio forks.
- **sm64ex / sm64-port** and the SM64 decompilation ([n64decomp/sm64](https://github.com/n64decomp/sm64)): technical base of Saturn.
- **DynOS**, **Dear ImGui** (Omar Cornut) and **SDL2** ([libsdl-org](https://github.com/libsdl-org/SDL)).
- **Android port** (touch layer, mobile UI, 32/64-bit support, Gradle/NDK project, workflow): [YOUR NAME].
- Code written with the help of Claude (Anthropic).

### Licenses
Each component keeps its original license. The patches and new files in this repository are released under [LICENSE].

---
