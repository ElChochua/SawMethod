To receive uploaded files, first install python-multipart.\n
$ pip install python-multipart\n
you should format this way the text file to get a succesfull response:\n
cantidad_Criterios: 3\n
cantidad_Alternativas: 5\n
datos: [[4,3,5,4],[2,4,3,3],[4,4,2,3],[4,3,4,3],[5,4,3,5]]\n
alternativas: ["A1", "A2", "A3", "A4", "A5"]\n
criterios: ["C1", "C2", "C3", "C4"]\n
costos: ["C3"]\n
pesos: [5,4,3,1]\n
The raw input for the first method should be formated this way:\n
{\n
    "cantidad_Criterios": 4,\n
    "cantidad_Alternativas": 5,\n
    "datos": [\n
    [4,3,5,4],\n
    [2,4,3,3],\n
    [4,4,2,3],\n
    [4,3,4,3],\n
    [5,4,3,5]],\n
    "alternativas": ["A1","A2","A3","A4","A5"],\n
    "criterios": ["C1","C2","C3","C4"],\n
    "costos": ["C3"],\n
    "pesos": [5,4,3,1]\n
}\n
Buenas noches 👍\n
