# MinCloud: actualizaciones

Paquetes de actualización de MinCloud, cifrados y firmados.

Este repositorio **no contiene el programa**. Los archivos de `paquete/` solo los puede abrir
un MinCloud ya instalado, con la clave que trae su instalador. Sin esa clave no se pueden leer
ni se pueden fabricar actualizaciones válidas.

- `actualizacion.json`: versión publicada, huella de cada archivo y firma.
- `paquete/`: archivos cifrados que cambiaron en las últimas versiones.
