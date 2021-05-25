## Introducción y ¿Qué es Linux?
Linux es una familia de sistemas operativos (como el sistema operativo Windows) basados todos en el *kernel Linux*, de software libre y similares al primer sistema operativo portable *Unix*. Probablemente no han entendido mucho y piensen que Linux es una familia compleja y extraña, pero no se deben preocupar porque en esta página web creada para todos los interesados en aprender, profundizar o conocer de este gran grupo, les explicare todo paso a paso y de una forma fácil y sencilla de entender.

## Linux bajo la lupa
Linux esta compuesto de muchas partes, partes que al ser la mayoria de software libre (software cuyo código todos podemos ver, como ya veremos) se pueden personalizar derivando en muchas mas partes con un mismo fin. A continuacion veremos la mayoria de estas partes, desarolladas por una gran cantidad de personas alrededor del globo, y cuyas combinaciones en conjunto forman los miembros de la familia Linux.
### El Kernel o Núcleo
Linux al igual que Windows, MacOS y otros, tiene un kernel, un software fundamental para el funcionamiento de los sistemas operativos, tal como lo es un motor para un auto. El kernel es encargado de facilitar a los programas mediante operaciones llamadas *primitivas* un *acceso* seguro al *hardware* de la computadora. Además, se encarga de gestionar los recursos de las computadora, y de decidir y permitir el tiempo, los recursos y el uso de estos para cada programa. 
Esta familia de sistemas operativos de software libre estan basados todos en el kernel que lleva su mismo nombre (De hecho Linux basa su nombre de su kernel, no al contrario). Este kernel es mayormente de software libre, ya que también incluye *blobs binarios* (software cuyo código no es libre) como por ejemplo algunos drivers para controlar y comunicarse con algunas partes del computador. Así mismo el kernel es monolítico, modular o por partes, multitarea, parecido al kernel de Unix, y multiplataforma y portable para cualquier computador que tenga una versión del compilador (programa que traduce el código a binario) GCC.
### El Software
Ahora que ya conocimos el kernel, es momento de conocer brevemente el software, el cual nos permite realizar tareas en el sistema operativo. Este software es creado por muchas personas y se agrupa en colecciones. Además, así como el kernel de un sistema operativo es la base para otro software "más alto", hay otro soporte de programas básicos para otros programas más altos y más complejos en esta jerarquia, conocido como coreutils, y que también pertenece a las colecciones. 
La principal colección es GNU, de la cuál se han basado otras colecciones, y que también es parecida al software de Unix pero distinto de él, por lo que el acrónimo de GNU es GNU's Not Unix, o en español GNU no es Unix. De hecho GNU fue el primero en acoplarse a Linux, y crear y seguir creando gran parte de los sistemas operativos. Además GNU fue quién inicio el movimiento de software libre.
Por último, algo que resaltar es una controversia generada al referirse a los miembros de Linux y GNU, ya que muchas veces solo se menciona a Linux, y no al conjunto completo GNU/LINUX.
### Entornos de Escritorios
Para usar un sistema operativo se requiere de una interfaz, las más comunes son interfaces de linea de comandos (CLI) y las interfaces gráficas (GUI). Las interfaces gráficas utilizan una metáfora de escritorio para acceder a las aplicaciones, carpetas o documentos; En Linux hay muchos entornos de escritorios con distintas tecnologías, iconos y funciones. Entre los más destacados esta el escritorio GNOME, KDE, Xfce, y Cinnamon.
A continuación los voy a describir brevemente:
* GNOME (link)
GNOME es uno de los más importantes y usados. Entre sus principales características se destaca su simplicidad y su po tencia por lo que se centra en equipos de alto rendimiento. En un principio GNOME se creo para formar parte del proyecto GNU. Actualmente y hace poco se ha lanzado la versión de GNOME 40. 
(Imagen)

* KDE (link)
KDE es otro de los más importantes, se asemeja a Windows y tiene una interfaz visualmente interesante y muchas características. Sin embargo consume una gran cantidad de recursos.
(Imagen)

* Xfce (link)
Xfce es un entorno tradicional y bastante ligero. Xfce sus propios programas básicos ligeros y algunos de GNOME.
(Imagen)

* Cinamon (link)
Cinamon se baso en parte en GNOME pero fue diseñado para el miembro de la familia de Linux, distro o distribución: Linux Mint. Es un escritorio flexible y combina un diseño tradicional con características avanzadas. 
(Imagen)

### Instalación de Aplicaciones
Para instalar aplicaciones en Linux, estas se dividen en paquetes que pueden servir también para otras apps. Hay tres métodos para instalarlas, el primero es el más complejo y consiste en descargar el código de la app, y ya sea ejecutar el instalador que trae, o compilarlo (traducir el código fuente en código binario) y luego instalarlo. El segundo  método es instalar un paquete ya generado para la distribución o miembro de Linux (por ejemplo .deb para Debian). Y el tercero consiste en utilizar un programa que viene por defecto en todas las distros conocido como gestor de paquetes, y que se encarga de comunicarse con un repositorio o colección de software guardada en un servidor, y descargar los paquetes e instalarlos.

## Historia
Ahora vamos a conocer brevemente la historia de Linux:
### Unix
Antes y por como hemos visto que Linux y la mayoría de sus partes estan basadas en Unix, hemos de conocer su historia. Unix empezó en 1969 de la mano de un grupo de empleados de los laboratorios Bell de AT&T. Luego fue vendido junto con todos sus derechso a Novell, Inc, quien lo vendió a Santa Cruz Operation en 1995, y quien lo revendió a su vez a Caldera Software en 2001. Durante este periodo de tiempo Unix tuvo un clon llamado Minix creado por el científico de la computación Andrew S. Tanenbaum en 1987.
### Linux
Linux el kernel, fue creado en 1991 por Linus Torvalds de 21 años, quien empezó con unas simples ideas para un sistema operativo también libre. Él empezo no diseñando el software del que hemos hablado sino el kernel, tomando como base a Minix, y requiriendo de su uso para funcionar. El mismo año y en un grupo de noticias Torvalds escribio de su proyecto, y tras dicho mensaje muchas personas comenzaron a ayudar con el código, y fue en septiembre de 1991 cuando se lanzo la versión 0.01 de Linux. Este comienzo de Linux fue criticado por el creador de Minix Tanenbaum, quien le delato a Torvalds sus errores al crear un kernel demasiado compacto, cosa que acepto creyendo que Linux no tendría futuro. 
Actualmente su versión es la 5.8 y su mascota es Tux el pinguino.
### GNU 
De GNU no solo se puede hablar de software, pues tiene un trasfondo no solo respecto a los sistemas operativos. GNU empezo en 1983 liderado por el experto informático y activista estadounidense Richard Stallman auxiliado por una gran cantidad de académicos y programadores voluntarios. Su objetivo en el comienzo fue crear completamente un sistema operativo libre basado en Unix, pero ahora se ha vuelto una tarea secundaria y su objetivo actualmente es la promoción del movimiento del software libre con ayuda de la Free Software Foundation también creada por Stallman, y la manutención de GNU. Para complementar, durante el objetivo de crear un sistema operativo libre, Richard Stallman y su equipo después de crear el software, les falto un kernel, probaron varias opciones hasta llegar a Linux y crear GNU/Linux.
La mascota de GNU es Gnu

## Distribuciones de Linux
Linux como han leido tiene miembros debido a que es software libre. Estos miembros también llamados distros o distribuciones son muchos, muy variados y con muchos objetivos. A continuación podrán conocer algunos de ellos y bajo que licencia de código estan:
### Licencias del Codigo
El software libre, aquel cuyo código se puede ver y leer y que además por esta característica tiene mayor seguridad y se le puede fiar más, se divide en licencias, algunas de estas son:

* Open Source o Código Abierto
El código abierto u open source es aquel que es hecho gratuitamente y abiertamente para su modificación y redistribución pero también con ciertas condiciones escritas en más licencias.

* GPL o General Public License
La licencia GPL de la Free Software Foundation es una licencia de derecho de autor ampliamente usada en el software libre, que autoriza la libertad de uso, de acceder al código fuente, de distribuirlo y modificarlo, siempre que conjuntamente con otras características se redistribuya el programa completo (modificado o no modificado) bajo la misma licencia. 

* MIT License 
Esta licencia originada en el MIT es una licencia de software permisiva, lo que quiere decir que impone muy pocas limitaciones en la reutilización del código, proveyendo de esta forma una buena compatibilidad de licencia. 

* Debian/Ian Murdock/Debian Project/1993/propósito general/ninguno
* Ubuntu/Canonical Ltd./Canonical Ltd./2004/escritorio, servidor/Debian
* Linux Mint/Clement Lefebvre/dev team/2006/escritorio/Ubuntu
* openSUSE/SUSE Linux & Novell//Novell & openSUSE community/1994/escritorio/SUSE Linux
* Red Hat Linux/Red Hat/Red Hat/1995/servidor, workstation/ninguno
* Fedora/Fedora project/Fedora project/2003/propósito general/Red Hat Linux

## Usos de Linux y ¿Cómo Probarlo?
Linux por ser software libre principalmente es usado en servidores, pero también en escritorios. Si desean descargar Linux deberían probarlo antes,  para ello se puede descargar en una memoria usb mediante programas como Rufus, también se puede ejecutar como máquina virtual en el sistema operativo actual o se puede ejecutar en un servidor remoto. Así mismo es importante y los animo a seguir aprendiendo de este gran sistema operativo y su gran poder.