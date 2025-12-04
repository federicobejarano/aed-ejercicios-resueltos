# Resolución de ejercicios AED - Parcial 1 (Recuperatorio)

Acá llevo el registro de los ejercicios resueltos...

---

## 1. **Elementales**

### 1.1. [Datos y Estructuras](https://aed-frre.github.io/practica/1.1/)

#### Estructuras Secuenciales

- Completado: 1/7

| Ejercicio | Observaciones |
| --------- | ------------- |
| 1.1.5.7   |               |

###### I. Ejercicios Fundamentales

Estos ejercicios se centran en la aplicación directa de estructuras condicionales básicas (`Si...Entonces...FinSi`) y las estructuras repetitivas más simples (repeticiones fijas o por conteo, e introducción a la acumulación). Son esenciales para dominar antes de un examen.

| Hecho | Orden  |                                                                Ejercicio                                                                 | Consigna                                                                                                                         | Requisitos Clave                                       | Fuente |
| :---: | :----: | :--------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------- | :----- |
|  ✅   | **1**  | [1.1.19](https://github.com/federicobejarano/aed-ejercicios-resueltos/blob/main/1_1_b_condicionales-y-repetitivas/ejercicio_1.1.19.txt)  | Ingresar una variable V y emitir su valor, su cuadrado y su cubo                                                                 | **E/S y Aritmética básica**                            |        |
|  ✅   | **2**  | [1.1.11](https://github.com/federicobejarano/aed-ejercicios-resueltos/blob/main/1_1_b_condicionales-y-repetitivas/ejercicio_1.1.11.txt)  | Dado un año, emitir si es 'ACTUAL', 'PASADO' o 'FUTURO'                                                                          | **Condicional Simple** (comparación)                   |        |
|       | **3**  |                                                                  1.1.10                                                                  | Determinar si A es divisor de B o B es divisor de A                                                                              | **Condicional Simple** (operación módulo)              |        |
|       | **4**  |                                                                  1.1.7                                                                   | Calcular una suma de dos números e imprimir mensaje según rangos (Suma $\le 50$, $50 < \text{Suma} \le 100$, etc.)               | **Condicional Múltiple** (rangos)                      |        |
|       | **5**  |                                                                  1.1.9                                                                   | Determinar si una suma de dólares ahorrada es suficiente para una cantidad de euros requerida, calculando la diferencia en pesos | **Aritmética, Condicional y Conversión**               |        |
|  ✅   | **6**  | [1.1.6](https://github.com/federicobejarano/aed-ejercicios-resueltos/blob/main/2_1_secuencias-de-datos-elementales/ejercicio_2.1.06.txt) | Ingresar 3 valores numéricos y determinar cuál es el mayor, el medio y el menor                                                  | **Condicional Anidada** (ordenamiento por comparación) |        |
|       | **7**  |                                                                  1.1.17                                                                  | Calcular el producto de dos enteros (A \* B) empleando **solo la operación suma**                                                | **Repetición Básica** (introducción al bucle)          |        |
|       | **8**  |                                                                  1.1.20                                                                  | Incrementar la variable V y recalcular su cuadrado y cubo **10 veces**                                                           | **Repetición Fija** (bucle `PARA` o similar)           |        |
|       | **9**  |                                                                  1.1.26                                                                  | Imprimir coordenadas (X, Y) de una función cuadrática, haciendo variar X en el intervalo [20, -20] con un decremento de 2        | **Repetición Controlada** (con pasos definidos)        |        |
|       | **10** |                                                                  1.1.21                                                                  | Repetir el ejercicio anterior $n$ veces ($n>1$) y emitir la suma de los cuadrados de V                                           | **Repetición y Acumulación**                           |        |

---

###### II. Ejercicios de Refuerzo

Estos ejercicios combinan estructuras condicionales y repetitivas de manera más compleja, involucran manipulación aritmética de dígitos, simulación de operaciones o el uso de bucles centinela y manejo de lógica de estado. Son cruciales para consolidar las habilidades.

| Orden  | Ejercicio | Consigna                                                                                                                                                                                       | Requisitos Clave                                                                         | Fuente |
| :----: | :-------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------- | :----- |
| **1**  |  1.1.12   | Ingresar número $100 < N < 1000$. Mostrar composición (U, D, C) y determinar si es múltiplo de 3 (sumando dígitos)                                                                             | **Manipulación Aritmética** (división y módulo)                                          |        |
| **2**  |  1.1.36   | Determinar si un número es múltiplo de 3 en función de que la suma de sus dígitos lo sea                                                                                                       | **Repetición y Manipulación de Dígitos** (para sumar los dígitos)                        |        |
| **3**  |  1.1.13   | Dada una suma de dinero $100 < \text{Suma} < 1000$, indicar cuántos billetes de 100, 10 y 1 peso se necesitan                                                                                  | **Manipulación Aritmética** (aplicación práctica de div/mod)                             |        |
| **4**  |  1.1.35   | Dada una suma de dinero, indicar cuántos billetes de 500, 100, 50, 20, 10, 5 y 1 peso se necesitan                                                                                             | **Manipulación Aritmética Extensa** (más denominaciones)                                 |        |
| **5**  |   1.1.8   | Conocer la edad de una persona ingresando la fecha de nacimiento y la fecha actual (DIA, MES, AÑO)                                                                                             | **Lógica Condicional Compleja** (manejo de fechas)                                       |        |
| **6**  |  1.1.18   | Calcular el cociente y el resto de dos enteros (F / G) empleando **solo suma y diferencia**                                                                                                    | **Simulación de División** (bucle de restas repetidas)                                   |        |
| **7**  |  1.1.25   | Calcular los **primeros 50 números de FIBONACCI**                                                                                                                                              | **Repetición Fija** y manejo de variables de estado (secuencias)                         |        |
| **8**  |  1.1.22   | Determinar si un número es primo                                                                                                                                                               | **Lógica Clásica de Bucle y Condicional** (prueba de divisibilidad)                      |        |
| **9**  |  1.1.15   | Calcular la altura de varios edificios, incluyendo la modificación para **50 edificios** y la de **cantidad indeterminada** con condición de fin                                               | **Variaciones de Repetición** (fija y bucle centinela)                                   |        |
| **10** |  1.1.16   | Obtener el porcentaje de alumnos de varias facultades (ISI, IQ, IEM), informando los totales por carrera y total general                                                                       | **Repetición y Cálculo** (acumulación de totales y porcentajes)                          |        |
| **11** |  1.1.23   | Calcular cada renglón de una factura (valor unitario \* cantidad) y el total, suponiendo que el número de renglones es variable, emitiendo un mensaje de error si el valor unitario es $\le 0$ | **Repetición, Acumulación y Validación de Entrada** (condicional)                        |        |
| **12** |  1.1.30   | Calcular el sueldo de **100 choferes** teniendo en cuenta categoría, antigüedad y asistencia                                                                                                   | **Repetición Fija** con **Lógica de Negocio Compleja**                                   |        |
| **13** |  1.1.14   | Procesar un conjunto de pares de valores (S, V) y determinar varios estadísticos (cuantos tienen S igual al primero, cuantos S > V, cuantos S es el doble de V, productoria de S si V es nulo) | **Bucle de Procesamiento**, Contadores, Acumuladores y múltiples condicionales internas  |        |
| **14** |  1.1.24   | Calcular e informar impuesto (10%), cuotas (2 o 3, condicional) y valor de las mismas para varios importes, finalizando con **9999**                                                           | **Bucle Centinela** (hasta ingresar 9999) y **Condicionales Anidadas** (para las cuotas) |        |

---

###### III. Ejercicios Opcionales

Estos ejercicios requieren estructuras de control más avanzadas, como **bucles anidados** o la aplicación de algoritmos altamente especializados. Se recomiendan para profundizar el conocimiento una vez que los ejercicios fundamentales y de refuerzo han sido dominados.

| Orden | Ejercicio | Consigna                                                                                                                                                                          | Requisitos Clave                                                                                               | Fuente |
| :---: | :-------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------- | :----- |
| **1** |  1.1.33   | Imprimir una sucesión donde N es par (sucesión triangular)                                                                                                                        | **Bucles Anidados** (impresión de patrones)                                                                    |        |
| **2** |  1.1.34   | Imprimir una sucesión con forma triangular invertida                                                                                                                              | **Bucles Anidados** (impresión de patrones)                                                                    |        |
| **3** |  1.1.29   | Imprimir los números primos menores a un valor dado _n_                                                                                                                           | **Bucles Anidados** (integración del algoritmo de primalidad dentro de un bucle de recorrido)                  |        |
| **4** |  1.1.28   | Encontrar todas las cifras de **tres dígitos** donde la suma de los cubos de sus dígitos sea igual al número                                                                      | **Bucle de Búsqueda Exhaustiva** (100 a 999) y Manipulación de Dígitos compleja                                |        |
| **5** |  1.1.27   | Repetir el ejercicio 1.1.26 para **varias funciones**, terminando al ingresar 9999 para el término cuadrático                                                                     | **Control Anidado** (bucle centinela exterior controlando un bucle fijo interior)                              |        |
| **6** |  1.1.32   | Determinar la fecha del domingo de Pascua para los años comprendidos entre **1990 y 2010**                                                                                        | **Bucle Fijo** (recorrido de años) y **Algoritmo Especializado de Cálculo** (secuencia de modulo y aritmética) |        |
| **7** |  1.1.31   | Calcular el peso de varias piezas de tela según calidad, material, porcentaje por apresto (2% seda, 7% algodón) y peso del núcleo (400g/300g), finalizando al ingresar FIN = 'SI' | **Bucle Centinela** (FIN='SI') y **Lógica de Negocio Condicional Extrema** (múltiples variables dependientes)  |        |

**Estructuras Condicionales y Repetitivas**

- Completado : 0/30

| Ejercicio | Observaciones |
| --------- | ------------- |
| 1.1.6     | ---           |

###### Subacciones

### 1.2. [Subacciones](https://aed-frre.github.io/practica/1.1/)
