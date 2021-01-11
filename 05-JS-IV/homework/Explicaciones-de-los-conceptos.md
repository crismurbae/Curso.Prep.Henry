##Explicaciones de los siguientes conceptos:

	1. Objetos
		* Conjunto o colección de propiedades. EN el objeto se pueden guardar todo tipo de datos, string, number, booleano, array, function, null, undefined.
		* Su sintaxis es la siguiente:
			var nombreDelObjeto = {
				nombreDePropiedad1: 'valor',
				nombreDePropiedad2: 2,
				nombreDePropiedad3: true,
				nombreDePropiedad4: [2,3,4],
				nombreDePropeidad5: function() {console.log ("Hola");}

			}

	2. Propiedades
		* Relación entre un nombre clave y un valor. Ese nombre es en formato string. A diferencia que el array, que es en formato número.
		* Para llamar a una propiedad, se debe escribir de la siguiente forma:
			nombreDelObjeto.nombreDePropiedad1
			nombreDelObjeto ['nombreDePropiedad2']

	3. Métodos
		* Los métodos son propiedades de un objeto que contienen funciones.
			var nombreDelObjeto = {
				nombreDePropeidad5: function() {console.log ("Hola");}
			}

	4. Bucle `for…in`
		* Para poder iterar o mostrar todos los pares de nombre de la propiedad y su valor correspondiente. Debe ser un tipo especial de bucle, porque no tiene índice numérico como el array.
		* Su sintaxis es la siguiente:
			for (let clave in nombreDelObjeto) {
				console.log (clave);
				console.log (nombreDelObjeto[clave]);
			}

			clave es una variable que irá iterando o mostrando todos los nombres de la propiedad del objeto.

	5. Notación de puntos vs notación de corchetes
		* Para llamar a una propiedad, se puede escribir de dos maneras diferentes:
			*Como Dot notation:
				Es más fácil, pero es literal, no permite el usao de variables para el nombre de la propiedad:
					nombreDelObjeto.nombreDePropiedad1
			*Como Bracket notation:
				Se puede llamar de manera literal como en el anterior, entonces se usan comillas:
					nombreDelObjeto ['nombreDePropiedad2']
				O se puede hacer uso de variables para reemplazar el nombre de la propiedad, entonces no se usan comillas porque se trata de una variable:
					nombreDelObjeto [nombreDePropiedad2]