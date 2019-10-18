[Click here for English Version](https://github.com/RetroGamer74/RR_RetroReloaded/blob/master/README_EN.md)
# RR (RetroReloaded - Gestor de Arranque)

Muy Importante: Para nuevos usuarios, o usuarios actualizando a RetroReloaded 2.XX por primera vez, eliminar la carpeta de atmosphere y ReiNX en tu microSD si existen. Esto proporcionará un estado limpio antes de instalarlo.
Puedes ver los cambios de cada versión en las [Releases.](https://github.com/RetroGamer74/RR_RetroReloaded/releases)

### Cambios Importantes
* Siempre que descargues una versión de RetroReloaded, puede ser que el payload.bin que extraerás del paquete y quedará almacenado en tu microSD en la carpeta raíz haya sido actualizado. Si usas TegraRCMGUI para arrancar desde tu PC debes copiar este archivo en tu PC. No lo elimines de la SD. Sólo copialo, para luego lanzarlo desde TegraRCMGUI.

Tinfoil ha sido eliminado.

Puedes eliminar de tu microSD de la carpeta swich, las carpetas Tinfoil y Mercury si aún las tienes. No se van a usar más en el contexto actual. Tinfoil requiere ahora una versión de Atmosphere preparada ad-hoc para esta herramienta y no es algo aceptable.

Cuando utilices la herramienta Hekate desde RetroReloaded hay un botón que pone Back RR que te permite volver al boot manager de RetroReloaded cuando quieras.

### Qué es RetroReloaded?

Es un Boot Manager para Switch que permite arrancar de una forma preconfigurada custom firmwares como Atmosphere, ReiNX y SX OS, desde un menú único. Además de herramientas de gran utilidad.

( Ver los  CRÉDITOS para más información )

![alt text](rr_boot_v3.jpg)

![alt text](Settings-RR.jpg)

![alt text](Service-RR.jpg)



Soporte touch.

[![Chat on Discord](https://camo.githubusercontent.com/b4175720ede4f2621aa066ffbabb70ae30044679/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636861742d446973636f72642d627269676874677265656e2e737667)](https://discordapp.com/invite/cUnjkPH)

## Instalación

### Descarga

Tienes dos opciones. Utilizar el Windows Installer, o descargar el zip que hay en la sección de [Releases](https://github.com/RetroGamer74/RR_RetroReloaded/releases) y extraerlo tu mismo sobre tu microSD.

#### Opción 1
Descarga el [Windows RetroReloaded Installer](https://github.com/RetroGamer74/RR_RetroReloaded-RetroReloaded-Switch-RR/blob/master/RR_Installer.rar) para preparar tu microSD automáticamente. 

![alt text](RR_Installer.jpg)

#### Opción 2
Descarga la última release disponible ( https://github.com/RetroGamer74/RR_RetroReloaded/releases ), extráela sobreescribiendo los archivos ya existentes en tu microSD. No sobreescribe archivos de configuración de tus aplicaciones ni te elimina datos.

### Arranque

Para arrancar RetroReloaded puedes usar las siguientes opciones.

#### Usando un cable USB-C y un PC

Si usas esta opción no tendrás que actualizar nunca el payload.bin. Descarga [NX_Payload_Forwarder](https://github.com/RetroGamer74/NX_Payload_Forwarder) que yo mismo he desarrollado, utilizando el siguiente enlace [link](https://github.com/RetroGamer74/NX_Payload_Forwarder), y copialo en alguna carpeta de tu PC. Este payload no requiere de actualizaciones porque cuando lo ejecutes lo único que hace es cargar el payload que se encuentre en la microSD. Por tanto la funcionalidad de este payload es siempre la misma y de esa manera evitas tener que copiar el payload.bin que venga actualziado en la release de RetroReloaded.

Una vez descargado y copiado, usando un inyector de payloads como por ejemplo TegraRCMGui, ( ver CREDITOS ), selecciona el fichero de payload que descargaste anteriormente ( NX Payload Forwarder ). Conecta por cable USB-C tu Switch y tu PC. Entra en el modo RCM, usando tu JIG y realizando las pulsaciones de Vol+ y Power. Si no sabes cómo hacer esto puedes entrar en nuestro discord a pedir ayuda.

[Enlace a los foros de soporte de RetroGamer_74](https://discord.gg/cUnjkPH)

#### Usando Dongles

##### Usando el dongle de SX OS ( TX )

Desde la versión 3.50 se puede usar el dongle de SX OS para arrancar RetroReloaded. Pincha el Dongle y arranca como sueles hacer. En vez de arrancar SX OS arrancará el menú de RetroReloaded, a no ser que hayas activado en RetroReloaded la opción de Autoboot, en cuyo caso deberás mantener pulsado el botón Vol - para que aparezca el menú cuando se esté reiniciando.

##### Usando el dongle de R4S

Puedes usar el dongle R4i. Utilizando el siguiente enlace oficial a descarga flasheareamos un payload forwarder.

https://bit.ly/2EsOeKj

Conecta tu dongle R4S a tu pc utilizando el cable microUSB. Pon el dongle en modo de escritura flash pulsando dos veces seguidas el botón que tiene en una de sus esquinas. Esto hará que automaticamente aparezca la ventana del explorador de archivos de Windows, y una nueva unidad en tu sistema. Ahora lo unico que tenemos que hacer es copiar el archivo con la extensión UF2 directamente sobre la nueva unidad que nos aparece en el explorador de archivos. Podemos hacer drag & drop. Una vez que el archivo se termina de copiar el dongle se desconecta del modo flasheo, y la unidad del explorador desaparece. En ese momento tu dongle ya está programado.

### Puedo usar RetroReloaded para hackear mi Mariko?

Sí. RetroReloaded está preparado para que puedas arrancar tu Mariko con custom firmware.

Sigue este [vídeo](https://youtu.be/chbpxLs0Akc?t=328)

### Puedo usar AutoRCM?

Claro. La primera vez que arranques RetroReloaded puedes arrancar la herramienta Hekate. En su menú de Tools, abajo a la derecha encontrarás la opción de AutoRCM. Una vez la habilites la consola ya no arrancará automáticamente sino que se quedará metida en el modo RCM esperando la inyección del Payload, bien desde TegraRCMGUI y tu PC, o bien al pincharle un dongle. De esta forma te ahorras el JIG. Ya no es necesario.

### Se puede desactivar AutoRCM?

Por supuesto. De la misma manera que lo has activado, se desactiva. Entras en Hekate desde el menú de RetroReloaded y te diriges al menú de Tools. Abajalo a la derecha encontrarás la opción de AutoRCM que ahora la tendrás habilitada. Pulsas sobre ella y se desactiva.

### Qué son los 90DNS?

90DNS es un servicio de DNS que proporciona unas direcciones IP para ser usadas como DNS Primario y DNS Secundario. Ajustadas sobre la configuración de red de tu consola, impedirán que esta se conecte a los servicios de NN. Evitando así cualquier riesgo de baneo. En las últimas releases el modo Stealth de SX OS se ha mostrado comprometido así que no es garantía. Recomendamos a todos los usuarios a añadir 90DNS además de tener el modo Stealth activado.

DNS Primario: 163.172.141.219

DNS Secundario: 207.246.121.77

### Puedo usar incógnito ?

Sí. Para poder usar incógnito es necesario que la partición PRODINFO se encuentre en modo lectura escritura. RetroReloaded incluye un módulo que habilita esto para que la herramienta incógnito funciona. Desde la herramienta RetroReloaded Toolkit que encontrarás en el homebrew preinstalada, selecciona la opción Prodinfo y asegúrate de ponerlo en modo lectura escritura (RW). Después ya puedes ejecutar incógnito. Cuando acabes de hacer los cambios con incógnito, deberías volver a poner Prodinfo en modo sólo lectura (RO).

![alt text](RRToolkit1.JPG)

![alt text](RRToolkit2.JPG)


### Puedo usar Super Lan Play?

Por supuesto RetroReloaded está preparada para ser usada con Atmosphere y Super Lan Play.

### Puedo usar Emunand?

Sí. La emunand para Atmosphere tiene una integración especial en RetroReloaded. Una vez que la crees o la migres desde SX OS ( puedes usar este [vídeo](https://www.youtube.com/watch?v=WBO69FYA_UI) si quieres hacer compatible tu emunand de SX OS con Atmosphere ) aparecerá un nuevo botón en el Arranque de RetroReloaded, desde donde podrás activar o desactivar la emunand a la hora de arrancar.

Si quieres hacer una integración total y previamente tenías la emunand en SX OS, y ya has seguido el vídeo del enlace anterior y la has migrado a Atmosphere, recuerda que para hacerla compatible con atmosphere debes editar el archivo que hay en la carpeta emuMMC de tu microSD, que se llama emummc.ini y encontrarás unas líneas similares a estas:

[emummc]

enabled=1

sector=0x1a278800

path=emuMMC/RAW1

id=0x0000

nintendo_path=emuMMC/RAW1/Nintendo

Lo que tienes que hacer es cambiar las rutas path y nintendo_path a la carpeta Emutendo, que es la que originalmente utiliza SX OS en su emunand. Recuerda sólo debes hacer esto si quieres seguir usando la emunand tanto desde SX OS como desde Atmosphere. Aún así puede requerir la reinstalación de los juegos.

Por tanto el archivo quedaría así:

[emummc]

enabled=1

sector=0x1a278800

path=Emutendo

id=0x0000

nintendo_path=Emutendo


## Gestor de Arranque

Dependiendo de lo que necesites puedes utilizar los custom firmwares que están disponibles que son los siguientes.

**Primera Opción:**

**[Atmosphere]**

Actualmente 0.9.4.

Firmwares soportados: 1.0.0 - 9.0.1

Incluye soporte para jugar en Super Lan Play. Puedes jugar con tu Switch, incluso si está baneada, con otros jugadores en multiplayer. 

No es un servicio oficial. Lee bien las instrucciones y conéctate a nuestros foros de soporte en discord, porque hace falta cuenta para poder jugar.

[![Chat on Discord](https://camo.githubusercontent.com/b4175720ede4f2621aa066ffbabb70ae30044679/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636861742d446973636f72642d627269676874677265656e2e737667)](https://discordapp.com/invite/cUnjkPH)

http://lanboard.retrogamer.tech


**Segunda opción:**

**[ReiNX]**

Currently 2.4

Firmwares supported: 1.0.0 - 8.1.0

Incluye soporte para jugar en Super Lan Play. Puedes jugar con tu Switch, incluso si está baneada, con otros jugadores en multiplayer. 

No es un servicio oficial. Lee bien las instrucciones y conéctate a nuestros foros de soporte en discord, porque hace falta cuenta para poder jugar.

[![Chat on Discord](https://camo.githubusercontent.com/b4175720ede4f2621aa066ffbabb70ae30044679/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636861742d446973636f72642d627269676874677265656e2e737667)](https://discordapp.com/invite/cUnjkPH)

http://lanboard.retrogamer.tech


**Tercera opción:**

**[SX OS]**

Importante: Recuerda copiar tu license.dat en la raíz de tu microSD.

Firmware soportado: 1.0.0 - 9.0.1 (2.9.1 Beta)

Puedes jugar en Super Lan Play siempre que el servicio Lan Play del menú de opciones esté habilitado en SX OS y haya sido actualizado por los desarrolladores de SX OS.

## CREDITOS
**Atmosphere**

https://github.com/Atmosphere-NX/Atmosphere

**ReiNX**

https://github.com/Reisyukaku/ReiNX

**ArgonNX**

twitter: @Guillem_96

https://github.com/Guillem96/argon-nx


**TegraRCMGui**

https://github.com/eliboa/TegraRcmGUI/releases

**Switch Lan Play**

https://github.com/spacemeowx2/ldn_mitm/releases

**Hekate CTCaer**

https://github.com/CTCaer/hekate
