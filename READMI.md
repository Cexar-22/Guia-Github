# Mi Guía Para GitHub

Este repositorio contiene los pasos esenciales para conectar proyectos locales con GitHub utilizando la terminal de VS Code.

---

## 1. Configuración Inicial
*Solo se realiza la primera vez o después de formatear el PC.*

* **Establecer nombre:** `git config --global user.name "Tu Usuario de Github"`
* **Establecer correo:** `git config --global user.email "tuemaildetucuentadeGithub@email.com"`

## 2. Crear un Repositorio desde Cero

Sigue este orden para subir un proyecto nuevo:

1. `git init` — Inicia el rastreo del proyecto.
2. `git add .` — Añade los archivos, el punto añade todo ,si quiero añadir algo especifico : "git add "nombre del archivo"
3. `git commit -m "Mensaje descriptivo"` — Guarda los cambios y Añade un Mensaje Descriptivo.
4. `git branch -M main` — Renombra la rama principal a `main`.
5. `git remote add origin <LINK_DEL_REPO_EN_Github>` — Conecta mi carpeta del proyecto con el servidor de github.
6. `git push -u origin main` — Sube los archivos Hacia el servidor de Github.

## 🔄 3. Comandos de Uso Diario
| Comando | Descripción |
| :--- | :--- |
| `git status` | Revisa qué archivos han cambiado. |
| `git add .` | Prepara todos los cambios para el commit. |
| `git commit -m "texto"` | Guarda una versión de tus cambios. |
| `git push` | Sube los cambios a la nube. |
| `git pull` | Baja los cambios más recientes del servidor. |