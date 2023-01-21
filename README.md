# Steins;Gate 0 Steam Español

Esta traducción fue realizada con la traducción de [TraduSquare](https://github.com/TraduSquare?q=steins&type=&language=), y adaptada por mi para poder ser jugable en la versión de [Steam](https://store.steampowered.com/app/825630/STEINSGATE_0/)


## Instrucciones
Para poder instalar el parche primero debe tener la versión Original de Steam **en ingles**
> puede comprobar esto dando clic derecho en su la portada de su biblioteca-> propiedades -> idioma

Ahora debe instalar el parche ingles de [Committee of Zero](http://sonome.dareno.me/projects/sg0-steam.html)  siguiendo las siguientes instrucciones 

 1. Descargar la versión del parche que quieras [aqui](https://github.com/CommitteeOfZero/zero-patch/releases) o el que deje en el [repositorio](https://github.com/Sarag1/Steins-es-0/releases/tag/1.0) para tener la versión con la que trabaje
 2. Extrae los archivos y ejecuta la instalación de `SG0Patch-Installer.exe`
 >  Si el instalador se cierra con el error  `MSVCP140_1.dll`, Instala [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe)  (32-bit versión, vc_redist.x86.exe - dependiendo de tu sistema operativo) e inténtalo de nuevo

Una vez terminada la instalación del parche debe irse a la carpeta en la que tiene instalado **Steins;Gate 0** normalmente se encuentra en `C:\Program Files (x86)\Steam\steamapps\common\STEINS;GATE 0` Cuando estemos en la dirección, debemos ir a la carpeta `languagebarrier` y reemplazar el archivo `enscript_h.mpk` por el que esta en [este repositorio](https://github.com/Sarag1/Steins-es-0/releases/download/1.0/enscript_h.mpk)

y eso es todo, ya esta el juego parchado al español.
## Errores conocidos
En algunas partes de la traducción se puede llegar a encontrar errores debidos a unas "L" y "l" que se encontraban en la traducción original, las cuales removí algunas pero no descarto haber pasado por alto una que otra, si encuentra algunas "L" o "l" que no cuadre en la traducción puede por favor reportarla en esta [discusión general](https://github.com/Sarag1/Steins-es-0/discussions/2)

## Errores del parche de Committee of Zero

Aqui dejo las soluciones a los errores comunes del parche de Committee of Zero en español

### error `mgs::Audio::CPlayer::InitializeXaudio()`
![XAudio2 error](http://sonome.dareno.me/uploads/error_xaudio.png)

Instalar  [DirectX 9.0c](https://www.microsoft.com/en-us/download/details.aspx?id=35)  y reintentar.

### Instalador muestra el error de  `MSVCP140_1.dll`

![MSVCP140.dll error](http://sonome.dareno.me/uploads/error_vcruntime_sg0_steam.png)

Installar  [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe)  (32-bit version, vc_redist.x86.exe - dependiendo de tu sistema) e inténtalo nuevamente.

### Error del instalador  `api-ms-win-crt-runtime-l1-1-0.dll`

![UCRT error](http://sonome.dareno.me/uploads/error_ucrt.png)

Actualizar Windows. Es posible que deba instalar Visual C ++ Redistributable nuevamente después (archivo anterior): use "Reparar" cuando se le solicite
