# Etiquetas HTML

## <label></label>
###### R: Representa una etiqueta para un elemento en una interfaz de usuario, un ejemplo claro puede ser el texto que viene arriba de los input en un formulario.
'''html
<label for="Name">Click me</label>
<input type="text" id="Name" name="Name" />
'''

## <pre></pre>
###### R: Representa texto preformateado exactamente como viene en el archivo.

'''html
<pre>Las cosas que escribiré tendran identación al mostrarse por la etiqueta pre:

  - HTML.

  - Javascript.

  - CSS.

</pre>
'''

## <br/>
###### R: Un salto de línea en lugar donde los insertemos.

'''html
<p>Este es un texto en línea</p>
<p>Esto no es un <br/> texto seguido</p>
'''

## <table></table>
###### R: Es la etiqueta contenedora de una tabla.

'''html
<table>
  <!-- Cabecera -->
  <tr>
    <th>Título columna 1</th>   <!-- Celda de cabecera de la columna 1 -->
  </tr>
  <!-- Primera fila -->
  <tr>
    <td>Celda 1x1</td>    <!-- Primera celda de la primera fila -->
  </tr>
  <!-- Segunda fila -->
  <tr>
    <td>Celda 1x2</td>    <!-- Primera celda de la segunda fila -->
  </tr>
</table>
'''