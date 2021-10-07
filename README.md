![Tec de Monterrey](images/logotecmty.png)
# Actividad 3.5 - Implementación de "Graph coloring"

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás el archivo "main.cpp". En este archivo deberás desarrollar la implementación del problema presentado en esta actividad.  En la parte superior del archivo coloca, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
```
Implementa, <span style="text-decoration-line: underline;">en parejas</span>, el algoritmo del problema de "Coloreo de grafos" visto en clase.

## <span style="color: rgb(26, 99, 169);">**Entrada**</span>
El programa recibe un un grafo no dirigido, en forma de matriz de adyacencias. La primera línea de entrada contiene un entero n, indicando el número de vértices del grafo. A continuación n líneas. La i-esima línea contiene n números.  El j-ésimo valor es 1 si el vértice i tiene conexión con el vértice j, 0 en caso contrario.

## <span style="color: rgb(26, 99, 169);">**Salida**</span>
Deberá desplegar los colores asignados a cada vértice.

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada**</span>
```
5
0 0 1 0 1
0 0 1 1 1
1 1 0 1 0
0 1 1 0 1
1 1 0 1 0
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida**</span>
```
Node 0 <-> Color 1
Node 1 <-> Color 1
Node 2 <-> Color 2
Node 3 <-> Color 3
Node 4 <-> Color 2
```

Para probar tu implementación, compila tu programa con el comando:
```
g++ -std=c++11 main.cpp -o app
```
Posteriormente, ejecuta tu programa. Para realizar las pruebas, puedes usar las siguientes líneas de código.
```
./app > mysolution.txt
diff mysolution.txt solution.txt
```
Si el segundo comando no tiene ninguna salida, los resultados que obtuviste son los esperados.

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **90%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (90%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (68%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (45%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (23%)** - pasa correctamente menos del 50% de los casos de prueba.

- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Cuando hayas pasado todas las pruebas, recuerda publicar el código en tu repositorio (*git push*).
