CÓMO CONSUMIR UN REPOSITORIO DE UN PROYECTO JAVA EN GITHUB PARA IMPORTARLO EN ELCIPSE
==========================================================================================
SELECCIONAR y COPIAR LA URL DEL REPO: Pej https://github.com/Valexx55/FEMXA_211_JAVA_BASICO

EN ECLIPSE, Botón derecho sobre un area en blanco de project o package explorer e IMPORT

IMPORT -- GIT -- Projects from git -- Clone Uri -- Siguiente, siguiente siguiente

Resolver los posibles problemas de dependecias. Botón derecho sobre la carpeta raíz del proyecto

y selecciono Properties -- JAva Build Path // add external jars ( o remove ) 

También es posible tener que editar la librería JRE por la carpeta JDK

===========================================================================================


A continuación, se repasan los CONCEPTOS clave vistos, tanto práctica como teóricamente:

CLASE: La unida básica de modelado en Java. Es un fichero .java. Sólo dos criterios se emplean en la definición de una nueva
clase: por su funcionalidad ("vale para algo") o por su naturaleza ("representa algo")
Una clase tiene atributos y métodos. Se nombran en mayúsculas, en CamelCase.

OBJETO: Instancia concreta de una clase

CONSTRUCTOR: Método definido implícitamente para cada clase con su mismo nombre que permite la instaciación de objetos de esa clase

PUBLIC, PRIVATE: Modificadores de visibilidad. Por defecto, atributos privados.

[]: Al lado de un clase, representa un ARRAY o colección de una Clase. Su tamaño es fijo.

MAIN: Clase que contiene el método main, por el que empieza la ejecución del programa

BUCLES: N -- for | 0 a N while | 1 a N do while

IF: if (expresión/valor booleana) {} else {}

FOR EACH: for (Object o : Collection)

&& Operador lógico booleano que representa el "AND"

|| Operador lógico booleano que representa el "O"

% Módulo

BEAN: Clase básica con sus atributos y métodos de acceso (getters y setters)

THIS: Palabra reservada que puede aparecer en dos contextos: En un Constructor, donde representa el objeto en ciernes, o en otro método, 
donde representa el objeto llamante

STATIC: Si un método es static, es que está definido a nivel de clase. Si esto ocurre, el método se invoca directamente desde el nombre
de la propia clase (no es necesario objeto) Su comportamiento, por tanto, no varía en función del objeto llamante.
 
NO STATIC: Si un método no es static le llamamos "dinámico" lo que implica que funciona de forma distinta según con qué objeto se invoque.
Es necesario en métodos cuyo resultado depende del estado del objeto llamante. Si un método no es estático, es necesario invocarlo a través
de un objeto (la mayoría de los métodos son "no estáticos).

JAR: Agrugpación de archivos .class relativos a un proyecto que se empaqueta en este formato para su reutilización y distribución

JSE: Librerías estándar de lenguaje que integran por ejemplo las clases como String, Scanner, System...etc. Una versión concreta del JSE
determina una versión del lenguaje 

JDK: Conjunto de herramientas que me permite construir y ejectuar un programa Java

JAVADOC: Herramienta incluída en el JDK que transforma los comentarios /** */ de código en páginas web

TODO: //TODO Comentario para marcar por donde te quedas o qué hay pendiente de hacer. Importantísimo comentar

API: Conjunto de clases y métodos de un determinado producto o librería que queda a mi disposición cuando programo

MAVEN: Tecnlogía que: 1 Representa un repositorio donde almacenar librerias de java y poder compartirlas así con el resto 2 Permite 
la creación de proyectos con una estructura estándar 3 Gestión de dependencias de forma declarativa en el pom.xml 


JDBC: API que permite el acceso a Bases de datos relacionales. Clases importantes: DriverManager, Connection, ResultSet y Statement

EXCEPTION: Clase que representa un comportamineto anómalo en la ejecución de un programa.
Puedo capturarlas con try/catch o try/catch/finally y además propagarla con throw

LOG4J: Librería para loguear los eventos de un sistema/app, con distintos tipos de prioridad


HERENCIA: Se representa usando la palabra reservada extends y define una relación de jerarquía entre dos clases. La clase hija, 
hereda los atributos y métodos de su clase padre.Si una clase, redefine un método heredado, a eso lo llamamos sobreescritura (Overwrite)
lo que puede dar lugar al polimorfismo.

POLIMORFISMO: La capacidad del lenguaje Java para determinar en tiempo de ejecución el tipo más concreto (clase) al que aplica un método

=================================================================================================================================

Cosas básicas que quedan pendientes de ver por motivos de tiempo

Interfaz,
Orden natural (Comparable), orden total (Comparator)
El método equals de Object,
Colecciones (Mapas),
Ficheros y serialización de objetos







