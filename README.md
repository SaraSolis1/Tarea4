Integrantes: 
Erwin Fernando Blanco Melendres 9490-23-7748 100% 
Sara Abigail Solis Ixquiactap 9490-23-12295 100%

Arbol de Busqueda Binaria (ABB) y Arbol AVL
Este proyecto implementa un árbol de búsqueda binaria AVL Python, permitiendo la inserción, eliminación, Carga de archivos .txt y .csv, visualización en representación gráfica de los nodos.

Como funciona: Inserción de números en el árbol AVL.
Búsqueda de números dentro del árbol.
Eliminación de números del árbol AVL.
Carga de datos desde un archivo CSV para insertar múltiples valores.
Visualización del árbol con Graphviz.
Eliminación total del árbol, incluyendo cualquier imagen generada.
Menú interactivo para facilitar el uso del programa.

Ejemplo: insertamos los siguientes datos 1,2,3,4,5,6,7,8,9,10 y lo nivela correctamente demostrado en una imagen con Graphviz.
![image](https://github.com/user-attachments/assets/9c65d583-59cb-427c-b77b-822ea95701bd)

Instalar dependencias Instala la librería Graphviz con pip install graphviz Instala la librería csv Instala la librería os

Detalles de la ejecución del código completo:

En la primera parte NODO ABB representa un nodo en el árbol por lo cual definimos su direccion a la que ira ya sea derecha o izquierda y agregar la altura de balanceo que nos indicará si esta equilibrado.
Luego tiene los procesos antes mencionados, y posterior a ello, extienden la funcionalidad del ABB a un AVL en el que conseguimos la altura, el balanceo y la rotacion ya sea simple derecha o simple izquierda, luego inserta el nodo balanceado y lo muestra a traves de una grafica, misma practica al insertar los archivos CSV, con numeros que podran formar un arbol balanceado. Además, como extra tenemos una opcion de eliminar todo el arbol esto ayudara en caso de que querramos seguir trabajando en la misma consola para evitar que existan registros ingresados de los archivos o manual, junto con la imagen que puede generar de cada uno. 
Finalmente, tenemos el menú que nos muestra las opciones que tenemos para escoger y realizar el proceso deseado. Asimismo, este progra es util para las optimizaciones de busqueda. 

También agregamos la documentación necesaria para su una interpretación del código más sencilla. 
