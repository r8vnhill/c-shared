# CShared

_CShared_ is an implementation of a concurrent message sharing system, based on _nSystem_, during the course of Operating Systems on the Spring semester of 2019.

## nSystem
Below is the original documentation of _nSystem_ written by Luis Mateu:

Este es nSystem2001

Esta distribucion viene con los makefiles preparados para Linux,
pero Ud. debe compilar la biblioteca para poder utilizarla.

Instrucciones:

Defina la variable NSYSTEM con el directorio en donde se encuentra
el nSystem.  Esto se hace en csh con el comando:

    setenv NSYSTEM <directorio de nSystem>

Los makefiles dependen de esta variable de ambiente para poder
compilar exitosamente algunas aplicaciones.

Para compilar nSystem2001 debe ejecutar:

    % cd $NSYSTEM/src
    % make

Para usar nSystem debe cargar sus programas con la biblioteca
de nSystem que se encuentra en "$NSYSTEM/lib/libnSys.a".

Utilice los makefiles de ejemplo que aparecen en los directorios ex-*
(pero no olvide definir la variable NSYSTEM!).

src: el codigo de nSystem
doc: la documentacion de nSystem (explica que' es lo que hay en src).
lib: la biblioteca (libnSys.a)
include: ahi se encuentra nSystem.h

ex-msgs, ex-sems, ex-monitors, ex-io: ejemplos de uso de mensajes,
   semaforos, monitores y E/S no bloqueante, respectivamente.

games: juegos varios que usan tareas.

equiv: Ejemplo para mostrar que todas las primitivas de sincronizacion
   son equivalentes.  En este directorio se implementan semaforos a
   partir de mensajes.
