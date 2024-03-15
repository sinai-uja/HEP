# HEP - High Energy Physics collection.
## Descripción
Este corpus está orientado al estudio de clasificadores de texto multi-etiquetado. Está compuesto por artículos científicos en el área de la Física de Altas Energías (HEP – High Energy Physics) obtenidos del servidor de documentos CDS del Laboratorio de Física Nuclear Europeo (CERN). El corpus está dividido en tres subconjuntos (denominadas particiones), donde cada partición se compone, a su vez, de dos ficheros: uno que contiene los registros de cada artículo (con información como los abstract, los autores y, por supuesto, las clases o palabras clave) en formato XML comprimido, y otro que contiene una versión en texto plano del artículo completo generado a partir del PDF disponible en las bases de datos del CERN (en formato tar + gzip) Las clases están delimitadas por la marca XML KEYWORD. Estas son las etiquetas del tesauro de DESY asignadas manualmente. Puede obtener más información sobre el tesauro de DESY.

- Partición **hepth**: 18,114 documentos de Física Teórica (metadatos – 5,3 Mb) (artículos – 226 Mb)
- Partición **hepex**: 2,599 documentos de Física Experimental (metadatos – 1,6 Mb) (artículos – 28 Mb)
- Partición **astroph**: 2,716 documentos de Astrofísica (metadatos – 1,1 Mb) (artículos – 29 Mb)

**Actualizado el 29.09.2021**: Gracias a Jaime Collado, de la Universidad de Jaén, por generar una versión actualizada de los ficheros XML, asegurando su compatibilidad con los parseadores y reglas actuales.

**Actualizado el 23.04.2007**: Gracias a Ioannis Katakis, de la Aristotle University of Thessaloniki, (Grecia) por corregir algunos problemas en el XML proporcionado. 

## Disponibilidad
El corpus HEP está disponible en: https://sinai.ujaen.es/investigacion/recursos/coleccion-hep

## Como citar
Este corpus ha sido preparado por Arturo Montejo Ráez, con metadatos facilitados por Jens Vigen y la ayuda del CDS Team. Para referencias usar:

Montejo-Ráez, A. and Steinberger, R. and Ureña-López, L. A. (2004). *Adaptive selection of base classifiers in one-against-all learning for large multi-labeled collections*. Advances in Natural Language Processing: 4th International Conference, EsTAL 2004, pp 1-12. Lectures notes in artifial intelligence, number 3230, Springer. 


```
@Article{montejo2004, 
  author = {Montejo-Ráez, A. and Steinberger, R. and Ureña-López, L. A.}, 
  title = {Adaptive selection of base classifiers in one-against-all learning for large multi-labeled collections}, 
  booktitle = {Advances in Natural Language Processing: 4th International Conference, EsTAL 2004}, 
  pages = {1--12}, 
  year = {2004}, 
  editor = {Vicedo J. L. et al.}, 
  location = {Alicante, Spain}, 
  number = {3230}, 
  series = {Lectures notes in artifial intelligence}, 
  publisher = {Springer} 
}
```
