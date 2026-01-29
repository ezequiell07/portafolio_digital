<img src="https://inscripciones.unl.edu.ec/images/logo_unl.png" alt="Logo UNL" width="400" height="130" style="display: block; margin: 0 auto;"/>

# 📘 Unidad 3: Programación Modular y Estructuras de Datos Estáticas

## Contenidos de la Unidad 3 ⬇️

# 📦 Programación Modular:

---

## 🔹 **Conceptos Básicos de Programación Modular**

<p style="text-align: justify;">
La programación modular es un paradigma que consiste en dividir un programa complejo en subprogramas más pequeños y manejables, llamados módulos (o funciones). Cada módulo se encarga de una tarea específica. Esto permite aplicar el principio de <i>"Divide y Vencerás"</i>, facilitando la lectura, la detección de errores y la reutilización del código en diferentes partes del programa.
</p>

### **Diagrama de Estructura**

<p style="text-align: justify;">
A continuación se observa cómo un programa principal (Main) delega tareas a sub-módulos específicos.
</p>

<p align="center">
<img width="400" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEivE6G5itWPU-CFaqM2009UtlCpDOkTBrKxRTaJSAYrydBK2UCQuifuip2S75jn3oklEbkFTFjW7W1VZsWA73Pvz-6Ab2nl8DyykpLc4duuVu4eYCJpaj25nU5eQQhomNyWB8FBINDLEbg/w1200-h630-p-k-no-nu/Sin+t%25C3%25ADtulo.png" alt="Esquema Modular" />
</p>

---

## 🔹 **Funciones y Procedimientos**

<p style="text-align: justify;">
En la práctica, la modularidad se implementa mediante:
<br><br>
1. <b>Funciones:</b> Bloques de código que reciben datos de entrada, realizan un cálculo y <b>retornan un valor</b> (ej. <code>CalcularSuma</code>).
<br>
2. <b>Procedimientos:</b> Bloques que ejecutan una acción (como mostrar un menú o limpiar pantalla) pero <b>no retornan valor</b> explícito (en C se usan como funciones <code>void</code>).
<br><br>
El intercambio de información entre el programa principal y los módulos se realiza a través de <b>parámetros</b>.
</p>

### **Codificación en C**

<p style="text-align: justify;">
En este ejemplo se observa una función <code>sumar</code> definida antes del <code>main</code>, la cual recibe dos enteros y devuelve el resultado.
</p>

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/c02190bd-1027-4ba1-abff-1194cefce972" " alt="Código Funciones" />
</p>

---

# 📊 Estructuras de Datos Estáticas:

---

## 🔹 **Arreglos Unidimensionales (Vectores)**

<p style="text-align: justify;">
Un arreglo unidimensional (vector) es una estructura de datos que almacena una colección de elementos del mismo tipo (enteros, flotantes, caracteres) bajo un mismo nombre. Estos elementos se guardan en posiciones contiguas de memoria y se accede a ellos mediante un <b>índice</b>.
<br>
<i>Nota: En C y Java, los índices siempre comienzan en 0.</i>
</p>

### **Representación Gráfica**

<p style="text-align: justify;">
Esquema de un vector de tamaño N, donde cada celda tiene su índice y contenido.
</p>

<p align="center">
<img width="300" src="https://github.com/user-attachments/assets/fb3de568-e774-4afd-b138-c6270c627a2a" alt="Vector" />
</p>

### **Codificación**

<p style="text-align: justify;">
El código muestra cómo declarar un vector <code>int numeros[5]</code> y utilizar un ciclo <code>for</code> para recorrerlo y llenar sus posiciones.
</p>

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/643c8f5b-3e85-46cf-ad6a-81760e906988" alt="Código Vector" />
</p>

---

## 🔹 **Arreglos Bidimensionales (Matrices)**

<p style="text-align: justify;">
Una matriz es un arreglo de dos dimensiones, organizado en <b>filas</b> y <b>columnas</b> (similar a una tabla de Excel). Para acceder a un dato específico, se necesitan dos índices: <code>matriz[fila][columna]</code>. Son ideales para representar tableros de juego, mapas o sistemas de ecuaciones.
</p>

### **Representación Gráfica**

<p style="text-align: justify;">
Visualización de una matriz donde se cruzan las filas (i) y las columnas (j).
</p>

<p align="center">
<img width="300" src="https://github.com/user-attachments/assets/e55a1ebc-234b-4da4-98ea-02291ad9f466" Matriz" />
</p>

### **Codificación**

<p style="text-align: justify;">
Para recorrer una matriz se utilizan dos ciclos <code>for</code> anidados: el externo controla las filas y el interno las columnas.
</p>

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/9ea88699-eef5-4804-899b-428f667e051f" alt="Código Matriz" />
</p>

---

## 🔹 **Arreglos Tridimensionales (Matrices)**

Un arreglo tridimensional es una estructura de datos que permite almacenar información en **tres dimensiones**, organizadas como **capas, filas y columnas**.

Cada elemento se accede mediante **tres índices**:

### **Representación Gráfica**
<p style="text-align: justify;"> Esquema de un arreglo 3D donde se observa la organización por niveles. Cada celda es un espacio de memoria contiguo identificado por tres coordenadas espaciales. </p>

<p align="center">
<img width="300" src="https://github.com/user-attachments/assets/2885da45-c966-4a24-a738-86f4c262f990" Matriz" />
</p>

### **Codificación**
<p style="text-align: justify;"> El siguiente código en <b>lenguaje C</b> muestra la declaración de un arreglo <code>int cubo[2][2][3]</code> y el uso de tres ciclos <code>for</code> anidados para recorrer la estructura completa y asignar valores secuenciales. </p>

<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/a8bb9a35-0bfa-4483-b3b1-c2dfac67ef9c" alt="Código Matriz" />
</p>



## 🔹 **Cadenas de Caracteres (Strings)**

<p style="text-align: justify;">
Una cadena es una secuencia de caracteres utilizada para procesar texto.
<ul>
    <li>En <b>C</b>: Se tratan como vectores de caracteres (<code>char nombre[50]</code>) que terminan con un carácter nulo <code>0</code>.</li>
    <li>En <b>Java</b>: Existen objetos <code>String</code> que simplifican su uso.</li>
</ul>
</p>


<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/02a9647e-d835-43b2-87cf-478df8612560" alt="Código Strings" />
</p>


<p align="center">
<img width="300" height="200" src="https://github.com/user-attachments/assets/b19f6b53-d6a6-4bf8-8b2f-bb4cdba94edc" alt="Código Strings" />
</p>

---

# 🚨 Principales dificultades en la aplicación de los contenidos

<p style="text-align: justify;">
Durante el desarrollo de la Unidad 3, la principal dificultad radicó en el concepto de <b>ámbito de las variables</b> (scope). Entender que una variable declarada dentro de una función no existe en otra (variables locales) fue confuso al principio, lo que llevaba a errores de compilación al intentar acceder a datos no visibles.
</p>

<p style="text-align: justify;">
Adicionalmente, el manejo de <b>arreglos bidimensionales (matrices)</b> presentó retos lógicos. La coordinación de dos ciclos anidados (uno para <code>i</code> y otro para <code>j</code>) suele generar confusiones, provocando que se intercambien filas por columnas erróneamente o que el programa intente acceder a un índice fuera de rango, causando cierres inesperados del programa.
</p>

<p align="center">
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/8d80dd32-813f-4f64-bd26-345cabeacfb3" />
</p>

<hr>

# 💡 Reflexión Crítica de Aprendizajes

<p style="text-align: justify;">
La Unidad 3 ha marcado un antes y un después en mi forma de programar. Pasar de escribir todo el código dentro del <code>main</code> a estructurarlo en <b>módulos y funciones</b> me ha permitido crear programas más ordenados, legibles y fáciles de corregir. He comprendido que la modularidad es esencial para el trabajo en equipo en proyectos reales.
</p>

<p style="text-align: justify;">
Asimismo, la incorporación de <b>estructuras de datos estáticas</b> (arreglos) me ha dado la capacidad de procesar conjuntos de datos en lugar de variables aisladas. Esto es la base para resolver problemas más realistas, como gestión de inventarios, listas de estudiantes o procesamiento de imágenes (matrices), optimizando significativamente el uso del código.
</p>

---

# 📑 Tareas Entregadas

## 🎓 ACD: Aprendizaje en Contacto con el Docente
#### ACD 1. Proyecto Académico Integrador
- [x] 📎 [Ver Evidencia]

#### ACD 2. Control de aprendizaje sobre python
- [x] 📎 [Ver Evidencia](assets/ACD2_UNIDAD3.png)
<hr>

## 💻 APE: Aprendizaje Práctico Experimental
#### APE 1. Construcción de funciones y procedimientos en un lenguaje de programación
- [x] 📎 [Ver Evidencia](assets/APE1_UNIDAD3.pdf)

#### APE 2. Implementación de funciones utilizando el paso de parámetros por valor y por referencia.
- [x] 📎 [Ver Evidencia](assets/APE2_UNIDAD3.png)

<hr>

## ✍️ AA: Aprendizaje Autónomo
#### AA 1. Curso Fundamentos de Python 1. Computación UNL
- [x] 📎 [Ver Evidencia](AA1_certificado_emerson.pdf)

<hr>
<div align="center">
  
## [⬅️ Regresar al menú principal](index.md)
</div>
