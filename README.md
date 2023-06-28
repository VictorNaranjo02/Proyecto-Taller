# Transformando Fila-Mentes
_Víctor Naranjo Cifuentes_ & _Juan Sebastián Bohorquez_
### Descripción
Este es un proyecto para la asignatura de taller de ingeniería electrónica el cual se basa en la fabricación de una maquina transformadora de PET en filamento para impresión 3d
### Problemática
En las últimas décadas la industria de la impresión 3d se ha venido expandiendo y se ha vuelto más frecuente, tanto así que ahora nos es posible tener una impresora 3d en nuestras casas, claro está que con un precio un poco elevado.
Debido a esto ha surgido la necesidad de buscar nuevos materiales para la impresión 3d y uno de los más populares es el PETG, quien gracias a sus siglas PET (tereftalato de polietileno) se puede saber que es un polietileno (plástico), el cual es uno de los plásticos más utilizados en el mundo y comúnmente se utiliza en la fabricación de envases de bebidas. Este PET gracias al proceso de glicosilación, proceso que permite la unión de carbohidratos a proteínas, adquiere unas características que le permiten termoformarse y le dan una mejor resistencia.
Además, el PET al ser un material tan común, ocasionalmente tiende a desecharse, lo cual causa una mayor contaminación y daño al ambiente. Es por lo anterior, que el proyecto de Transformando Fila-Mentes tiene la intención de reusar las botellas PET, a través de una máquina que transforma las botellas en filamentos, para su uso en las impresiones 3D. Así propiciando una mayor vida útil de estos materiales que afectan al ambiente e  impulsando maneras alternativas en el uso de la impresión 3D.
### Alcance
Como resultado del proyecto tendríamos la máquina de filamentos, esta se basó principalmente en el modelo de Leandro Mantirgano (https://github.com/VictorNaranjo02/Transformando_Fila-Mentes/blob/main/Maquina%20inspiracion.jpg), con sus respectivos cambios, los cuales consisten en el cambio del regulador de temperatura manual a uno digital, el control de la velocidad del motor manual (potenciómetro) por uno digital (a través de codigos en python) y el cambio de componentes por el microcontrolador esp32, el cual nos permite controlar varias funciones a través del lenguaje de programación, en este caso específico microphyton.
### Objetivos
Planteamiento de la máquina
Diagrama de cajas negras
Diagrama de tecnología
Esquemático del circuito
Elaboración del circuito
Elaboración de la estructura
Ensamblaje de la máquina
Resultados
Conclusiones
### Materiales
- 1 Esp32 V1
- 1 driver a4988
- 1 motor paso a paso mitsumi (a106)
- 1 termistor de 100k
- 1 cartucho calefactor 
- 1 bloque calefactor
- 1 fuente de poder de 12v
### Diagrama de caja negra
[Diagrama_de_Cajas_Negras.jpg](https://github.com/VictorNaranjo02/Transformando_Fila-Mentes/blob/main/Diagrama_de_Cajas_Negras.jpg)
### Ideas de Tablero
Con ayuda del profe surgieron ideas para las tecnologias a implemetar https://github.com/VictorNaranjo02/Transformando_Fila-Mentes/blob/main/Tablero.jpg
### Diagrama de caja negra (con tecnológia)
A partir del diagrama de cajas negras y las charlas con el profe, se obtiene el diagrama de la tecnologia a disponer en el proyecto 
https://github.com/VictorNaranjo02/Transformando_Fila-Mentes/blob/main/Diagrama%20tecnologia.jpg
### Apartado Kicad
Con la ayuda de la herramienta Kicad se realizo el esquematico electrico del proyecto, tal que https://github.com/VictorNaranjo02/Transformando_Fila-Mentes/blob/main/Esquematico%20electrico.jpeg
### Codigo Python
Para el manejo de la velocidad en el motor paso a paso se utilizo la herramienta de micropython en la Esp32, lo cual no permite tener un control de la velocidad del motor de manera digital. Para esto se hizo uso del codigo https://github.com/VictorNaranjo02/Transformando_Fila-Mentes/blob/main/Codigo%20Python
### Link del video de Youtube (donde se explique la implementación del proyecto)
https://docs.google.com/presentation/d/1lC93OKbK18KAW_jD2Hf-klyL_9yhNtIW/edit?usp=sharing&ouid=104707535118213430211&rtpof=true&sd=true
### Conclusiones

### Referencias
Cambatronix Online. (2022, Noviembre 12). MicroPython para ESP32 #10 : Termistores NTC. YouTube. https://www.youtube.com/watch?v=7SpQ0ttJr3A&ab_channel=CambatronicsOnline
Hachi Quintana, J. G., & Rodríguez Mejía, J. D. (2010). Estudio de factibilidad para reciclar envases plásticos de polietileno tereftalato (PET), en la ciudad de Guayaquil. Estudio de factibilidad para reciclar envases plásticos de polietileno tereftalato (PET), en la ciudad de Guayaquil. https://dspace.ups.edu.ec/bitstream/123456789/2450/20/UPS-GT000106.pdf
iobotic. (2020, Agosto 9). Como instalar microPython en la ESP32 - FÁCIL - V1. YouTube. https://www.youtube.com/watch?v=RLqPB1PM6gE&list=PL7qLO1tt1gJ6_qTBv6RtBqPnl7uRzyk_R&index=6&ab_channel=iobotic
Programador Novato. (2022, Noviembre 8). Enviar datos al ESP32 vía Bluetooth con App Inventor. YouTube. https://www.youtube.com/watch?v=l10NGNCGUBc&list=PL7qLO1tt1gJ6_qTBv6RtBqPnl7uRzyk_R&index=13&ab_channel=ProgramadorNovato
Sampallo, G. (2019, Marzo 22). MicroPython - Control de motor paso a paso con A4988. YouTube. https://www.youtube.com/watch?v=0L2vNh2fi-M&list=PL7qLO1tt1gJ6_qTBv6RtBqPnl7uRzyk_R&index=11&t=84s&ab_channel=GuillermoSampallo
XY.3D. (2022, Julio 7). Construye tu propia máquina para fabricar filamento 3D a partir de botellas. YouTube. https://www.youtube.com/watch?v=u7IBrJk_kgg&list=PL7qLO1tt1gJ6_qTBv6RtBqPnl7uRzyk_R&index=2&t=50s
