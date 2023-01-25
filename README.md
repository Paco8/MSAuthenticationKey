
# MSAuthenticationKey

Este es un programa para poder obtener un fichero *.key para poder
iniciar sesión en el plugin [plugin.video.movistarplus](https://github.com/Paco8/plugin.video.movistarplus).

El programa abrirá una ventana de Google Chrome (vale también Chromium o Brave), con la web
de movistarplus, donde deberás iniciar sesión. Hecho eso el programa obtendrá un token de la web,
cerrará la ventana de Chrome y guardará ese token en un fichero en el disco (`msauthentication.key`).

Ese fichero key se puede usar para poder iniciar sesión en el plugin `plugin.video.movistarplus`. 
Puedes usar el fichero key en multiples dispositivos.

## Descarga
Existen versiones para Windows, Linux y Mac OS.

## Instrucciones de uso
- Descomprime el fichero zip que has descargado. El zip contiene dos 
ficheros, `MSAuthenticationKey` que es el ejecutable y `settings.json`.
- Ejecuta el fichero `MSAuthenticationKey`. Después de un mensaje de
bienvenida te pedirá que pulses Intro, tras lo cual abrirá una
ventana de Google Chrome en modo incógnito con la web de movistarplus.
- En esa ventana selecciona la opción `Identifícate` e introduce
tus credenciales.
- Si todo ha ido bien la ventana de Chrome se cerrará y se habrá
guardado en la misma carpeta el token en el fichero `msauthentication.key`.
- Este fichero cópialo al dispositivo donde quieras usarlo, en una
carpeta que sea accesible por Kodi (por ejemplo `Download`).
- En Kodi, entra en `plugin.video.movistarplus` y selecciona
`Iniciar sesión con un fichero key`.
Si todo ha ido bien cargará el menú principal del plugin ya podrás
acceder a las diferentes secciones.


