# Disposición: gato_verde

Disposición de botones para OSMTracker usada en el trabajo de campo del curso de SIG (mapeo de espacio público en Gato Verde, Pueblo Nuevo, Interlomas y San Gerardo).

| Botón | Elemento | Geometría | Etiquetas OSM |
|---|---|---|---|
| Parada de bus | Parada de bus de Gato Verde | Punto | `highway=bus_stop`, `public_transport=platform`, `bus=yes` |
| Reductor de velocidad | Reductor frente a plaza de Pueblo Nuevo | Punto (sobre la calle) | `traffic_calming=bump` |
| Clínica | Clínica Philips | Punto | `amenity=clinic`, `healthcare=clinic` |
| Panadería Musmanni | Musmanni | Punto | `shop=bakery`, `brand=Musmanni` |
| Basurero público | Basurero de San Gerardo | Punto | `amenity=waste_basket` |
| Teléfono público | Teléfono de San Gerardo | Punto | `amenity=telephone` |
| Puente - inicio / fin | Puente Pueblo Nuevo – Gato Verde | Línea | `bridge=yes`, `layer=1` + `highway=*` |
| Acera - inicio / fin | Acera Pueblo Nuevo – Gato Verde | Línea | `highway=footway`, `footway=sidewalk` |
| Tramo sin acera - inicio / fin | Interrupciones de la acera | Marca en la línea | (se usa para no dibujar la acera donde no existe) |
| Plaza - inicio / fin perímetro | Plaza de Gato Verde | Área | `leisure=pitch`, `sport=soccer` |
| Parque - inicio / fin perímetro | Parque Interlomas | Área | `leisure=park` |

Las líneas y áreas se capturan con la traza GPS: presione "inicio", camine el recorrido (o el perímetro completo) y presione "fin".
