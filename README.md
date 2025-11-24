# INFORME DE INVESTIGACION


![LOGO CARRERA](assets/ups-icc.png)


### *Asignatura:* Estructura de Datos

### *Tema:* Proyecto de Complejidad y Eficiencia de Algoritmos


# Integrantes:
- Renato Martín Amaya Siguenza - https://github.com/MartinAmaya12
- Geovanny Alejandro Cabrera Tapia - https://github.com/alejoca112


































## **2. Ejemplos de Complejidad en Java**

En esta sección se presentan las clases creadas dentro del proyecto y el análisis correspondiente a cada una.

---

## **2.1 Complejidad O(1) – Constante**

### **Archivo:** `ComplejidadConstante.java`

### **Código del ejemplo**

![alt text](<assets/CConstante(java).png>)

### Salida del ejemplo

![alt text](assets/ComplejidadConstante.png)

### **Explicación resumida**

La complejidad es $O(1)$ (Constante) porque el número de operaciones es fijo y no depende del tamaño de ninguna entrada. El código siempre ejecuta las mismas líneas sin importar factores externos.

## **2.2 Complejidad O(n) – Lineal**

### **Archivo:** `ComplejidadLineal.java`

### **Código del ejemplo**

![alt text](<assets/ComplejidadLineal(java).png>)

### Salida del ejemplo

![alt text](assets/ComplejidadLineal.png)

### **Explicación resumida**

La complejidad es $O(n)$ (Lineal) porque existe un bucle que itera exactamente $n$ veces. El tiempo de ejecución crece proporcionalmente al tamaño de $n$; si $n$ se duplica, el tiempo también2.

## **2.3 Complejidad O(n^2) – Cuadrática**

### **Archivo:** `ComplejidadCuadratica.java`

### **Código del ejemplo**

![alt text](<assets/ComplejidadCuadratica(java).png>)

### Salida del ejemplo

![alt text](assets/ComplejidadCuadratica.png)

### **Explicación resumida**

La complejidad es $O(n^2)$ (Cuadrática) debido a la presencia de dos bucles anidados. Por cada iteración del bucle externo, el interno se ejecuta completamente, resultando en $n \times n$ operaciones totales

## **2.4 Complejidad O(log n) – Logaritmica**

### **Archivo:** `ComplejidadLogaritmica.java`

### **Código del ejemplo**

![alt text](<assets/ComplejidadLogaritmica(java).png>)

### Salida del ejemplo

![alt text](assets/ComplejidadLogaritmica.png)

### **Explicación resumida**

La complejidad es $O(\log n)$ (Logarítmica). En lugar de recorrer todos los elementos, el algoritmo salta pasos multiplicando el iterador (o dividiendo el problema), lo que reduce drásticamente el número de operaciones necesarias.

## **2.5 Complejidad O(n log n) – Logaritmica**

### **Archivo:** `ComplejidadNLogN.java`

### **Código del ejemplo**

![alt text](<assets/ComplejidadNLogN(java).png>)

### Salida del ejemplo

![alt text](assets/ComplejidadNLogN.png)

### **Explicación resumida**

La complejidad es $O(n \log n)$. Se produce al combinar un bucle logarítmico (externo) con un bucle lineal (interno). Es común en algoritmos de ordenamiento eficientes como Merge Sort o Quick Sort.

# **Conclusiones**

**Geovanny Cabrera**:
Para concluir en base a la practica me he dado cuenta que la complejidad con mas costo computacional ha sido la Cuadratica ($O(n^2)$) ha sido la mas larga(ineficiente) de todas 
, considero este resultado debido a que por cada iteracion de dato que se realiza, sube exponencialmente a las iteraciones debido al bucle for interno(anidado).
Comparando con la complejidad lineal, este algoritmo se vuelve inviable para conjuntos de datos muy grandes, tambien existe una palabra que me llamo mucho la atencion la cual fue
sobre la eficiencia de software usando escabilidad,la capacidad de manejar un volumen creciente de datos, me di cuenta que un software no solo necesita buena funcionalidad
sino tambien una buena forma de como escalar todo ese trabajo.Además pude comprender sobre la diferencia entre lo que es coste temporal y coste espacial.
Pero tengo un favorito, lo que mas me gusto del trabajo fue que pude entender a fondo lo que es O(n log n) debido a que me gusto la forma en la que con cambiar el bucle for
ayuda a que quizas un millon de datos , se procese de manera corta con tan solo 20 iteraciones usando matematica.  Recuerdo tambien que existia un metodo de "Divide y Venceras",
el cual era realmente esto , grandes partes dividirlas en pequeñas partes por las que se completan de manera demasiado rapida.
Fue muy importante porque me permitio conocer sobre como un algoritmo es correcto, ademas de comprendes las diferentes notaciones para cada complejidad.
**Martin Amaya**:
