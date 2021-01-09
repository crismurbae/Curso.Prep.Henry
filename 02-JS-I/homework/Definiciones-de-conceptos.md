# Homework: Introducción a Javascript

Explicaciones de los siguientes conceptos:


	* Variables:
		Sirven para contener información ó un valor que podrá ser utilizado todas las veces que se necesite. 
		Para crearla se emplea la palabra clave var, y puede modificarse su contenido todas las veces que sean necesarias. En Javascript no es necesario utilizar la palabra clave var, para su creación, se puede directamente asignar un valor, mediante el signo igual.
		Si se utiliza la palabra clave const para crearla su valor no podrá ser modificado.
		Su sintaxis es la siguiente:
			var nombredelavariable = contenido;
			const nombredelaconstante = contenido;
		No se pueden utilizar palabras reservadas por el lenguaje (o palabras claves o keywords) para asignarle nombre a la variable o constante.
		Exite otra palabra clave para crear una variable que es let, y tiene que ver con el scoup o area de alcance de la variable.
		El contenido de las variables pueden clasificarse en tres tipos de datos: strings, números o booleanos.

	* Strings: 
		Es un tipo de dato que se escribe entre comillas conteniendo palabras o más bien cadenas de caracteres alfanuméricos. Si su contenido fueran números, estos no son tratados como números, sino como si fueran palabras.
		No se pueden realizar operaciones matemáticas con su contenido, pero se utiliza el operador suma para concatenar su contenido, es decir, unir. 
		Hay que aclarar que Javascript es muy flexible y puede suceder que realice la conversión de tipos de datos para resolver algunas operaciones.

	* Funciones (argumentos, `return`):
		Es una forma de reutilizar código para que no tenga que escribirse repetidas veces.
		Su sintaxis es la siguiente:
			function nombredelafunción () {
				//se escribe el código
			}
		Para invocar la función, es decir, llamarla, hay que escribir su nombre y luego ,los paréntesis:
			nombredelafunción ()
		Y de esta manera se ejecuta el código que contiene.
		A la función se le pueden pasar argumentos que pueden ser utilizados dentro del código.
		Estos argumentos son como variables que son declaradas dentro de la función cuyo scoup (alcance o área de influencia) está limitado al área contenida entre las llaves de la función.
		La función puede devolver o retornar valores al ser ejecutada, cuando no devuelve ninguno, su resultado es undefined. La sintaxis para hacer que una función devuelva valores es la siguiente:
			function nombredelafunción () {
				//se escribe el código
				return valoraretornar;
			}
		Cuando la función encuentra la orden return no sigue leyendo el código, finalizando su ejecución. Todo lo que se escriba luego de return no será leído y por lo tanto no será ejecutado.

	* Declaraciones `if`:
		La declaración if funciona como un condicional, que realiza un pregunta: si se cumple determinada condición se ejecuta un código, y si no se cumple se puede ejecutar otro.
		Su sintaxis es la siguiente:
			if (condición) {
				//código cuando la condición es verdadera
			} else {//sino se ejecuta esto

			} 

	* Valores booleanos (`true`, `false`):
		Los valores booleanos representan los valores verdadero para true y falso para false.
		Cuando se evalúa una condición (comparaciones), el resultado de esa condición puede ser verdadera o falsa.
		Por ejemplo:
		5>4 es verdadero, true
		5<4 es falso, false.
		5==4 es falso, false.
		4==4 es verdadero, true.
		