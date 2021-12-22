![Tec de Monterrey](images/logotecmty.png)
# Actividad 3.4 Implementación de "Graph coloring"

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás el archivo "main.cpp". En este archivo deberás desarrollar la implementación del problema presentado en esta actividad.  En la parte superior del archivo coloca, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Authors:
//  Edward Elric - A00123456
//  Alphonse Elric - A00124598
// Date: 01/01/2021
// =========================================================
```
Implementa, <span style="text-decoration-line: underline;">en equipos de 2 personas (máximo)</span>, una solución para el problema de "Coloreo de grafos" visto en clase.

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

- **80%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (80%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (60%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (20%)** - pasa correctamente menos del 50% de los casos de prueba.

- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>
- **10%** - Se especifica (en comentarios) la complejidad computacional de cada uno de las funciones desarrolladas.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Cuando hayas pasado todas las pruebas, recuerda publicar el código en tu repositorio (*git push*).

## <span style="color: rgb(26, 99, 169);">**Importante**</span>
Recuerda colocar el nombre y las matrículas de ambos integrantes en en los comentarios iniciales. En caso de que se incumpla este punto, se penalizará con 20 puntos sobre la calificación obtenida.
