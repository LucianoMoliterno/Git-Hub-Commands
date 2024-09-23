# Control de Versiones con Git y GitHub

¡Bienvenidos! En este curso aprenderás a controlar versiones y colaborar en proyectos de desarrollo web utilizando Git y GitHub. Además, veremos cómo publicar una página web con GitHub Pages. Todo lo necesario para gestionar proyectos y trabajar en equipo de manera eficiente.

## Unidades de Aprendizaje

### 1. Terminal, Git y GitHub
Aquí te enseñaré a:
- Crear un repositorio remoto en GitHub.
- Controlar las versiones de un proyecto.
- Publicar una página web usando GitHub Pages.

### 2. Trabajo Colaborativo y GitHub Pages
En esta unidad aprenderás:
- El flujo de trabajo colaborativo con Git.
- A gestionar cambios, ramas y conflictos en proyectos colaborativos.
- Cómo utilizar GitHub Pages para la publicación de sitios web.

## Herramientas Necesarias

- **Firefox**: Navegador recomendado para visualizar y probar la página web.
- **Visual Studio Code**: El editor de código que utilizaremos. [Descargar VSCode](https://code.visualstudio.com/).
- **Git Bash** (para Windows) / **Terminal** (para Linux y Mac): Herramientas de línea de comandos para ejecutar Git.
- **Git**: Software de control de versiones. [Descargar Git](https://git-scm.com/downloads).
- **GitHub / GitHub Pages**: Plataforma para alojar el código y la página web. [GitHub](https://github.com/).
- **Xcode** (para Mac): Utilizado para instalar y actualizar Git en macOS. [Descargar Xcode](https://imageoptim.com/changelog.html).

## ¡Empecemos!

Este curso está diseñado para que entiendas no solo cómo controlar versiones, sino también cómo colaborar efectivamente con otros en un proyecto y compartir tu trabajo con el mundo a través de GitHub Pages.

---

## Paso a Paso para Controlar Versiones y Colaborar

### 1. Configuración Inicial

Primero, asegúrate de tener Git instalado. Luego configura tu nombre y correo en Git:

- git config --global user.name "Tu Nombre"
- git config --global user.email "tuemail@example.com"

### 2. Crear un Repositorio Local

Para iniciar un repositorio en tu proyecto, usa el siguiente comando dentro de la carpeta de tu proyecto:

- git init
- 
Esto iniciará el control de versiones en la carpeta donde estás trabajando.

### 3. Crear un Repositorio Remoto en GitHub

1) Inicia sesión en GitHub.
2) Crea un nuevo repositorio, dale un nombre y selecciona "Create repository".
3) Luego enlaza tu repositorio local con GitHub usando el siguiente comando (reemplaza con tu URL):

- git remote add origin https://github.com/tuusuario/tu-repositorio.git

### 4. Realizar Cambios y Subirlos a GitHub

1) Agregar archivos al área de staging:
   
   - git add .
     
3) Hacer un commit con un mensaje que describa los cambios:
   
   - git commit -m "Descripción de los cambios"
     
4) Subir los cambios al repositorio remoto en GitHub:
   
   - git push -u origin main
   
### 5. Clonar un Repositorio Existente

Si estás colaborando en un proyecto y necesitas clonar un repositorio existente:

- git clone https://github.com/usuario/proyecto.git

### 6. Colaboración: Pull y Push

Para trabajar con otros, siempre es importante obtener los últimos cambios antes de hacer modificaciones:

- git pull origin main

Después de hacer tus propios cambios, agrega y sube con:

- git add .
- git commit -m "Descripción de cambios"
- git push origin main

### 7. Publicar una Página Web con GitHub Pages

Para publicar tu proyecto como una página web:

1) Ve a la pestaña Settings en tu repositorio de GitHub.
2) En GitHub Pages, selecciona la rama main y la carpeta /root.
3) ¡Listo! Tu página estará disponible en https://tuusuario.github.io/tu-repositorio/.

