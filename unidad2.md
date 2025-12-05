<img src="https://inscripciones.unl.edu.ec/images/logo_unl.png" alt="Logo UNL" width="400" height="130" style="display: block; margin: 0 auto;"/>

# 📘 Unidad 2: Estructuras Algorítmicas de Control

## Contenidos de la Unidad 2 ⬇️

# **♟️ Estructuras Algorítmicas Condicionales:**

---

## 🔹 **Estructura condicional simple (Si… Entonces)**

La estructura condicional simple ejecuta una instrucción únicamente cuando una condición lógica es verdadera. Si la condición no se cumple, el programa continúa normalmente sin ejecutar acciones adicionales. Se usa para decisiones básicas basadas en una sola evaluación.



### ⭐ **Diagrama de Flujo**

La parte estructural del código la cual permite observar los procesos que evaluará según la condición.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/84b9178a-e083-4e91-ab5b-0894f9b112d2" />
</p>


### ⭐ **Codificación en C**

Este código usa la condicional simple `Si... Entonces` lo que hace es evaluar que el número ingresado por el usuario cumpla la condición puesta, si el número ingresado es menor que el rango de condición `numero < 10` muestra un mensaje diciendo que el número N es menor a 10, en cambio si es mayor finaliza el proceso.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/9ed56b6d-afca-4ad0-a7c4-60091446c915" />
</p>

---



## 🔹 **Estructura condicional doble (Si… Entonces, Sino)**

La estructura condicional doble evalúa una condición y permite elegir entre dos caminos: si la condición es verdadera, se ejecuta un bloque de instrucciones; si es falsa, se ejecuta un bloque alternativo. Es útil cuando existen dos posibles resultados para una decisión.



### ⭐ **Diagrama de Flujo**

La parte estructural del código la cual permite observar los procesos que evaluará según las condiciones.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/ea4515b5-e7e0-4746-98b0-46c503f36bcf" />
</p>


### ⭐ **Codificación en C**

Usamos el mismo código ahora usando la condicional `Si... Entonces, Sino` la cual permite tener dos salidas mediante la condición puesta.  
Si el usuario ingresa un número menor a 10, imprime el mensaje `El número N es menor a 10`, pero si ingresa un número mayor a la condición da otro mensaje diciendo `El número N es mayor a 10`, ya que esta condicional permite tener dos salidas: una verdadera (cuando cumple la condición) y otra falsa (cuando no cumple la condición).

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/0fea3ed7-9c2a-45c1-8624-9d1d5b1e970b" />
</p>



---

## 🔹 **Estructura condicional múltiple (En caso de… / Switch)**

La estructura condicional múltiple permite seleccionar una acción entre varias opciones según el valor de una variable. Evita el uso de múltiples condicionales anidados y organiza mejor las alternativas mediante switch-case. Incluye un caso por defecto para valores no contemplados.



### ⭐ **Diagrama de Flujo**

La parte estructural del código la cual permite observar los procesos que evaluará según las condiciones/case del switch.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/94e9b0ce-77a6-466a-a6ef-06428c8d28c3" />
</p>



### ⭐ **Codificación en C**

Ahora utilizamos la condición `En caso de...` o también `switch`, la cual recibe una expresión booleana (Verdadero o Falso).  
Esto significa que si el usuario ingresa un número **N** menor a 10 la condición y camino que utilizará es el verdadero `case 1`.  
Si ingresa un número **N** mayor a 10 utilizará el `case 0`, que sería falso.  
Esto permite crear varias opciones de salida para el usuario al ingresar los datos.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/7f090d49-1f34-4a20-8124-62b70c2df026" />
</p>





