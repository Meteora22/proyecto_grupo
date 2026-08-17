# Proyecto Grupo

Repositorio de práctica para el Laboratorio 1 — Colaboración con Git y GitHub, de la asignatura Principios de Desarrollo de Software (Pontificia Universidad Javeriana). El objetivo es practicar el flujo de trabajo colaborativo con ramas, pull requests, resolución de conflictos de merge y la comparación entre merge y rebase.

## Integrantes del equipo

- Santiago Urrutia
- Isaac Janica
- Juan Camilo Delgado

## Descripción del proyecto

Cada integrante trabajó en su propia rama para agregar su nombre a la lista de integrantes en `index.html`, siguiendo el flujo estándar de Git: clonar el repositorio, crear una rama personal, hacer commits, subir la rama, abrir un pull request, recibir revisión de un compañero y fusionar los cambios a `main`. Como parte del ejercicio, se provocó y resolvió intencionalmente un conflicto de merge, y se realizó un experimento adicional comparando merge contra rebase.

## Comandos utilizados

| Comando | Propósito |
|---|---|
| `git --version` | Verificar que Git esté instalado correctamente |
| `git config --global user.name "..."` | Configurar el nombre asociado a los commits |
| `git config --global user.email "..."` | Configurar el correo asociado a los commits |
| `gh auth login` | Autenticar el computador con GitHub CLI |
| `gh auth status` | Verificar que la autenticación quedó activa |
| `gh repo clone USUARIO/proyecto_grupo` | Clonar el repositorio remoto al computador local |
| `git branch --show-current` | Ver en qué rama se está parado |
| `git checkout -b nombre-rama` | Crear una rama nueva y moverse a ella |
| `git status` | Ver qué archivos cambiaron y su estado |
| `git add .` | Preparar los cambios para el próximo commit |
| `git commit -m "mensaje"` | Guardar los cambios preparados en el historial local |
| `git push -u origin nombre-rama` | Subir una rama nueva a GitHub y enlazarla con el remoto |
| `git push origin nombre-rama` | Subir commits a una rama ya enlazada con el remoto |
| `git pull origin main` | Traer y aplicar los cambios que otros subieron a `main` |
| `git checkout main` | Moverse a la rama `main` |
| `git checkout nombre-rama` | Moverse a una rama que ya existe |
| `git merge nombre-rama` | Integrar los cambios de otra rama en la rama actual |
| `git rebase main` | Reaplicar los commits de la rama actual encima de `main`, generando un historial lineal |
| `git rebase --continue` | Continuar un rebase después de resolver un conflicto |
| `git add archivo` (durante conflicto) | Marcar un archivo en conflicto como resuelto |
| `git log --oneline --graph --all --decorate` | Visualizar el historial de commits en forma de árbol |

## Enlace al repositorio

https://github.com/Meteora22/proyecto_grupo
