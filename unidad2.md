<img src="https://inscripciones.unl.edu.ec/images/logo_unl.png" alt="Logo UNL" width="400" height="130" style="display: block; margin: 0 auto;"/>

# 📘 Unidad 2: Estructuras Algorítmicas de Control

## Contenidos de la Unidad 2 ⬇️

# **♟️ Estructuras Algorítmicas Condicionales:**

---

## 🔹 **Estructura condicional simple (Si… Entonces)**

La estructura condicional simple `Si... Entonces` ejecuta una instrucción únicamente cuando una condición lógica es verdadera. Si la condición no se cumple, el programa continúa normalmente sin ejecutar acciones adicionales. Se usa para decisiones básicas basadas en una sola evaluación.



### **Diagrama de Flujo**

La parte estructural del código la cual permite observar los procesos que evaluará según la condición.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/84b9178a-e083-4e91-ab5b-0894f9b112d2" />
</p>


### **Codificación en C**

Este código usa la condicional simple `Si... Entonces` lo que hace es evaluar que el número ingresado por el usuario cumpla la condición puesta, si el número ingresado es menor que el rango de condición `numero < 10` muestra un mensaje diciendo que el número N es menor a 10, en cambio si es mayor finaliza el proceso.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/9ed56b6d-afca-4ad0-a7c4-60091446c915" />
</p>

---



## 🔹 **Estructura condicional doble (Si… Entonces, Sino)**

La estructura condicional doble `Si… Entonces, Sino` evalúa una condición y permite elegir entre dos caminos: si la condición es verdadera, se ejecuta un bloque de instrucciones; si es falsa, se ejecuta un bloque alternativo. Es útil cuando existen dos posibles resultados para una decisión.



### **Diagrama de Flujo**

La parte estructural del código la cual permite observar los procesos que evaluará según las condiciones.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/ea4515b5-e7e0-4746-98b0-46c503f36bcf" />
</p>


### **Codificación en C**

Usamos el mismo código ahora usando la condicional `Si... Entonces, Sino` la cual permite tener dos salidas mediante la condición puesta.  
Si el usuario ingresa un número menor a 10, imprime el mensaje `El número N es menor a 10`, pero si ingresa un número mayor a la condición da otro mensaje diciendo `El número N es mayor a 10`, ya que esta condicional permite tener dos salidas: una verdadera (cuando cumple la condición) y otra falsa (cuando no cumple la condición).

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/0fea3ed7-9c2a-45c1-8624-9d1d5b1e970b" />
</p>



---

## 🔹 **Estructura condicional múltiple (En caso de… / Switch)**

La estructura condicional múltiple `Switch` permite seleccionar una acción entre varias opciones según el valor de una variable. Evita el uso de múltiples condicionales anidados y organiza mejor las alternativas mediante switch-case. Incluye un caso por defecto para valores no contemplados.



### **Diagrama de Flujo**

La parte estructural del código la cual permite observar los procesos que evaluará según las condiciones/case del switch.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/94e9b0ce-77a6-466a-a6ef-06428c8d28c3" />
</p>



### **Codificación en C**

Ahora utilizamos la condición `En caso de...` o también `switch`, la cual recibe una expresión booleana (Verdadero o Falso).  
Esto significa que si el usuario ingresa un número **N** menor a 10 la condición y camino que utilizará es el verdadero `case 1`.  
Si ingresa un número **N** mayor a 10 utilizará el `case 0`, que sería falso.  
Esto permite crear varias opciones de salida para el usuario al ingresar los datos.

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/7f090d49-1f34-4a20-8124-62b70c2df026" />
</p>


# **♟️Estructuras Algorítmicas Repetitivas:**

--- 

## 🔹 **Bucle While (Mientras…)**

El bucle `while` permite repetir un bloque de instrucciones mientras se cumpla una condición lógica. La condición se evalúa antes de cada repetición, por lo que el ciclo puede ejecutarse cero o muchas veces. Se utiliza cuando no se conoce cuántas iteraciones serán necesarias y la repetición depende directamente de la condición.

## **Diagrama de Flujo**
La parte estructural del código donde se puede visualizar cómo el bucle `while` evalúa la condición y repite el proceso mientras el número ingresado siga siendo menor que 10.

<p align="center">
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/74ad0e5c-0f34-4d51-a051-4343e6f81ac0" />
</p>



## **Codificación en C**
En este caso utilizamos el bucle `while`, el cual permite repetir las instrucciones mientras la condición establecida siga siendo verdadera. Aquí se evalúa si el número ingresado es menor que 10 y, mientras eso se cumpla, el programa muestra el mensaje correspondiente y solicita otro número. El ciclo continúa hasta que el usuario ingresa un valor que ya no cumple la condición, finalizando así el proceso.

<p align="center">
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/65288cb6-9c32-438e-82c5-f4321e65f100" />
</p>

---

## 🔹 **Bucle Do… While (Hacer… Mientras)**
El bucle `do-while` ejecuta primero el bloque de instrucciones y evalúa la condición al final del ciclo. Esto garantiza que el cuerpo del bucle se ejecute al menos una vez, incluso si la condición no se cumple desde el inicio. Es útil cuando se requiere que una acción ocurra mínimo una vez antes de validar la condición.

## **Diagrama de Flujo**
La parte estructural del código donde se observa cómo el ciclo `do…while` ejecuta sus instrucciones al menos una vez y luego valida la condición, repitiendo el proceso mientras el número ingresado sea menor que 10.

<p align="center">
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/7d6bc2e9-70c8-4358-a343-7a622cd45c97" />
</p>


## **Codificación en C**
En este caso utilizamos el bucle `do...while`, el cual se ejecuta al menos una vez antes de evaluar la condición. El programa solicita un número inicial y luego continúa pidiendo nuevos valores mientras el número ingresado siga siendo menor que 10. Una vez que la condición deja de cumplirse, se muestra un mensaje indicando que el número ingresado ya no cumple la condición establecida.

<p align="center">
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/7dbf22f8-8abd-40e5-a6fb-a0f34907016b" />
</p>

---

##  🔹**Bucle For (Para…)**
El bucle `for` permite repetir un conjunto de instrucciones un número determinado de veces. Está compuesto por tres partes: inicialización, condición y actualización del contador. Su estructura facilita recorrer rangos numéricos, realizar pasos controlados o ejecutar repeticiones predefinidas.

## **Diagrama de Flujo**
La parte estructural del código donde se observa cómo el ciclo `for` evalúa la condición `numero < 10` y repite el proceso mientras esta se cumpla. Dentro del bucle se muestra el mensaje correspondiente y se solicita un nuevo número, permitiendo visualizar de forma clara el comportamiento repetitivo antes de finalizar el algoritmo.

<p align="center">
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/b296001b-10ce-4247-89ba-c40efd84a648" />
</p>

## **Codificación en C**
En este caso utilizamos el ciclo `for`, el cual repite sus instrucciones mientras la condición establecida siga siendo verdadera. Aquí el bucle se mantiene activo mientras el número ingresado sea menor que 10, mostrando el mensaje correspondiente y pidiendo un nuevo valor. Una vez que el usuario ingresa un número que ya no cumple la condición, se imprime un mensaje final indicando que el ciclo ha terminado.

<p align="center">
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/41cc4ba8-431b-4725-a820-f395e487d8c3" />
</p>

---

# ♨️ Ejercicio Combinado 

## Descripción del problema
El programa solicita al usuario ingresar la cantidad de estudiantes y luego, mediante un ciclo repetitivo for, permite ingresar la nota de cada uno de ellos.
Por cada nota ingresada:

* Si la nota es mayor a 7, el estudiante se considera Aprobado.

* Si la nota es menor o igual a 7, se considera Reprobado.

Cada nota es almacenada en un arreglo para poder mostrarlas nuevamente al final junto con su respectivo estado (Aprobado/Reprobado).

Este ejercicio combina:

* Estructura repetitiva `for`

* Estructura condicional `if…else`

## Diagrama de flujo simplificado
El diagrama de flujo muestra el proceso completo para gestionar las notas de varios estudiantes utilizando un ciclo repetitivo y una estructura condicional.
Primero, el programa solicita la cantidad de estudiantes y crea un arreglo para almacenar sus notas. Luego, por medio de un ciclo, se pide la nota de cada estudiante y se evalúa si es mayor a 7 para determinar si está aprobado o reprobado.
Después de registrar todas las notas, un segundo ciclo recorre nuevamente el arreglo para mostrar las notas finales junto con su respectivo estado. De esta forma, el diagrama refleja la combinación de decisiones y repeticiones dentro del algoritmo.

<p align="center">
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/85a2656d-2a7c-490c-93e0-668baed82706" />
</p>

## Código en Java
Este programa combina una estructura repetitiva `for` con una condición `if… else` para evaluar las notas de varios estudiantes.
Primero se pide al usuario la cantidad total de estudiantes y se crea un arreglo para almacenar todas las notas.
Dentro del primer ciclo for, se solicita la nota de cada estudiante y se evalúa si es mayor a 7 para mostrar si está aprobado o reprobado.
Una vez ingresadas todas las notas, un segundo ciclo for recorre nuevamente el arreglo y muestra cada nota junto con su estado final, utilizando una expresión condicional para simplificar la impresión de "Aprobado" o "Reprobado".
Finalmente, el programa cierra el escáner y termina el proceso.

<p align="center">
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/3d8f17fd-8d28-4b62-833f-954dccfac6d9" />
</p>

## Verificación 

Para comprobar el correcto funcionamiento del programa, se utilizaron varios datos de prueba y se registraron las salidas esperadas según la lógica implementada.
<p align="center">
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/98cbb804-3601-463a-a0c8-d525d1cd7a20" />
</p>

Al ejecutar el programa en la terminal, las salidas obtenidas coinciden exactamente con los resultados previstos en los casos de prueba, confirmando que el comportamiento del algoritmo es el adecuado.
<p align="center">
<img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/d5fa8c4f-ef8e-46a1-97a9-652242c9236b" />
</p>





