# Ejercicio Avanzado de Git

Este ejercicio se divide en tres partes, cada una enfocada en diferentes aspectos avanzados de Git, como la resolución de conflictos, la comparación de cambios entre commits, y el rebase de ramas.

## Parte 1: Resolución de Conflictos en Fusión de Ramas

### Instrucciones
1. **Equipo 1**: Trabaja en la rama `feature1` y realiza cambios en el archivo `archivo.txt`.
2. **Equipo 2**: Trabaja en la rama `feature2` y realiza cambios en el archivo `archivo.txt`.
3. **Equipo 3**: Trabaja en la rama `feature3` y realiza cambios en el archivo `archivo.txt`.
4. Una vez realizados los cambios, cada equipo debe fusionar su rama con la rama principal (`main`).

### Pista
- **Pista**: Al fusionar las ramas, es posible que se generen conflictos si las mismas líneas en `archivo.txt` han sido modificadas por más de un equipo. Asegúrate de revisar cuidadosamente los conflictos y resolverlos antes de completar la fusión.

## Parte 2: Comparación de Cambios entre Commits

### Instrucciones
1. **Desarrollador 1**: Trabaja en la rama `dev1` y realiza cambios en el archivo `script.py`.
2. **Desarrollador 2**: Trabaja en la rama `dev2` y realiza cambios en el archivo `script.py`.
3. Los desarrolladores deben comparar los cambios en sus respectivas ramas con la rama principal (`main`) utilizando `git diff`.
4. Una vez completada la comparación, ambos desarrolladores deben fusionar sus cambios en la rama principal.

### Pista
- **Pista**: Usa el comando `git diff` para comparar los cambios entre la rama principal y las ramas de los desarrolladores. Esto te permitirá ver exactamente qué se ha cambiado en el archivo `script.py` antes de hacer el merge.

## Parte 3: Resolución de Conflictos en Rebase

### Instrucciones
1. **Grupo 1**: Trabaja en la rama `feature-config1` y realiza cambios en el archivo `config.json`.
2. **Grupo 2**: Trabaja en la rama `feature-config2` y realiza cambios en el archivo `config.json`.
3. El grupo 1 debe realizar un rebase de su rama `feature-config1` sobre la rama `feature-config2`.
4. Después del rebase, los cambios deben integrarse en la rama principal (`main`).

### Pista
- **Pista**: Durante el rebase, es probable que encuentres conflictos si ambos grupos han cambiado las mismas claves en `config.json`. Resuélvelos con cuidado antes de continuar.

---

**Nota**: Recuerda que cada parte del ejercicio está diseñada para que experimentes con diferentes funcionalidades avanzadas de Git. Sigue las pistas si necesitas ayuda, pero intenta resolver los problemas por ti mismo antes de buscar asistencia.
