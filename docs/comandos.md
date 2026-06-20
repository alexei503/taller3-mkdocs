# Comandos básicos de Git

Los siguientes comandos son fundamentales para trabajar con Git.

## Tabla de comandos

| Comando | Función |
|----------|----------|
| git init | Inicializa un repositorio |
| git status | Muestra el estado actual |
| git add . | Agrega archivos al área de preparación |
| git commit | Guarda cambios en el historial |
| git push | Envía cambios a GitHub |

## Ejemplo de uso

=== "Linux"

    ```
    bash
    git init
    git add .
    git commit -m "Primer commit"
    git push origin main
    ```

=== "Windows"

    ```
    powershell
    git init
    git add .
    git commit -m "Primer commit"
    git push origin main
    ```

## Flujo básico de trabajo

1. Crear un repositorio.
2. Agregar archivos.
3. Realizar commits.
4. Enviar cambios a GitHub.

!!! warning "Advertencia"
    Antes de ejecutar `git push`, verifica que estás trabajando en la rama correcta.

Volver al [Inicio](index.md).
