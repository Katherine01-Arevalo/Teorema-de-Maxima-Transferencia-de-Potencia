# Teorema-de-Maxima-Transferencia-de-Potencia

**1.OBJETIVOS**

Generales:

•	Identificar teórica y experimentalmente el Teorema de la Máxima Transferencia de Potencia.

•	 Probar de manera experimental el Teorema de Máxima Transferencia de Potencia. 

Específicos:

•	Identificar el valor de la resistencia interna de la fuente de voltaje y de la resistencia de carga. 

•	Calcular la potencia generada por la fuente para cada resistencia de carga. 

•	Especificar el valor de la resistencia de carga para el cual existe la mayor transferencia de potencia. 

•	Demostrar el cumplimiento del Teorema de Máxima Transferencia de Potencia. 


**2.MARCO TEÓRICO**

![Transferencia de potencia](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/Transferencia%20de%20potencia.png)

![Grafico_potencia](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/Grafico_potencia.png)

En la imagen se puede ver la curva de la transferencia de potencia donde la transferencia máxima de potencia se da cuando el valor de la resistencia de carga es igual al de la resistencia interna de la fuente.  

**3.DIAGRAMAS**

![circuito](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/circuito.png)

**4.LISTA DE COMPONENTES**

![lista](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/materiales.png)

**5.EXPLICACIÓN**

TEÓRICA:

Se tiene un circuito equivalente de Thévenin, cuya fuente de voltaje es de 15V. y su resistencia equivalente de Thévenin tiene un valor de 1.2 kOhm. Tenemos diez diferentes valores de resistencias de carga (0.22, 0.47, 0.68, 0.82, 1, 1.5, 1.8, 2.2, 3.9, 4.7) cuya unidad de medida son kOhm. 

Se incluye la primera resistencia de carga de 0.22 kOhm al circuito equivalente. Calcular el voltaje en la resistencia de carga que debido a que es un divisor de voltaje, el voltaje ahí va a ser diferente al de la fuente. También es necesario calcular la corriente usando el valor del voltaje de la fuente y de la corriente total. Luego se calcula la potencia haciendo uso de cualquiera de las tres formulas existentes, I*V, V^2/RL, I^2*RL.  Repetir el mismo proceso para cada valor de la resistencia de carga. 

Realizando estos cálculos se podrá observar que conforme el valor de la resistencia de carga se acerca al valor de la resistencia interna de la fuente, que va a ser la misma que la resistencia equivalente de Thévenin, el valor de la potencia incrementara. Cuando el valor de la resistencia de carga es igual al de la resistencia interna de la fuente se presentará la máxima potencia que podrá ser transferida. Por otro lado, cuando el valor de la resistencia de carga excede el valor de la resistencia de Thévenin la potencia ira decreciendo. 

PRÁCTICA:

En cualquier simulador de circuitos eléctricos puede ser Proteus, Tinkercad o cualquier otro se arma el circuito equivalente de Thévenin con la fuente de 15V. y la resistencia equivalente de 1.5 kOhm. Se debe incluir un voltímetro para medir el voltaje en la carga, un amperímetro para medir la corriente y un medidor de potencia. Luego se añade cada resistencia de carga. Al iniciar la simulación se podrá observar si los valores calculados se asemejan a los valores de la simulación. Si los cálculos están bien y el circuito de la simulación esta bien armado los valores obtenidos deben ser los mismos o al menos similares. De lo contrario en algún lado hay un error. 

De igual manera, con la simulación se podrá corroborar que mientras el valor de la resistencia de carga se asemeja al de la resistencia interna de la fuente la potencia incrementara hasta legar al punto máximo cuando las dos resistencias son iguales. Pero cuando el valor de la carga se aleja la potencia menorara. 



**6.APORTACIONES**

Simulación para  la resistencia de carga  de 220 Ohm

![simulacion](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/simulacion.png)

![resultados](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/potencia.png)

![errores relativos](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/errores.png)


PREGUNTAS

¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.

Si se cumple  el teorema de Máxima Transferencia ya que para los valores  muy grandes y los valores muy pequeños  la potencia es mínima y para los valores que se aproxima a la resistencia de 1200Ω se observa la máxima transferencia de potencia.

![GRAFICA](https://github.com/Katherine01-Arevalo/Teorema-de-Maxima-Transferencia-de-Potencia/blob/main/img/grafica.png)

¿Cuál fue la potencia máxima en RL?

0.04 Watts

¿Para qué valor de RL se obtiene la MTP?

Para la resistencia en de 1000 a 1500 Ω


**7.MANUAL DE USUARIO** 

**8.PRERREQUISITOS**

- Al instante de generar la simulación tener en cuenta la unidad de media para el uso del amperímetro y el voltaje a utilizar.
- En el uso del vatímetro tener en cuenta  a que terminal se conecta la parte de la corriente(serie) y la parte del voltaje (paralelo).
- Verificar que el circuito se encuentre bien conectado, caso contrario se generaran datos erróneos.


**9.CONCLUSIONES**

Finalmente se llega a corroborar el teorema de  máxima  transferencia de potencia el cual dice que cuando la resistencia de  carga es igual al valor de la resistencia de la fuente se va a obtener su valor máximo de potencia mediante el análisis del circuito realizado previamente se observó de manera practica que para resistencias menores a 1.2 KOhm y mayores a la misma los valores de la potencia eran mínimos. Por lo cual se concluye que; para que experimente la máxima potencia  en el circuito el valor de la resistencia de carga debe ser de 1.2 KOhm , los valores que se asemejan  a esta resistencia  llegan a obtener una potencia relativamente máxima.

**10.BIBLIOGRAFÍA**

-Teorema de máxima transferencia de potencia. (2016, 5 diciembre). [Vídeo]. YouTube. https://www.youtube.com/watch?v=uPcY8fedBdA

-Floyd, Thomas L., (2007). Principios de circuitos eléctricos. México. PEARSON EDUCACIÓN.

**11.ANEXOS**
