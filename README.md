# 1-TAREA-1INT46-PUCP

### Diccionario de Datos

| Columna        | Tipo de Dato        | Descripción                                                                 |
|----------------|---------------------|-----------------------------------------------------------------------------|
| **coordenadas** | `object`            | Coordenadas geográficas en formato de texto.                                |
| **latitud**     | `float64`           | Latitud de la ubicación donde ocurrió el evento.                            |
| **longitud**    | `float64`           | Longitud de la ubicación donde ocurrió el evento.                           |
| **fecha**       | `datetime64[ns]`    | Fecha exacta del evento en formato de fecha y hora.                         |
| **nombre_dia**  | `object`            | Nombre del día de la semana en que ocurrió el evento (ej. "Lunes").         |
| **nombre_mes**  | `object`            | Nombre del mes en que ocurrió el evento (ej. "Enero").                      |
| **tiempo**      | `float64`           | Tiempo del evento en un formato numérico (segundos, minutos, horas, etc.).  |
| **anio**        | `Int64`             | Año en que ocurrió el evento.                                               |
| **mes**         | `Int64`             | Mes en que ocurrió el evento (en formato numérico).                         |
| **dia**         | `Int64`             | Día del mes en que ocurrió el evento.                                       |
| **turno**       | `object`            | Turno del día en que ocurrió el evento (ej. "Mañana", "Tarde", "Noche").    |
| **departamento**| `object`            | Nombre del departamento en el que ocurrió el evento.                        |
| **provincia**   | `object`            | Nombre de la provincia en la que ocurrió el evento.                         |
| **distrito**    | `object`            | Nombre del distrito en el que ocurrió el evento.                            |
| **tipo_delito** | `object`            | Categoría principal del delito (ej. "Robo", "Asalto").                      |
| **subtipo**     | `object`            | Subcategoría del delito especificando el tipo de crimen (ej. "Robo a mano armada"). |
| **modalidad**   | `object`            | Modalidad en la que se cometió el delito (ej. "Con violencia", "Sin violencia"). |
| **macroregion** | `object`            | Macroregión a la que pertenece el lugar del evento.                         |
| **region_pol**  | `object`            | Región policial responsable de la jurisdicción donde ocurrió el evento.     |
| **ubigeo**      | `object`            | Código UBIGEO del lugar donde ocurrió el evento.                            |
| **case**        | `object`            | Identificador único del caso registrado.                                    |

Enlace a GitHub Pages: 
