# Nuevo Conocimiento

Este es un archivo Markdown creado para practicar lo aprendido en el curso de Git y GitHub.

## Sección 1: Introducción a Git

En esta sección, aprendí los conceptos básicos de Git, incluyendo:
- **Sistema de control de versiones**: Git es un sistema distribuido de control de versiones.
- **Instalación de Git**: Cómo instalar Git en diferentes sistemas operativos.
  - **En Windows**:
    - Descarga el instalador desde [git-scm.com](https://git-scm.com/download/win).
    - Ejecuta el instalador y sigue las instrucciones.
  - **En macOS**:
    - Usa Homebrew para instalar Git con el siguiente comando:
      ```bash
      brew install git
      ```
  - **En Linux**:
    - Usa el gestor de paquetes de tu distribución. Por ejemplo, en Debian/Ubuntu:
      ```bash
      sudo apt-get install git
      ```
    - En Fedora:
      ```bash
      sudo dnf install git
      ```
- **Configuración inicial**:
  - Configurar el nombre de usuario:
    ```bash
    git config --global user.name "Tu Nombre"
    ```
  - Configurar el correo electrónico:
    ```bash
    git config --global user.email "tuemail@example.com"
    ```
  - Habilitar colores en la línea de comandos:
    ```bash
    git config --global color.ui auto
    ```

## Sección 2: Comandos Básicos de Git

- **Inicializar un repositorio**:
  ```bash
  git init
