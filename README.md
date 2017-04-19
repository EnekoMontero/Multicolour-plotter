# Multicolour-plotter
3D To 2D. Use a Prusa i3 as plotter. Up to 6 colours in v1.0
![alt text](https://github.com/EnekoMontero/Multicolour-plotter/blob/master/Imagenes/Multicolour-plotter.jpg "Version 1.0 del plotter")

## Objetivo
- Crear un plotter que sea capaz de dibujar en varios colores (6 en la primera versión) sin intervención del usuario.
- Que no sea necesario cambiar el firmware, únicamente añadiendo un servo sg90 en el pin D11.
- Hacer dibujos muy chulos.
- Aprender cosas nuevas.

## Modo de funcionamiento
Aclaración: Este modo no es ni el mejor ni el peor, es uno que se me ha ocurrido. Con CNCs he trabajado muy poco, estoy más cómodo en impresión 3D, por lo que mi cabeza piensa así.
Mi idea es que el diseño sea un STL en el que cada capa sea un color. Luego realizar un script de python que te convierta el gcode que has fileteado como siempre a un nuevo gcode que te cambie los rotuladores. El truco está en buscar el cambio de capa para introducir los comandos a dejar rotulador y coger rotulador.

## To-Do List
- Crear script para convertir el gcode del objeto 3D al gcode del dibujo multicolor.
- Mejorar método de agarre para que el rotulador permanezca fijo durante el proceso.
- Dibujar con muchos colores.

## Vídeos de pruebas realizadas
- [1er Test: Test en vacío usando varios rotuladores](https://www.youtube.com/watch?v=smSGIGMu_bk)
- [2o Test: Test Pick & Place](https://www.youtube.com/watch?v=2m39z0g3RdI)
- [3er Test: Test pintando con dos rotuladores](https://www.youtube.com/watch?v=vBUHGIYiAxE)

## Instrucciones de montaje
1. Imprimir:
	1x engranaje_servo.stl
	1x engranjeaux.stl
	1x pinzadcha.stl
	1x pinzaizda.stl
	1x servo.stl
	1x soporterotuladores.stl

2. Montar el enganche del servo como se ve en las imágenes 3D.
![alt text](https://github.com/EnekoMontero/Multicolour-plotter/blob/master/Imagenes/montaje3d.JPG "Montaje 3D")
![alt text](https://github.com/EnekoMontero/Multicolour-plotter/blob/master/Imagenes/montaje3d_2.JPG "Montaje 3D 2")

3. Atornillar el soporte de rotuladores, si tienes base caliente en los puntos (100,0) y (200,0) "mas o menos". Si no, puedes usar una plancha de madera fina u otra cosa. Eso como prefieras.

## Licencia
GPL license or Creative Commons Attribution-shareAlike (Copyleft)

# Autor
Eneko Montero