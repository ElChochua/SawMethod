To receive uploaded files, first install python-multipart.
$ pip install python-multipart
you should format this way the text file to get a succesfull response:
cantidad_Criterios: 3
cantidad_Alternativas: 5
datos: [[4,3,5,4],[2,4,3,3],[4,4,2,3],[4,3,4,3],[5,4,3,5]]
alternativas: ["A1", "A2", "A3", "A4", "A5"]
criterios: ["C1", "C2", "C3", "C4"]
costos: ["C3"]
pesos: [5,4,3,1]
The raw input for the first method should be formated this way:
{
    "cantidad_Criterios": 4,
    "cantidad_Alternativas": 5,
    "datos": [
    [4,3,5,4],
    [2,4,3,3],
    [4,4,2,3],
    [4,3,4,3],
    [5,4,3,5]],
    "alternativas": ["A1","A2","A3","A4","A5"],
    "criterios": ["C1","C2","C3","C4"],
    "costos": ["C3"],
    "pesos": [5,4,3,1]
}
Buenas noches 👍
