# bin-utils
scripts propios para mejorar la experiencia

## br
br (branch recent) se tiene que ejecutar en un directorio con un repositorio git. Su objetivo es ayudar a listar rápidamente las ramas y su última actividad, ordenadas descendientemente por actividad.

### Usos

br: uso normal, imprime las última 10 ramas, mostrando fecha total de última actividad, fecha relativa y el nombre de la rama
  -c: color -> cambia el color del nombre de la rama (<= 30 días verde, <= 3 meses amarillo, más tiempo es rojo)
  -n N: number -> imprimir un número N de ramas
  -s: short -> modo corto, sólo imprime la última rama activa, sin fechas
  -r: relative -> sólo imprime la fecha relativa y el nombre de la rama
  -t: total -> sólo imprime la  fecha total y el nombre de la rama
  t y r son excluyentes mutuamente
