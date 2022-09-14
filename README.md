# sketchApoyadoFreeCAD

In FreeCAD, create an INDEPENDENT sketch (not Part Design) supported by a face

En FreeCAD, crea un sketch (sin ser de Part Design) apoyado en una cara pero sin depender de ella.


## Agradecimientos

Sebastián Ernesto García


## Funcionamiento

Este script para FreeCAD consta de dos scripts. El primero realiza un sketch basado en una cara (que no sea de Part Design), pero sin dependencia a esa cara. El segundo cambia la posición de la cara por una nueva.

Con un ejemplo:

Se puede crear cualquier objeto en FreeCAD hecho con Part. Se selecciona una cara del objeto, y se pulsa el icono correspondiente al primer script. Entonces creará un sketch en esa cara, sin dependencias. Esto es, si borramos el objeto base, el sketch se mantiene y además NO generará ningún error.

Si queremos asociar ese sketch a una nueva cara, seleccionaremos la nueva cara, y el plano de referencia que estaba asociado al sketch, y pulsaremos el icono del segundo script (el que tiene símbolo de recargar amarillo), lo que posicionará el sketch en la nueva cara.

Todo ello, sin depender del body de Part Design.
