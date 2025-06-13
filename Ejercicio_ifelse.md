## **Tienes edad suficiente?** 

1. Declare una variable edad utilizando la palabra clave var y establézcala en el número 10.

2. Añade una sentencia if que compruebe si el valor de la variable age es mayor o igual que el número 65. Dentro del bloque if, console.log la sentencia: "Obtienes tus ingresos de tu pensión". (Utilizaremos console.log en todo el código para mostrar la salida en la consola, lo que nos ayudará a mostrar los resultados de las condiciones y a seguir el comportamiento del programa durante su ejecución)

3. Añade un bloque "else if", donde comprobarás si el valor de la edad es menor que 65 y mayor o igual que 18. Dentro de este bloque "else if", escribe "console.log" y a continuación "Cada mes recibes un salario".

4. Añade otro "else if", y esta vez comprueba si el valor de la edad es menor de 18 años. Dentro del bloque "else if", escribe "console.log" y luego "Recibes un subsidio".

5. Añada una sentencia "else" para capturar cualquier otro valor. Dentro del bloque, escriba "console.log" y a continuación "El valor de la variable edad no es numérico".


```js
var age = 10 
if (age>=65)
{
	console.log("Obtienes tu ingresos de tu pension")
}

else if(age<65 && age>=18)
{
	console.log("Cada mes recibes un salario")
}
else if(age<18)
{
	console.log("Recibes un subsidio")
}
else
{
	console.log("El valor de la variable edad no es numerico")
}

```

## **los días de la semana**

1. En la siguiente línea, define una nueva variable, llámala day, y establece su valor a "Sunday".

2. Comienza a codificar una sentencia switch, pasando la variable day como la expresión a evaluar.

3. Dentro de switch, añade casos para cada día de la semana, empezando por "lunes" y terminando por "domingo". Asegúrate de usar valores de cadena para los días. Dentro de cada caso, por ahora, sólo añade un console.log('Do something'), y añade un break; en la línea de abajo.

4. Al final de la sentencia switch, añade el caso por defecto y añade un console.log('There is no such day').

5. Finalmente, actualice las llamadas console.log para cada caso, basándose en cualquier actividad que tenga en cada uno de los días.

```js
var day="Thursday"

switch(day)
{
	case 'Monday':
	console.log('I run a mountain');
	break;
	case 'Tuesday':
		console.log('I cook in the morning');
	break;
	case 'Wednesday':
		console.log('I week up on the bed');
	break;
	case 'Thursday':
	console.log('I watch tv');
	break;
	case 'Friday':
		console.log('I talk with my friends');
	break;
	case 'Saturday':
		console.log('I sing with spotify');
	break;
	case'Sunday':
		console.log('I sleep on the bed');
	break;
	default:
		console.log('There is no sush day');
	break;
}

```



##### Una sentencia if else(condicional), normalmente la usamos en casos de opciones binarias como tal vez usar un paraguas en caso de que llueva y no usarlo en caso de que no llueva, Tambien Podemos usar con la sentencia if else, varios operadores logicos.

##### Mientras que con la setencia switch, lo usamos con cadenas o numeros, y cuando tenemos multiples opciones de resultados como podria ser elegir una prenda para salir. 

##### Ambas son setencias de flujo,dependiendo las decisions o condiciones que Deben seguir.

```js
var puntaje = 800
if(puntaje=>1000)
{
	 console.log("Felicidades tu puntaje es alto")
}
else
{
	console.log("No has alcanzado un puntaje alto")
}

```

```js
var opc =0

switch(opc)
{
	case '1':
	console.log("Iniciar juego");
	break;
	case '2':
	console.log("Opciones");
	break;
	case '3':
	console.log("Salir");
	break;
	default:
	console.log("No existe la opcion");
	break;
}
```
