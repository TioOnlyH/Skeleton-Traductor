# Skeleton Traductor

Traductor de juegos para Windows: Unity, Ren'Py, RPG Maker, KiriKiri y Wolf RPG.

## Descargar

**[Descargar Skeleton Traductor 0.5.6 Portable](https://github.com/TioOnlyH/Skeleton-Traductor/releases/download/v0.5.6/SkeletonTraductor_0.5.6_Portable.zip)**

- Archivo: `SkeletonTraductor_0.5.6_Portable.zip`
- SHA-256: `C17B905D8CF492C3676D1B8F59059C238B4B6C3364891780E5DA3B4AA15068D3`
- No necesitas instalar Python.
- Windows 10/11 de 64 bits.

Si el enlace no abre, entra en **Releases** y descarga el ZIP de la version 0.5.6.

## Novedades de la 0.5.6

- Hilos de Google ajustables de 1 a 8 en Ajustes para reducir errores 429.
- Traduccion manual: Ctrl+G traduce solo la linea seleccionada.
- La tabla manual se selecciona con un solo clic y Ctrl+G funciona aunque el foco este en el cuadro de traduccion.
- Ren'Py guarda Fase_1/Fase_2 parciales cuando la traduccion automatica falla, para poder corregir desde Traduccion manual.
- Ren'Py conserva los IDs de auto-voice cuando el juego configura `get_voice_file(id)` con funcion.
- Soporte de imagenes de RPG Maker: preparar, abrir e inyectar.
- Soporte de BepInEx/XUnity y literales de Assembly-CSharp en Unity.
- Nuevas fuentes CSV para KiriKiri y RPG Maker.
- Correcciones de registros por juego, publicacion y rutas de trabajo.

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

La app consulta `latest.json` al pulsar **Actualizar**. Tambien puedes descargar el ZIP nuevo desde Releases y descomprimirlo sobre la carpeta del programa; no borres `Registros` ni `Juegos Terminados`.

## Si una carpeta da acceso denegado

Ejecuta `SOLUCIONAR_PERMISOS.cmd` dentro de la carpeta del programa. Repara los permisos heredados del ZIP y de la carpeta donde lo descomprimiste.

## Problemas con Windows Defender

Si Windows muestra un aviso, comprueba el SHA-256 publicado. La distribucion principal es la portable.

## Soporte

Incluye un diagnostico en la app (**Diagnostico**) que comprueba Python, librerias, espacio, configuracion y trabajos pendientes.

## Patrocinar

Puedes apoyar el proyecto y obtener una licencia Pro en:

https://www.patreon.com/c/onlyh/membership