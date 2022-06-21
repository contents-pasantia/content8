# ¿Qué es Json?

JSON (JavaScript Object Notation - Notación de Objetos de JavaScript) es un formato ligero de intercambio de datos. Leerlo y escribirlo es simple para humanos, mientras que para las máquinas es simple interpretarlo y generarlo. Está basado en un subconjunto del Lenguaje de Programación JavaScript, Standard ECMA-262 3rd Edition - Diciembre 1999. JSON es un formato de texto que es completamente independiente del lenguaje pero utiliza convenciones que son ampliamente conocidos por los programadores de la familia de lenguajes C, incluyendo C, C++, C#, Java, JavaScript, Perl, Python, y muchos otros. Estas propiedades hacen que JSON sea un lenguaje ideal para el intercambio de datos.

JSON está constituído por dos estructuras:

- Una colección de pares de nombre/valor. En varios lenguajes esto es conocido como un objeto, registro, estructura, diccionario, tabla hash, lista de claves o un arreglo asociativo.


- Una lista ordenada de valores. En la mayoría de los lenguajes, esto se implementa como arreglos, vectores, listas o sequencias.

Estas son estructuras universales; virtualmente todos los lenguajes de programación las soportan de una forma u otra. Es razonable que un formato de intercambio de datos que es independiente del lenguaje de programación se base en estas estructuras.

[enlace documentacion](https://www.json.org/json-es.html)

ejemplos:
Objeto JSON
```javascript
    {
        "llave1": "valor1",
        "llave2": "valor2",
        "llave3": "valor3",
        "llave4": 7,
        "llave5": null,
        "llave5":false,
        "favAmigos": ["Kolade", "Nithya", "Dammy", "Jack"],
        "favJugadores": {"uno": "Kante", "dos": "Hazard", "tres": "Didier"}
    }
```
Array de Json
```javascript
    [
        {
            "llave1": "valor1",
            "llave2": "valor2",
            "llave3": "valor3",
            "llave4": 7,
            "llave5": null,
            "llave5": false,
            "favAmigos": ["Kolade", "Nithya", "Dammy", "Jack"],
            "favJugadores": {"uno": "Kante", "dos": "Hazard", "tres": "Didier"}
        },
        {
            "llave1": "valor1",
            "llave2": "valor2",
            "llave3": "valor3",
            "llave4": 7,
            "llave5": null,
            "llave5": false,
            "favAmigos": ["Kolade", "Nithya", "Dammy", "Jack"],
            "favJugadores": {"uno": "Kante", "dos": "Hazard", "tres": "Didier"}
        }
    ]
```


## Reglas de sintaxis JSON que hay que conocer:
- Todos los datos del archivo deben estar rodeados de llaves {} si quieres representar un objeto y entre corchetes cuadrados si es un arreglo [].
- Las comillas simples no están permitidas.
- La llave en cada JSON debe ser única y debe estar entre comillas dobles.
- Los números no deben ir entre comillas dobles, de lo contrario se tratarán como cadenas de texto.
- El tipo de dato null no debe ir entre comillas dobles.
- Los valores booleanos solo pueden ser verdaderos o falsos.
- Cada par llave:valor debe terminar con una coma, excepto el último elemento
- Un solo objeto dentro de un arreglo debe terminar también con una coma.


