# SoloLearn

### Fundamentos 
* llenar los espacios en blanco para generar js es genial para la consola sololearn
__console.log ___ ("J's is cool")

* Declare una variable llamada x, asígnele el valor 42 y envíela a la consola.
x = 42;
console.log(x);






* ¿Cuál es el resultado de este código?
//x=8;
x=2;
//x=3;
console.log(x);
* [] 3
* [] 0
* [x] 2
* [] 8


* Reorganizar para formar un código JavaScript válido que declare una variable y la envíe a la consola.

<script>\
name = "James";
  console.log(name);
</script>

### Conceptos basicos 

* Cuáles de estos nombres son aceptables para las variables de JavaScript?

* [x] firtsNumber
* [x] _module


* Complete los tipos de datos de los datos que se muestran a continuación en el campo de comentarios:

12 // number 

"some text" // **string**


true // **boolean**




* ¿Cuál es el resultado de la expresión var1 && var2, si var1 = true y var2 = false?

el valor de la expresion va a ser igual a **false**


### condicionales y bucles 

 * ¿Cuál es el resultado de este código?
 
 var x=0;
 while(x<6) {
   x++;
 }
 document.write(x);

 El resultado es "6"

* Complete las palabras clave correctas para probar las condiciones:
____switch___(day_of_week) {

  case 1:

  case 2:

  case 3:

  case 4:

  case 5:

    document.write("Working Days");
    _____break;____
    
;

  case 6:

    document.write("Saturday");
_________break;_____
    
;

  default:

    document.write("Today is Sunday");

    break;

}

* Complete las palabras clave correctas para componer un bucle:

__do__ {
  document.write(i);

  i++;

}

_____while____ (i < 10);


#### Funciones


* ¿El siguiente código dará como resultado qué valor?
function test(number)
{
   while(number < 5) {
      number++;
   }
   return number;
}
alert(test(2));

El valor va a ser igual a 5.

* W¿Cuál es el resultado de la siguiente expresión?
function multNmbrs(a, b) {
    var c = a*b;
}
multNmbrs(2, 6);

El resultado es nada.


* Complete los nombres correspondientes para los cuadros de diálogo integrados:

 ____prompt___es para obtener información del usuario;

___alert_____ es para mostrar un mensaje en un cuadro;

* Complete los espacios en blanco para calcular el máximo de los parámetros:

function max(a, b) {

  
____if__(a >= b)

    return ___a__;

  

      ____else_____
    return b;

}

* ¿Cuál es la sintaxis correcta para hacer referencia a un script externo llamado "script.js"?

* [x] <script src="script.js">
* [] <script name="script.js">
* [] <script href="script.js">

* ¿Qué alerta se mostrará en la pantalla?

function test(a, b) {
  if(a > b) {
    return a*b; 
} else {
     return b / a; 
    }
}
alert(test(5, 15));

___El resultado es "3"__


### objetos 

* Las propiedades de un objeto son similares a las variables; los métodos son similares a:

* [] operators
* [] properties
* [x] functions
* [] conditionals


* ¿Cuál es el resultado de la siguiente expresión?
var myString = "abcdef";
document.write(myString.length);

el resulsato es __________6_________

* Complete la expresión para crear un constructor de objetos, teniendo en cuenta que "altura" y "peso" son propiedades y "calcular" es un método para el objeto dado:

function mathCalc (height, weight) {

  this.height = ________height___;

  this.weight =  ______________weight________
;

  this.sampleCalc = _______________calculate________
;

}


### Objetos esenciales 

* Dada la matriz a continuación, complete la expresión para recibir una alerta con  "apple".
var fruits = new Array("pear", "orange",

"apple", "grapefruit");



alert(fruits_____[2]____);

* ¿Cuál es el resultado de la siguiente expresión?
alert(Math.sqrt(36));

* [] 0
* [] 12
* [] 36
* [x] 6


* omplete los espacios en blanco para mostrar los minutos actuales:
var date = new Date();

alert(_____date__.__get___Minutes());


* ¿Cuál es el resultado de este código?
var arr = new Array("a", "b", "c"); 
alert(arr[1]);


el resultado es "b"

* Arrastre y suelte las opciones siguientes para recibir una alerta con el valor de la constante PI.


La respuesta es______alert(Math.PI);


### Dom y Eventos

Complete los espacios en blanco para cambiar el contenido de todas las etiquetas de párrafo de la página a "SoloLearn".
var arr = ___document___.

  getElementsByTagName("____p___");

for(var x=0; x<arr.length; x++) 

{

   arr[____x____].innerHTML="SoloLearn";

}

* ¿Cuál es el resultado de este código?
<div id="test">
<p>some text</p>
</div>
<script>
var el=document.getElementById("test");
alert(el.hasChildNodes());
</script>
* [] false
* [x] true
* [] undefined

* Arrastre y suelte las opciones siguientes para cambiar el color del párrafo con id = "p2"" a red.
<script>


var d = document.
    

______getElemetById______("__p2___");


d.__Style__.____color___="red";


</script>

* ¿Puede manejar varios eventos en el mismo elemento HTML?

* [] No
* [X] Yes


* Complete los espacios en blanco para alertar un mensaje cuando se hace clic en el botón.
<button ____onlick_____="msg()">Click me</button>

<script>

 _______function__msg() {

  alert("Hi!");

}

</script>

* Muestre una alerta cuando el puntero del mouse esté sobre la etiqueta div:
<div _____onmouseover__="alert('Hi!');">

  put the mouse pointer over me

</div>

