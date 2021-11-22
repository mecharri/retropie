# Compatibilidad
https://retropie.org.uk/about/building/

* Compatible con Raspberry Pi (A, A+, B, B+, Zero, 2, 3, 4)
* Se recomienda Raspberry 3 o 4
* 5V 2.5A Power supply
* 8GB Micro SD Card Minimum

# Materiales necesarios:

* Computer (or laptop)
* Raspberry Pi
* MicroSD card (see compatible SD cards)
* Screen (TV, computer monitor, projector, etc) - anything with HDMI or RCA
* Video cable, Pi 1, 2, and 3 will need a full-size HDMI cable
* Power supply
* Game controller of your choice

# Instalación
## Descarga:
* Bajé la versión: pre-made image of RetroPie is v4.7. 
* Versión  para Raspberry 0/1
* Instalada con raspberri pi imager. Nota: el raspberry pi imager lo descarga automáticamente si no se tiene la imagen.

# Encendido
## Primera prueba:
Al prender da algunos errores y se cuelga con un error. Reinicio para anotar los errores
## Reinicio
Al reiniciar inicia correctamente, detecta que no hay gamepads. Pruebo con tecladito portatil. El teclado funciona pero no el mouse incorporado. 
* Pruebo el teclado en la laptop, fuinciona el mouse y el teclado.
## Otro inicio
* Intento reiniciar con el tecladito puesto a ver si toma el mouse al iniciar => No hay mouse
* Coloco mouse USB => No hay mouse 
* Pruebo: cat /dev/input/mice  => Hay log cuando muevo el touchpad
* El tecladito se vuelve loco (ya me habia pasado con otros dispositivos)
* Pongo un teclado inalambrico, funciona corretamente, mouse no hay => Supongo que no hay puntero mouse

# Uso

## ROMs
* No hay ROMs, hay que agregarlas
* 
