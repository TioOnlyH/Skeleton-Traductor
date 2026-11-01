# Skeleton Traductor

Traductor de juegos para Windows: Unity, Ren'Py, RPG Maker, KiriKiri y Wolf RPG.

## Descargar

**[Descargar Skeleton Traductor 0.5.4 Portable](https://github.com/TioOnlyH/Skeleton-Traductor/releases/download/v0.5.4/SkeletonTraductor_0.5.4_Portable.zip)**

- Archivo: `SkeletonTraductor_0.5.4_Portable.zip`
- SHA-256: `EA0789B7765E7169FC56DE7B048C4B33D915B71B97C3AA304FFBD44E4CE54DB8`
- No necesitas instalar Python.
- Windows 10/11 de 64 bits.

Si el enlace no abre, entra en **Releases** y descarga el ZIP de la version 0.5.4.

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

La licencia se verifica sin conexion. Esta descarga no incluye el generador de claves ni claves privadas.

## Carpetas importantes

- `Ordenardor`: deja aqui los juegos nuevos.
- `Unity`, `RPGM`, `Renpy`, `Kirikiri`, `WOLFRPG`: colas internas por motor.
- `Juegos Terminados`: resultados publicados.
- `Registros`: copias de seguridad de las traducciones.

No borres `Registros` si quieres conservar traducciones ya hechas.

## Actualizaciones

La app consulta `latest.json` cuando se añada el actualizador. Mientras tanto, descarga el ZIP nuevo desde Releases y descomprimelo sobre la carpeta del programa; no borres `Registros` ni `Juegos Terminados`.

## Si una carpeta da acceso denegado

Ejecuta `SOLUCIONAR_PERMISOS.cmd` dentro de la carpeta del programa. Repara los permisos heredados del ZIP y de la carpeta donde lo descomprimiste.

## Problemas con Windows Defender

Si Windows muestra un aviso, comprueba el SHA-256 publicado. La version 0.5.4 aun no tiene firma Authenticode; se esta preparando para versiones posteriores.

## Soporte

Incluye un diagnostico en la app (**Diagnostico**) que comprueba Python, librerias, espacio, configuracion y trabajos pendientes.

## Patrocinar

Puedes apoyar el proyecto y obtener una licencia Pro en:

https://www.patreon.com/c/onlyh/membership
