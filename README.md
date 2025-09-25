# Sesión 2

## Audio y vídeo

### &lt;video&gt;
Este tag sirve para insertar videos. Para mostrar controles, se ha de añadir el atributo controls. El atributo autoplay permite que se reproduzca el vídeo automáticamente siempre que también cuente con el atributo muted. Con el atributo loop podemos hacer que el vídeo se reproduzca en bucle.

#### El tag &lt;source&gt;:
Modernamente, se pueden poner varios tags &lt;source&gt;. Para evitar que se intenten cargar videos que no se pueden reproducir, podemos añadir varias fuentes e indicar el tipo con los atributos de este tag.

### &lt;audio&gt;
Funciona igual que el tag &lt;video&gt;.


## Tablas
Las tablas se abren con el tag &lt;table&gt;. Cada fila de la tabla se añade con &lt;tr&gt;. Dentro de una fila, podemos distinguir entre 2 tipos principales de tags: el de encabezado y el de datos.

### &lt;thead&gt;
Dentro de este atributo va al menos un &lt;tr&gt; que solo contiene tags &lt;th&gt; (table header). Este tag se usa para el encabezado.

### &lt;tbody&gt;
Aquí va el cuerpo de la tabla. Cada uno de los &lt;tr&gt;s contiene tags &lt;td&gt; (table data). Este tag se usa para el cuerpo.