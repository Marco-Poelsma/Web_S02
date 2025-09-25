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


## Elementos en bloque y elementos en línea
En HTML, podemos distinguir entre dos tipos de elementos. Los elementos de bloque, que ponen un salto de línea al final, y el elemento en línea, que no hace el salto de línea.

### &lt;div&gt; y &lt;span&gt;
El tag &lt;div&gt; es el elemento en bloque por excelencia y &lt;span&gt; es el elemento en línea por excelencia.

## Los atributos id y class
Estos dos atributos son universales y pueden ser usados por cualquier elemento. El atributo id es único y no se puede repetir dentro de una misma página, mientras que el atributo class se puede aplicar a varios elementos.
***IMPORTANTE: No hace falta asignarle un id o un class a todos los elementos de una página. Estos atributos son útiles para diferenciar elementos únicos que queramos resaltar, con lo que añadirlos a todos los elementos de la página hará que se agrupen todos los elementos de la misma manera.***

## Tags semánticos
Los tags &lt;header&gt;, &lt;nav&gt;, &lt;main&gt;, &lt;section&gt;, &lt;aside&gt; y &lt;footer&gt; nos permiten dar significado semántico para nuestra página, de manera que un buscador pueda encontrar información clave sobre la página. Además, nos permiten organizar la información dentro de la página.