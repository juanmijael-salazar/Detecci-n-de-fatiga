# Detección del estado fisiológico del ojo para captar la fatiga en conductores

## Hipótesis
• La fatiga y la somnolencia influyen de manera significativa en accidentes de tránsito.

• Existen sistemas y algoritmos que reconocen la fatiga y somnolencia en conductores
gracias a la visión computacional

• No todos los algoritmos de detección de fatiga son fiables y muy eficaces para un
escenario de conducción, más cuando se toman en cuenta factores como la luminosidad,
contraste, balance de blancos, etc.

## Metodología
Para poder evaluar los resultados obtenidos por las fases se analizó cada fotograma de cada uno
de los videos proporcionados por la base de datos NTHU-DDD (Driver Drowsiness Detection
Dataset) y para la validación de la propuesta de mejor solución se harás uso de indicadores como:
la precisión media que es (AAC) y tasa de detección (DR) de acuerdo a las ecuaciones (7) y (8)
respectivamente, estas dos medidas propuestas no ayudará a evaluar la exactitud e indicar que
algoritmo propuesto es el más aceptable en cuanto a la detección de fatiga y somnolencia en
conductores al momento de conducir un vehículo motorizado, para esto se hará una matriz de
confusión donde:

![](https://github.com/juanmijael-salazar/Deteccion-de-fatiga/blob/main/imagenes/metodo.png)

![](https://github.com/juanmijael-salazar/Deteccion-de-fatiga/blob/main/NTHU-dataset-including-22-subjects-with-different-of-ethnicities.jpg)
![](https://github.com/juanmijael-salazar/Deteccion-de-fatiga/blob/main/imagenes/img2.png)

## Precisión de algoritmos
![](https://github.com/juanmijael-salazar/Deteccion-de-fatiga/blob/main/imagenes/conclusiones%20matrix.png)

## Salida de código
![](https://github.com/juanmijael-salazar/Deteccion-de-fatiga/blob/main/imagenes/deteccion%20somnolencia.png)
