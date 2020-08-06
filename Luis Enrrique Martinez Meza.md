__Lenguajes de Programación__
====

Introducción
------------------

En la actualidad existen distintos lenguajes de programación que son utilizados para distintos propósitos: Desarrollo Web, Desarrollo Móvil, Sistemas Operativos, Inteligencia Artificial, etc. En este ensayo se trata el tema sobre como nacieron los lenguajes de programación, cuales han sido los lenguajes que han influenciado más en el desarrollo de los mismos, asi como las partes por las que pasa un código escrito en éstos lenguajes para poder saber si es un código válido o no, y las diferentes herramientas utilizadas para este fin.

-----------------------------

¿Qué es un lenguaje de programación?
-----------------------
* Un lenguaje de programación es un lenguaje que posee un conjunto de reglas gramaticales definidas y que nos ofrece la posibilidad de escribir instrucciones que pueden ser entendidas y ejecutadas por una computadora. Éstas reglas gramaticales definidas las podemos separar en:

    * **Léxico**: La función principal de éste es la de  identificar si se está utilizando la nomenclatura especificada por el lenguaje de programación, por ejemplo si se está utilizando los caracteres permitidos por el lenguaje. E.g:

        ```php 
        $variable = "Hello World"; 
        ```
        
        Haciendo un análisis léxico devolveria un error si estuviesemos trabajando con las reglas de JS ya que los nombres de variables no pueden llevar el caracter '$' pero si hacemos un análisis léxico usando las reglas del lenguaje PHP ésta linea de código cumpliría con el léxico del leenguaje. Para realizar una amálisis léxico se hace uso de elementos los cuales seran explicados mas adelante.


    * **Semántica**: La semántica se encarga de analizar el sentido que tiene el codigo escrito  por ejemplo verificar si la asignación de variable es la correcta, si un if tiene la estrucutura correspondiente, etc. E.g.:

        ```javascript
        A = 1
        B = 4
        C = D
        ```
        En este caso haciendo un analisis del código anterior, éste tendría un error de tipo semántico, ya que se está asignando  a la variable **C** el valor de una variable llamada **D**, la cual nunca fue declarada.

    * **Sintaxis**: Puede que sea el elemento más conocido sobre las reglas de un lenguaje, pues si no conocemos la sintaxis de un lenguaje de programación es casi imposible poder escribir y ejecutar código en éste. La sintaxis se encarga de revisar si el código que se quiere compilar o interpretar tiene la estructura correcta, la cual tambien es dada por el lenguaje de programacion en el que se esté trabajando. E.g:

        ```java
            if (2 > 1){
                System.out.println "Hola";
            }            
        ```
        En el codigo anterior si estamos trabajando en Java encontrariamos un error sintáctico, pues podemos ver que en la instrucción para escribir en consola hace falta los paréntesis que rodean el paŕametro que queremos imprimir, y vemos que ésta es una regla sintáctica ya dictada por el lenguaje Java.

---------------------------------------
¿Porqué son importantes los Lenguajes de Programación?
----------------------------------------
Podemos cambiar la pregunta a ¿qué pasaría si los lenguajes de programación no existieran?, en ese caso la respuesta sería que muchas de las cosas que conocemos en la actualidad quizás no existieran, pues muchas de éstas usan de una u otra manera un lenguaje de prgramación para poder llevar a cabo tareas o incluso funcionar. Un ejemplo serían los teléfonos móviles, por una parte para poder funcionar, los teléfonos utilizan un sistema operativo, el cual esta construido gracias a lenguajes de programación, por otra las aplicaciones que usan éstos teléfonos y las cuales son de gran utilidad para uno u otro fin tampoco existirían. Otro ejemplo es el internet, si no existieran lenguajes de marcas y lenguajes de script, ¿como podriamos visualizar el contenido que nos ofrece una página cada vez que ingresamos en ella?

A simple vista puede parecer que los lenguajes de prgramación solo son de interés para quienes los utilzan para hacer desarrollos, pero la verdad es que los lenguajes de programación son importantes para todos, tanto para quienes los utilizan para crear herramientas como para aquellos quienes van a utilizar ésta herramienta, en general, los lenguajes de programación nos ayudan a todos en general, he ahi su importancia.


En la actualidad podemos encontrar una gran variedad de lenguajes de programación para elegir dependiendo de lo que queremos hacer, pero para llegar a los lenguajes de programación que existen hoy en dia se ha tenido que pasar por un camino largo.

------------------------------
## Los lenguajes mas importantes que han contribuido con la evolución de los Lenguajes de Programación son:

### 1. **FORTRAN**

FORTRAN cuyo significado es **For**mular **Tran**smition es considerado el lenguaje de programación mas antiguo y que aun se utiliza en la actualidad. Su origen se remonta al año 1954 y se atribuye su creación a un cientifico de computadores estadounidense llamado John Backus, el cual trabajaba para la mepresa IBM.

El objetivo que se buscaba con la creación de este lenguaje era el poder traducir de manera facil y sencilla distintas fórmulas matemáticas a código que pudiera entender un computador.

Exiten versiones subsiguientes de éste lenguaje como son:
* FORTRAN II
* FORTRAN IV
* FORTRAN 66
* FORTRAN 77
* FORTRAN 90
* FORTRAN 95
* FORTRAN 2003
* FORTRAN 2008
    
### 2. **Lisp**
Lisp( **Lis**t **P**rocessing) fue el primer lenguaje de programación funcional en inventarse en el año de 1958 pero publicado hasta el año 1960, su núcleo se basa en la abstracción de funciones y la aplicación de la función, éste lenguaje es habitualamente usado en Inteligencia Artificial.

Como su nombre lo indica en Lisp las listas tienen una gran importancia, las listas enlazadas son una de las estructuras mas importantes en el lenguaje, tambien encontramos que su codigo fuente está compuesto de listas, lo cual permite la manipulacion de su codigo fuente, y esto, a su vez, permite la creación de macro sistemas.

### 3. **ALGOL 60**
ALGOL 60, acrónimo de **Alg**orithmic  **O**riented **L**anguage fue el resultado de los esfuerzos para poder diseñar un lenguaje que fuese universal para aplicaciones científicas, y que se convirtió en un estándar para la descripción de algoritmos, asi como tanbién introdujo la recursión.

### 4. **COBOL**
COBOL es una lenguaje de programación de alto nivel desarrollado por primera vez en 1960, el objetivo que se buscaba al crear COBOL era el de crear un lenguaje de programación universal, que pudiera ser utilizado en cualquier computador. COBOL quiere decir **Co**mmon **B**usiness **O**rineted **L**anguage y está diseñado en específico para el desarrollo de negocios.

Es un lenguaje de programación que se sigue utilizando en la actualidad aunque ha sufrido "actualizaciones" a través de los años y sigue siendo el lenguaje mas usado para los negocios.

### 5. **BASIC**
BASIC es un lenguaje de programación creado en 1964 y cuyo objetivo era que sirviera como un primer acercamiento hacia la programación para cualquier tipo de público, pero el área donde éste lenguaje fue mas popular fue en las microcomputadoras, que eran máquinas que podian colocarse en una mesa y usarse desde alli, con ésto tambien inicia la llegada de las computadoras a domicilios.

BASIC se volvió popular gracias a éstas microcomputadoras y también por la simplicidad del lenguaje, con comandos intuitivos, pero éste fue quedando atras tras la llegada de lenguajes que superaban por mucho los limites de éste, hasta que en 1991 llega Visual Basic, donde se aplicaban mejoras al ya mencionado BASIC.

### 6. **PROLOG**
Prolog del francés **Pro**grammation en **Log**ique fue el primer lenguaje de Programación basado en el paradigma de la programación lógica, surge a prinicpios de 1970. La programación en este lenguaje consiste en:
* Declara hechos sobre objetos y relaciones
* Definir reglas sobre estos objetos y relaciones
* Hacer preguntas

### 7. **Ada**
Ada es un lenguaje de programación orientado a objetos diseñado por el Departamento de Defensa de E.U.A., es un lenguaje multipropósito, orientado a objetos y concurrente, su nombre se eligió como conmemoración de **Ada Lovelace**, la cual es considerada la primer programadora de la historia, por colaborar con Charles Babbage en su máquina analitica.

Ada es usado generalmente en entornos donde la seguridad es primordial como aeronáutica, gestion de tráfico aéreo, la industria aéroespacial, entre otros. 

### 8. **SmallTalk**
SmallTalk fue el primer lenguaje de programación que soportó por completo la orientación a objetos. Estuvo disponible de forma publica hasta 1980. En SmallTalk todo es un objeto, y en donde estos se comunican a través del envío de mensajes.

La sintaxis de Smalltalk es diferente a la de la mayoría de los otros lenguajes de programación, en gran parte debido al uso de mensajes, en lugar de expresiones aritméticas y lógicas y declaraciones de control convencionales.

### 9. **C++**
C++ es un lenguaje de programación diseñado a mediados de los 80 y fue creado con el objetivo de extender las capacidades del lenguaje C añadiendo funcionalidades como la manipulación de objetos. Su nombre tiene el significado de "incremento de C" para dar a entender que se trata de una extensibilidad en las funcionalidades de ese lenguaje.

C++ se convirtió y sigue siendo un lenguaje con mucha popularidad y ampliamente utilizado en campos como Sistemas Operativos, Compiladores, Desarrollo de Videojuegos, etc.

### 10. **Java**
Java es un lenguaje de programación lanzado en 1995 y uno de los lenguajes mas utilizados en distintos campos de la computación, está basado en C++ pero su diseño es mas pequeño, simple y confiable. Una de las razones por las que Java se popularizó es la portabilidad, donde se puede ejecutar un programa compilado en un sistema operativo especifico en otro, sin tener ningun tipo de conflicto, como ocurre en los programas de C++.

Java puede ser utilizado en aplicaiones de escritorio, aplicaiones web, sistemas de servidor, aplicaciones móviles, etc.

### 11. **Lenguajes de Script**
Los lenguajes de script son lenguajes de programación que permiten el control de otros programas o aplicaciones, éste tipo de lenguajes se han populairzado en los ultimos años, los lenguajes de script dan mas importancia a la flexibilidad y facilidad de desarrollo de programas, incorporando elementos de alto nivel como **regexp** y estructuras de datos.

Éste tipo de lenguajes tambien se han vuelto populares por su sintaxis sencilla y fácil de aprender, ya que éste es uno de los puntos con mas importancia. Los lenguajes de script mas populares que existen son:
* Shell
* Perl
* Python
* Ruby
* Javascript
* PHP
* Lua

![TimeLine](https://raw.githubusercontent.com/LKezHn/EssayLLP/master/src/TimeLine.jpg "Linea de Tiempo")

-----------------------------------

Tipos de Lenguajes
-------------------------------
* ### Lenguaje máquina y lenguaje ensamblador
    * **El lenguaje máquina** es el único lenguaje que puede ser interpretado directamente por una computadora. Los códigos en éste lenguaje son cadenas de digitos binarios (bits) y que normalmente son transformados en numeros hexadecimales para poder ser modificados, aún asi éste lenguaje es muy complicado de entender y de escribir, además que su código varía dependiendo de cada computadora.

    * **El lenguaje ensamblador** se encuentra a un nivel por encima del lenguaje maquina, utiliza códigos mnemotécnicos cortos(códigos fáciles de recordar) para instrucciones y permite al programador introducir nombres a bloques de memoria que contienen datos. El lenguaje ensamblador está diseñado para ser fácilmente traducido a lenguaje máquina.

* ### Lenguajes Algorítmicos
    Los lenguajes algoritmicos son diseñados para expresar cálculos matemáticos o simbólicos. Con éstos se pueden expresar operaciones algebraícas como una notación similar a la matemática, también permite el uso de subprogramas para reutilización de código. Fueron los primeros lenguajes de alto nivel.

    Entre estos están:
    * FORTRAN
    * ALGOL
    * Lisp
    * C
    * Python

* ### Lenguajes Orientados a Negocios
    El uso de las computadoras para las aplicaciones de negocios se inició en la década de los 50's. Los lenguajes de negocios se caracterizan por las formas precisas de describir y almacenar números decimales y datos de caracteres, asi como la capacidad de especificar las operaciones aritméticas decimales.Entre los lenguajes más famosos se encuentran:

    * COBOL
    * SQL

* ### Lenguajes Orientados a la Educación
    Como su nombre lo indica estos lenguajes se utilizan en al ámbito de la educacion, sinendo desarrollados de tal forma que sean fáciles de entender y aprender para un público general.

    Algunos ejemplos de éstos lenguajes son:
    * BASIC
    * Pascal
    * Logo
    * HyperTalk
    * PSeint
    * Scratch
    
* ### Lenguajes Orientados a Objetos
    Los lenguajes de programación Orientados a Objetos sirven para gestionar la complejidad en programas extensos. La capacidad de éstos lenguajes para que solo las operaciones sean públicas pero el resto de detalles internos sean privados facilita la programación a gran escala al permitir que los programadores piensen en cada parte del progrma de una forma aislada.

    Ejemplos de éstos lenguajes de programación son:
    * C++
    * Ada
    * Java
    * Python
    * Visual Basic
    * PHP
    * Ruby

* ### Lenguajes Declarativos
    Este tipo de lenguaje a su vez se divide en:
    * **Lenguajes Lógicos**: en éstos lenguajes se trabaja en una forma descriptiva, estableciendo relaciones entre entidades. Un programa es ejecutado por un "motor de inferencia" que responde una consulta buscando éstas relaciones sistemáticamente para hacer inferencia que responderán una consulta.
    Ejemplos de éste tipo de lenguajes son:
        * PROLOG
        * Curry
        * Gödel
        * P Sharp

    * **Lenguajes Funcionales**: Éste tipo de lenguaje posee un estilo matemático, se enfoca en "qué" se hace y no en "como" se está haciendo. Un programa funcional se construye al aplicar funciones a argumentos. Los lenguajes funcionales son utilizados como herramientas de investigación en leguajes de desarrollo, en demostradores automátizados de teoremas matemáticos y en algunos proyectos comerciales. Ejemplos de éste tipo de lenguajes son:
        * Lisp
        * Haskell
        * Scala
        * Miranda

* ### Lenguajes de Scripting
    Los lenguajes de scripting aveces llamados lenguajes pequeños están diseñados de tal manera que sea posible la cmunicación con otro lenguajes, la caracteristica mas notable en un lenguaje de scripting es que es un lenguaje interpretado, asi que no es necesario compilarlo para poder ejecutar un código, por ésta razón éste tipo de lenguajes se considera un poco mas rápido que los lenguajes compilados. Algunos lenguajes de scripts se utilizan para escribir funciones o utilidades de los sistemas operativos como el caso de PERL, otros se usan en el ámbito de la programación web. Ejemplos de estos lenguajes:

    * Perl
    * Ruby
    * Python
    * JavaScript
    * PHP


* ### Lenguajes de Formateo de Documentos
    Éstos tipos de lenguajes se utilizan, como su nombre lo indica para dar formato a documentos de texto, éstos sirven para especificar de que forma se organiza el texto e imágenes en un documento, entre éstos se encuentran lenguajes de marcado, lenguajes con notación de formato de texto, notación matemática, lenguajes qie pueden ser interpretados por dispositivos de impresión para darle un estilo,etc. En éste tipo de lenguaje los mas conocidos son:
    
    * TeX
    * Latex
    * SGML (Standard Generalized Markup Language)
    * MarkDown
    * PostScript

* ### Lenguajes para visualización en la Web
    Estos lenguajes se encargan de poder visualizar contenido en una página web, como también en algunos casos darle cierto estilo a éste, por lo que también se pdorian considerar como lenguajes de marcado. Un ejemplo de ésto es HTML, donde su primer función es permitir visualizar el contenido de una página web, asi como también el de darle estilos a éste contenido mediante etiquetas. Ejemplos de éstos lenguajes son:
    * HTML
    * XML
    * Web Scripting
--------------------------------------

FSM (Finite State Machine)
------------------------------------------
Se puede decir que una Máquina de Estado Finito o Autómata Finito es una abstracción computacional, la cual describe el comportamiento de un sistema mediante un número finito de estados y un número finito de transiciones, las cuales indican al autómata a cual estado debe pasar al ocurrir un determinado evento. Éstas máquinas de estado finito normalmente son utilizadas en compiladores, y su función es la de realizar un ánalisis léxico de la entrada que se quiere compilar en determinado lenguaje de programación para así poder saber si ésta entrada contiene tokens que cumplen con los lexemas correspondientes al lenguaje, pero ¿que es un token?

Token
------------
Un token es uno ó mas caracteres que cumplen con los lexemas dados por el lenguaje de programación. Se pueden dividir como tokens de usuario, que comunmente son las variables que encuentra el compilador al leer la entrada, también están los tokens propios de lenguajes como ser: 
* Asignacion de valor a una variable
* Concatenacion de cadenas
* Palabras reservadas
* Etc.

Autómata Finito Determinista (DFA)
----------------
Un autómata finito determinista es aquel en el cual una entrada que se encuentra en un estado del autómata solo puede hacer la transición a un único estado, esto quiere decir que las transiciones solo pueden ser al estado actual o a otro estado.

Para poder entender un diagrama FSM primero debemos enteder que es un diagrama de estados.

### **Diagrama de Estados**
Los diagramas de estado son estructuras donde se muestra un conjunto de estados por los que pasa un objeto o elemento durante su vida, asi como las acciones,respuestas y eventos que provocan que el objeto cambie de estado,los diagramas de estado nos permiten entender de una forma más intuitiva éstos distintos estados, ya que se puede decir que el propio diagrama nos va guiando.

Éste es un ejemplo de un diagrama de Estados:

![Diagram of State](https://raw.githubusercontent.com/LKezHn/EssayLLP/master/src/2Diagrama_Estados.jpg "Diagrama de estados")
---------------------- 
### **Diagrama FSM**
Un diagrama de estado finito nos permite entender, explicar y  construir de una manera mas sencilla y rápida un autómata finito, pues al ver éste de una forma gráfica se vuelve menos complejo, de igual forma al momento de llevar a código nuestro automata es muhco mas fácil, pues ya tenemos la idea de como será, cuantos estados y transiciones tendrá, en que momento se saldrá del estado, etc., algo que si intentamos hacer sin crear el diagrama se vuelve una tarea larga y confusa. 

A continuación un ejemplo de un diagrama FSM donde se explica la simbología del mismo:

![FSM Diagram](https://raw.githubusercontent.com/LKezHn/EssayLLP/master/src/FSM_Diagram.jpg "Diagrama FSM") 

-----------------------------------

Gramáticas Libres de Contexto
--------------------------
Los analizadores sintácticos (parsers) utilizan  gramática libre de contexto, la cual es una gramática formal en la que cada **regla de producción** es de la forma:

#
    E -> w
#

Donde E es un simbolo no terminal y w es una cadena de terminales o no terminales. Un ejemplo de una gramática libre de contexto usando la expresion regular
#
    01*0
#
 La gramática libre de contexto sería de la forma:

#
    E -> S
    S -> Z O Z
    Z -> 0
    O -> 1 | 1 O
#

Estas gramáticas libres de contexto tambien son usadas por **Parsers**

Parsers
--------------
Los parsers tambien llamados analizadores sintácticos es un programa que evalua una entrada dependiendo de la  gramática formal del lenguaje. Éstos parsers convierten la entrada en estructuras de árboles para poder analizarlas. La entrada que recibe el parser son los **tokens** generados por el analizador léxico.

Éstas estructuras de árboles son llamadas **arboles de parseo** los cuales usando las gramáticas libres de contexto analizan la estructura del token.

Dependiendo de como el parser recorre el arbol de parseo contruido se puede clasificar en:
* LR
* LL
* LALR
* SLR
-----------------------------

## Conclusiones

1. Los lenguajes de programación en la actualidad son de mucha importancia, tanto para los que hacemos uso de ellos como para los que se benefician de las tecnologias creadas con ellos.

1. Sabiendo como funciona el análisis léxico, sintáctico y semántico es posible crear un lenguaje de programación propio con una sintaxis distinta a la de los lenguajes ya existenes.

1. Los automatas finitos son de gran utilidad al momento de encontrar un patrón o identificar tokens, además es una alternativa para las expresiones regulares, que, aunque comunmente no se nos limita su uso siempre es de utilidad conocer otra forma para realizar la misma función de éstas.

1. Existen distintos tipos de analizadores sintácticos, dependiendo el recorrido, el cual al crear un lenguaje de programación de una manera mas formal debemos elegir cual usar dependiendo de las necesidades que se tengan.

1. Los lenguajes de programación están en constante crecimiento y evolución, y aunque existe un sinnúmero de lenguajes todos aportan caracteristicas interesantes t diferentes, que hace que cada vez los lenguajes de programación sigan avanzando en su evolución.
-------------------------------------------------
## Bibliografía

* Conceptos de Lenguajes de Programación, 10ma Edición, Robert W. Sebesta, University of Colorado at Colorado Springs.

* Introducción a la computación, lenguajes y teoría de los autómatas, 2da Edición, John E. Hopcroft, Rajeev Motwani, Jeffrey D. Ullman.



