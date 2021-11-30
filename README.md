# LAB_3

# LAB_2 ANALISIS DE NODOS

# INTEGRANTES

Fernanda Mayorga, Stalyn Castellanos, Nicolás Reyes

# OBJETIVOS

## OBJETIVO GENERAL 


## OBJETIVOS ESPECIFICOS


# MARCO TEORICO


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

**RESULTADOS SIMULADOS**
- En primer lugar, procedemos a realizar el circuito esquemático en un simulador, para nuestro trabajo preferimos utilizar multisim.  
![image](https://user-images.githubusercontent.com/93398718/143966099-73e1bf52-b81f-4181-a1c1-bda7c3a13529.png)  
- Luego, guiándonos de los datos obtenidos en el análisis analítico y en la manera que se terminaron las posiciones de los nodos, se colocan los voltímetros y se marca el nodo de referencias, de tal manera que se obtiene lo siguiente.  
![image](https://user-images.githubusercontent.com/93398718/143966194-b78d532c-d78d-4701-a1c2-1f68f4576127.png)  
- El nodo 3 tiene más conexiones que los demás nodos por este motivo fue seleccionado como nodo de referencia, además el nodo 2 y 3 fueron seleccionados porque tienen conexiones con más de dos elementos.
Podemos apreciar que los resultados obtenidos no difieren demasiado con respecto a los resultados obtenidos de manera analítica y experimental, de esta manera podemos afirmar que existe un alto índice de exactitud. A continuación, se pueden apreciar los resultados en la siguiente tabla:  
![image](https://user-images.githubusercontent.com/93398718/143966569-9d15d347-e167-43f6-a63b-d349130da627.png)


# RESPUESTA A INTERROGANTES Y CALCULO DE ERROR 

**TABLA:**

| NODO | R. ANALITICO | R. EXPERIMENTAL | R. SIMULADO |
|--------|------------|-------------------|-------------|
| NODO A | 2.822 V |  | |
| NODO B | 4.802 V |  |  |


# VIDEO


# CONCLUSIONES


# BIBLIOGRAFIA

- Floyd, T. (2007). Principios de circuitos eléctricos. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) Analisis de circuitos Teoria y Practica. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
