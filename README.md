# Skeleton Traductor

Traductor de juegos para Windows: Unity, Ren'Py, RPG Maker, KiriKiri y Wolf RPG.

## Descargar

**[Descargar Skeleton Traductor 0.5.5 Portable](https://github.com/TioOnlyH/Skeleton-Traductor/releases/download/v0.5.5/SkeletonTraductor_0.5.5_Portable.zip)**

- Archivo: `SkeletonTraductor_0.5.5_Portable.zip`
- SHA-256: `675883F5015E3360664D6B46B945A78D0CA90BA58ED8A0946B0996778C144D16`
- No necesitas instalar Python.
- Windows 10/11 de 64 bits.

Si el enlace no abre, entra en **Releases** y descarga el ZIP de la version 0.5.5.

## Novedades de la 0.5.5

- Boton **Actualizar** con comprobacion de `latest.json`, descarga, verificacion SHA-256 e instalacion conservando datos.
- Licencias **permanentes** y licencias de prueba **por horas**. Las de horas comprueban la hora UTC de Internet al activarse y al abrir la app; el contador solo corre con la app abierta.
- Busqueda global en todos los archivos de Fase_2, con resultados por archivo y linea.
- Editor manual ampliable y minimizable.
- Copiar original con clic o Ctrl+C y pegar con Ctrl+V.
- Botones del editor siempre visibles.
- Wolf RPG: soporte de `Data.wolf`, Fase_2 al extraer y comentarios `//` fuera.
- Ren'Py: Fase_2 se crea vacia y se conservan las traducciones existentes.
- KiriKiri: los `.scn` se instalan en su ruta correcta (`data/scenario/`).
- Reinyeccion mas limpia: reemplaza la salida anterior y conserva `Save`/`savedata`.
- Correcciones de cache y de deteccion de salidas.

## Instalar

1. Descomprime el ZIP en una carpeta con permisos de escritura.
2. Ejecuta `Iniciar.cmd`.
3. La primera vez se abre en modo **Free**.

No ejecutes el programa desde dentro del ZIP: descomprimelo primero.

## Uso rapido

1. Copia cada juego dentro de la carpeta `Ordenardor`. Puedes poner una carpeta por juego.
2. Abre la app y pulsa **Ordenar juegos**.
3. Elige el juego en la lista.
4. En **Free**:
   - **Extraer texto**.
   - Edita la tabla manual.
   - **Solo inyectar** cuando termines.
5. En **Pro**:
   - Activa la licencia en **Ajustes -> Licencia**.
   - Configura la clave de DeepSeek si la vas a usar.
   - Elige **Traducir** o **Reanudar**.

## Free y Pro

- **Free**: extraer texto, editarlo a mano e inyectarlo.
- **Pro**: traduccion automatica con Google/DeepSeek, reanudacion, editores y demas motores desbloqueados.

Las licencias permanentes se validan sin conexion. Las licencias por horas necesitan Internet al activarse y al abrir la app para comprobar la hora UTC. Esta descarga no incluye el generador de claves ni claves privadas.

## Carpetas importantes

- `Ordenardor`: deja aqui los juegos nuevos.
- `Unity`, `RPGM`, `Renpy`, `Kirikiri`, `WOLFRPG`: colas internas por motor.
- `Juegos Terminados`: resultados publicados.
- `Registros`: copias de seguridad de las traducciones.

No borres `Registros` si quieres conservar traducciones ya hechas.

## Actualizaciones

La app consulta `latest.json` cuando se anada el actualizador. Mientras tanto, descarga el ZIP nuevo desde Releases y descomprimelo sobre la carpeta del programa; no borres `Registros` ni `Juegos Terminados`.

## Si una carpeta da acceso denegado

Ejecuta `SOLUCIONAR_PERMISOS.cmd` dentro de la carpeta del programa. Repara los permisos heredados del ZIP y de la carpeta donde lo descomprimiste.

## Problemas con Windows Defender

Si Windows muestra un aviso, comprueba el SHA-256 publicado. La distribucion principal es la portable.

## Soporte

Incluye un diagnostico en la app (**Diagnostico**) que comprueba Python, librerias, espacio, configuracion y trabajos pendientes.

## Patrocinar

Puedes apoyar el proyecto y obtener una licencia Pro en:

https://www.patreon.com/c/onlyh/membership
