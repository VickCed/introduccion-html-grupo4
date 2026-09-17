Listas y Tablas en HTML



Las listas y las tablas son elementos fundamentales en HTML para organizar información de manera estructurada y legible.



1\. Listas en HTML



Las listas permiten agrupar elementos relacionados. Existen principalmente dos tipos:



A. Listas Desordenadas (`<ul>`)

Se utilizan cuando el orden de los elementos no es relevante. Utilizan viñetas (puntos).



```html

<ul>

&#x20;   <li>Manzanas</li>

&#x20;   <li>Plátanos</li>

&#x20;   <li>Naranjas</li>

</ul>

```



B. Listas Ordenadas (`<ol>`)

Se utilizan cuando el orden de los elementos importa (instrucciones paso a paso). Utilizan números automáticamente.



```html

<ol>

&#x20;   <li>Encender la computadora</li>

&#x20;   <li>Abrir el editor de código</li>

&#x20;   <li>Escribir el código HTML</li>

</ol>

```                                                                                                      2. Tablas en HTML (`<table>`)



Las tablas se utilizan para organizar datos en filas y columnas. Su estructura básica incluye:

\- `<table>`: Define la tabla.

\- `<tr>`: Fila de la tabla (Table Row).

\- `<th>`: Celda de encabezado (Table Header).

\- `<td>`: Celda de datos estándar (Table Data).



&#x20;Ejemplo de una Tabla:



```html

<table border="1">

&#x20;   <thead>

&#x20;       <tr>

&#x20;           <th>Nombre</th>

&#x20;           <th>Edad</th>

&#x20;           <th>Carrera</th>

&#x20;       </tr>

&#x20;   </thead>

&#x20;   <tbody>

&#x20;       <tr>

&#x20;           <td>Carlos</td>

&#x20;           <td>21</td>

&#x20;           <td>Desarrollo de Software</td>

&#x20;       </tr>

&#x20;       <tr>

&#x20;           <td>Ana</td>

&#x20;           <td>22</td>

&#x20;           <td>Redes Informáticas</td>

&#x20;       </tr>

&#x20;   </tbody>

</table>

