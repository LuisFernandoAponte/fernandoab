# Presentación: Cómo Subir a Mi Repositorio en Git

## 1. Introducción a Git
- **¿Qué es Git?**
  - Sistema de control de versiones.
  - Permite rastrear cambios en archivos y colaborar en proyectos.

## 2. Preparación
- **Instalación de Git**
  - Asegúrate de tener Git instalado. Puedes verificarlo con:
    ```bash
    git --version
    ```

- **Configuración Inicial**
  - Configura tu nombre y correo:
    ```bash
    git config --global user.name "Tu Nombre"
    git config --global user.email "tuemail@example.com"
    ```

## 3. Clonación del Repositorio
- **Clonar un Repositorio Existente**
  - Usa el siguiente comando para clonar un repositorio:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```

## 4. Trabajando en Tu Proyecto
- **Navegar al Directorio del Proyecto**
  - Entra en el directorio clonado:
    ```bash
    cd nombre-del-repositorio
    ```

- **Agregar Archivos**
  - Crea o modifica archivos en tu proyecto.

## 5. Subir Cambios al Repositorio
- **Verificar el Estado**
  - Comprueba qué archivos han cambiado:
    ```bash
    git status
    ```

- **Agregar Cambios**
  - Agrega los archivos que quieres subir:
    ```bash
    git add nombre-del-archivo
    ```
  - O para agregar todos los cambios:
    ```bash
    git add .
    ```

- **Realizar un Commit**
  - Guarda tus cambios con un mensaje descriptivo:
    ```bash
    git commit -m "Descripción de los cambios"
    ```

## 6. Subir Cambios al Repositorio Remoto
- **Enviar Cambios al Repositorio Remoto**
  - Usa el siguiente comando para subir tus cambios:
    ```bash
    git push origin main
    ```
  - Asegúrate de reemplazar `main` con la rama correspondiente si es diferente.

## 7. Conclusión
- **Resumen**
  - Hicimos un recorrido por los pasos necesarios para subir cambios a un repositorio en Git.
  
- **Preguntas**
  - Abro el espacio para preguntas y aclaraciones.
