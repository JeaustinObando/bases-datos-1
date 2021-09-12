#Nombre:Jeaustin Obando 
#Carnet: 2020067573
# Estándar de nombres

> ### Índice:
>
> > #### 1.  [`Introducción y justificación`](#Introducción y justificación).
> >
> > #### 2.  [`Entidades`](#Entidades).
> >
> > #### 3. [`Atributos`](#Atributos).
> >
> > #### 4. [`Tipos de datos a usar para atributos`](#Tipos de datos a usar para atributos).
> >
> > #### 5. [`Llaves primarias`](#Llaves primarias).
> >
> > #### 6. [`Llaves foraneas`](#Llaves foráneas).
> > 
> > #### 7. [`Índices`](#Índices).



<a name= "Introducción y justificación"></a>

> ### - Introducción y justificación
>
> ​	Conforme se programa se aprende a que existe un standard para todo en la programacion en esta ocasion veremos hacerlo con Entidades, Atributos, Tipos de Datos que se utilizan para atributos, Llaves Primarias, Llaves Foraneas e Indices, con todo esto se describirá una propuesta de estándar a usar en MySQL 8 el cual permite una sencilla comprensión de términos. Además es un estándar sencillo de adaptar a otras posibles aplicaciones fuera de MySQL 8.
>
> A continuacion se presentara un poco del estandard antes mencionado para la facilidad y comprension de otros programadores es en Español. Ademas se utilizará el guión bajo para separar palabras de una manera más sencilla y las palabras con normalidad seran utilizadas en miniscula, esto para acortar las búsquedas de nombres y facilidad a la hora de diferenciar los tipos, cabe recalcar que se intenta una mayor comprension del codigo y su forma de ser creado.



<a name= "Entidades"></a>



> ### - Entidades
>
> > ##### - Descripción del estándar:
> >
> > Deben cumplir con las siguientes requerimientos:
> >
> > 		1. Los nombres serán en Español.
> > 		2. Serán con la primer letra en mayuscula y lo demas en miniscula.
> > 		3. Los espacios se representarán con el guión bajo. 
>
> >##### - Ejemplos:
> >
> >​	`create table Libro()` , `create table Libro_estudiante()` 
> >
>
> > ##### -Excepciones:
> >
> > ​	Una excepción sucederá en caso de que ya exista se comenzara la segunda palabra con mayuscula para diferenciarla:
> >
> >​	` create table Libro_Prestamo()` , `create table Libro_Estudiante()` 



<a name= "Atributos"></a>



> ### - Atributos
>
> > ##### - Descripción del estándar:
> >
> > ​	Deben cumplir con las siguientes requerimientos:
> >
> > 	1. Estos serán escritos en Español.
> > 	2. Toda la palabra será escrita en minisucula.
> > 	3. En el caso de llevar espacios serán representados con guión bajo.
>
> > ##### - Ejemplos:
> >
> > `codigo`, `titulo` o `carnet_estudiante`
>
> > ##### - Excepciones:
> >
> > `carnet_Estudiante`, `carnet_Prestamo`.




<a name= "Tipos de datos a usar para atributos"></a>
> ### - Tipos de datos a usar para atributos
>
> > ​	Deben cumplir con las siguientes características:
> >
> > 	1. Estos serán escritos en inglés.
> > 	3. Se escribirá en miniscula.
> >    
>
> > ##### - Ejemplos:
> >
> >  `int`, `varchar` o `char`
>
> > ##### - Excepciones:
> >
> > No existe una excepcion. 




<a name= "Llaves primarias"></a>
> ### - Llaves primarias
>
> > ##### - Descripción del estándar:
> >
> > ​	Deben cumplir con las siguientes características:
> >
> > 	1. Estos serán escritos en Español.
> > 	2. Todo el nombre será escrito en mayúscula para diferenciarles del resto.
> > 	3. En el caso de llevar espacios serán representados con guión bajo.
> >     
>
> > ##### - Ejemplos:
> >
> > `CARNET`, `CODIGO`, `PRESTADO`
>
> > ##### - Excepciones:
> >
> > No habrán excepciones.





<a name= "Llaves foráneas"></a>
>### - Llaves foráneas
>
>> ##### - Descripción del estándar:
>>
> > ​	Deben cumplir con las siguientes características:
> >
> > 	1. Estos serán escritos en Español.
> > 	2. Todo el nombre será escrito en minúscula.
> > 	3. En el caso de llevar espacios serán representados con guión bajo.
> >  
>
>> ##### - Ejemplos:
>>
>> `carnet_estudiante` o `codigo_libro`
>
>> ##### - Excepciones:
>>
>> `carnet_Estudiante` o `codigo_Libro`





<a name= "Índices"></a>
> ### - Índices
>
> > ##### - Descripción del estándar:
> >
> > ​	Deben cumplir con las siguientes características:
> >
> > 	1. Estos serán escritos en Español.
> > 	2. Todo el nombre será escrito en minúscula.
> > 	3. En el caso de llevar espacios serán representados con guión bajo.
> > 	4. Se escribirá indice antes de cada Índice.
> >     5. La primera letra de la palabra siguiente es en mayuscula.
> >    
>
> > ##### - Ejemplos:
> >
> > `indice_Estudiante` o `indice_Libro`
>
> > ##### - Excepciones:
> >
> >  `INDICE_Estudiante` o `INDICE_Libro`
