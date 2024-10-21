# Instrucciones para Recibir Archivos Subidos

Para recibir archivos subidos, primero instala `python-multipart`:

```bash
$ pip install python-multipart
Deberías formatear el archivo de texto de la siguiente manera para obtener una respuesta exitosa:
cantidad_Criterios: 3
cantidad_Alternativas: 5
datos: [[4, 3, 5, 4], [2, 4, 3, 3], [4, 4, 2, 3], [4, 3, 4, 3], [5, 4, 3, 5]]
alternativas: ["A1", "A2", "A3", "A4", "A5"]
criterios: ["C1", "C2", "C3", "C4"]
costos: ["C3"]
pesos: [5, 4, 3, 1]

La entrada en raw para el primer método debería estar formateada de la siguiente manera:
{ "cantidad_Criterios": 4,
"cantidad_Alternativas": 5,
"datos": [
[4, 3, 5, 4],
[2, 4, 3, 3],
[4, 4, 2, 3],
[4, 3, 4, 3],
[5, 4, 3, 5]],
 "alternativas": ["A1", "A2", "A3", "A4", "A5"],
 "criterios": ["C1", "C2", "C3", "C4"],
 "costos": ["C3"],
 "pesos": [5, 4, 3, 1] }
