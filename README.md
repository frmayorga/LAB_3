# LAB_3 ANALISIS DE NODOS

# INTEGRANTES

Fernanda Mayorga, Stalyn Castellanos, Nicolás Reyes

# OBJETIVOS

## OBJETIVO GENERAL 
- Aplicar el conocimiento adquirido por las leyes de Kirchhoff en el análisis de nodos, de manera que encontremos los voltajes de nodo por los métodos analítico, experimental y simulado.

## OBJETIVOS ESPECIFICOS

- Determinar mediante el análisis de los nodos en el circuito dado los voltajes de cada nodo.
- Analizar los resultados obtenidos he interpretarlos.


# MARCO TEORICO

![Metodo del Voltaje en Nodos](https://user-images.githubusercontent.com/93561706/143985788-977dc477-79b1-404d-b455-4ccfe9ef2e52.png)

**CODIGO DE COLORES PARA RESISTORES DE 4 BANDAS** 

| DIGITO | COLOR |
|--------|------------|
| 0 | Negro |
| 1 | Café |
| 2 | Rojo |
| 3 | Naranja |
| 4 | Amarillo |
| 5 | Verde |
| 6 | Azul |
| 7 | Violeta |
| 8 | Gris |
| 9 | Blanco |

TOLERANCIA : Oro +- 5%; Plata +- 10%.

# EXPLICACION DEL PROCEDIMIENTO

**Se utilizo los siguientes materiales:** 

| CANTIDAD | MATERIAL |
|--------|------------|
| 1 | Fuente de voltaje en C.D. |
| 1 | Multimetro Digital |
| 1 | Resistor de 1.8 Kilo-Ohmios |
| 1 | Resistor de 470 Ohmios |
| 1 | Resistor de 1.5 kilo-ohmio |
| 1 | Resistor de 3.9 kilo-ohmios |
| 1 | Resistor de 2.2 Kilo-ohmios |
| 1 | Protoboard |


Se procedio a armar el siguiente circuito en los simuladores multisim y tinkercad: 

![image](https://user-images.githubusercontent.com/93361435/143960870-d777d017-5920-42c2-a778-3ba25c56da6a.png)


**RESULTADOS ANALITICOS**

![parte analitica](https://user-images.githubusercontent.com/93361435/143960939-5719a018-73c7-4adc-9a6d-c7f8d22098e9.png)

Para la parte analitica se uso una calculadora online para resolver el sistema de ecuaciones lineales, antes de ello se realizo un anilisis del circuito usando el analisis de nodos en el cual se debe encontrar un nodo de referencia y a partir de este encontrar los voltajes en los nodos.

Como resultados obtenemos: 

![image](https://user-images.githubusercontent.com/93361435/143963516-e20ac28c-08dd-4daf-bfc3-0ff14b5d488d.png)

**RESULTADOS EXPERIMENTALES**
- En primer lugar, procedemos a realizar el circuito esquemático en un simulador, para nuestro trabajo preferimos utilizar multisim.  
![image](https://user-images.githubusercontent.com/93398718/143966099-73e1bf52-b81f-4181-a1c1-bda7c3a13529.png)  
- Luego, guiándonos de los datos obtenidos en el análisis analítico y en la manera que se terminaron las posiciones de los nodos, se colocan los voltímetros y se marca el nodo de referencias, de tal manera que se obtiene lo siguiente.  
![image](https://user-images.githubusercontent.com/93398718/143966194-b78d532c-d78d-4701-a1c2-1f68f4576127.png)  
- El nodo 3 tiene más conexiones que los demás nodos por este motivo fue seleccionado como nodo de referencia, además el nodo 2 y 3 fueron seleccionados porque tienen conexiones con más de dos elementos.
Podemos apreciar que los resultados obtenidos no difieren demasiado con respecto a los resultados obtenidos de manera analítica y experimental, de esta manera podemos afirmar que existe un alto índice de exactitud. A continuación, se pueden apreciar los resultados en la siguiente tabla:  
![image](https://user-images.githubusercontent.com/93398718/143970203-3036fbcd-e1a0-42db-810a-997b277db9a1.png)


**RESULTADOS SIMULADOS**

- En primer lugar, procedemos a realizar el circuito en un simulador en este caso utilizamos tinkercad paro poder hacerlo de una mejor manera.
- Colocamos los elementos necesarios como son las resistencia y las fuentes de voltaje. 

![image](https://user-images.githubusercontent.com/93561706/143967185-85bfb375-4685-43ff-9cac-16d0b4a0a98f.png)

-Como observamos para poder determinar los valores de los voltajes en los nodos, tenimos que medirlo con respecto a la tierra en este caso nuestra tierra es nuestro nodo de referencia, una vez que ya obtuvimos los valores procedemos a colocarlo en nuestra tabla.

| NODO | R. ANALITICO | R. EXPERIMENTAL | R. SIMULADO |
|--------|------------|-------------------|-------------|
| NODO A | 2.822 V | 2.8203 V | 2.82 V|
| NODO B | 4.802 V | 4.802 V | 4.80 V |

-Como observamos los valores son muy similares lo unico que cambia son las cifras significativas, pero esto no significa que esta muy alejado ya que todos los resultados tanto en la parte analitica, sistematica y del simulador son similares. 

# RESPUESTA A INTERROGANTES Y CALCULO DE ERROR 

**TABLA:**

| NODO | R. ANALITICO | R. EXPERIMENTAL | R. SIMULADO |
|--------|------------|-------------------|-------------|
| NODO A | 2.822 V | 2.8203 V | 2.82 V|
| NODO B | 4.802 V | 4.802 V | 4.80 V |


# VIDEO


# CONCLUSIONES

- El análisis de nodos es de gran importancia pues nos permite determinar el voltaje que regula cada uno de los resistores aplicando las leyes de Kirchhoff, específicamente la ley de las corrientes, que facilita de gran manera el cálculo de este tipo de problemas tomando en cuenta ciertas consideraciones, como que siempre que se aplique este método debe existir un nodo de referencia el cual por conveniencia siempre es el que tiene conexión con más elementos del circuito y el voltaje de este nodo siempre será igual a cero.

- Haciendo uso de las plataformas tinkercad y multisim logramos comprobar los resultados obtenidos de manera analítica, además pudimos notar que los resultados no varían demasiado, es decir, que su variación es mínima, y, por ende, existe un gran nivel de exactitud. también pudimos notar que el voltaje medido del nodo de referencia es igual a cero.


# BIBLIOGRAFIA

- Floyd, T. (2007). Principios de circuitos eléctricos. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) Analisis de circuitos Teoria y Practica. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
