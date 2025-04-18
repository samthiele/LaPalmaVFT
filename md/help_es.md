
# Ayuda

[Traducido con DeepL]

Las excursiones virtuales de RockHopper deberían ser bastante intuitivas (¡esperamos!), pero esta página ayuda a aclarar cómo funciona todo.

## Controles 3D

Utiliza los siguientes controles para navegar por el visor 3D.
| Control |     Acción     |
|----------|----------|
| `Botón izquierdo del ratón` | Girar la vista   |
| `Botón derecho del ratón` | Desplazar la vista   |
| `Desplazamiento` | Acercar/alejar   |
| `Doble clic` | Establecer el centro de rotación o eliminar la anotación seleccionada  |
| `Mayús + clic izquierdo` | Desplazar la vista |
| `Ctrl + clic izquierdo` | Añadir un punto a la anotación actual |

## Controles de anotación
Se pueden añadir puntos de anotación utilizando `Ctrl+clic izquierdo` (deberían aparecer inicialmente como pequeñas esferas amarillas). Una vez finalizada una anotación, pulse `Intro` para aceptarla o `Esc` para borrarla.
El tipo de anotación que se añadirá se decidirá en función del número de puntos cuando se pulse `Intro`:
1 punto: Añade un objeto `Etiqueta` que contiene texto (o HTML arbitrario).
2 puntos: Añade un objeto «Vector» y añade su «tendencia», «caída» y «longitud» a la pestaña Notas.
3 puntos: Añade un objeto «Plano» y añade su «strike», «dip» y «dirección del dip» a la pestaña Notas.
4+ puntos: Añade un objeto «Polilínea». Esto puede ser útil, por ejemplo, para resaltar características lineales (o rodear objetos de interés).

---

**Nota importante**: *Las anotaciones se perderán si se actualiza la página (a menos que esté ejecutando RockHopper en un servidor de desarrollo local), lo que significa que cualquier cambio deberá descargarse utilizando el botón «⬇ Notas» situado en la parte inferior izquierda.*

---

Las anotaciones (y las etiquetas HTML) pueden ocultarse o mostrarse utilizando los botones correspondientes situados en la parte inferior izquierda del visor 3D. El color de las anotaciones (actualmente dibujadas) también se puede cambiar haciendo clic en el widget de selección de color.
## Controles de visualización
Una de las principales ventajas de RockHopper es que se pueden transmitir y visualizar múltiples atributos de conjuntos de datos de nubes de puntos de diferentes maneras. Estos «estilos» de visualización se definen cuando la nube de puntos se convierte a un formato transmisible y se les asignan nombres (esperemos que) comprensibles. 
**Utilice los botones de la parte superior izquierda de la vista 3D para cambiar el estilo de visualización**. La fila superior cambia la asignación de colores utilizada para definir el color de los puntos. La segunda fila se puede utilizar para resaltar u ocultar un subconjunto de los puntos (basándose en una clasificación subyacente). Esto puede ser útil para visualizar diferentes fechas en un conjunto de datos de series temporales o para resaltar partes específicas de una nube de puntos.
