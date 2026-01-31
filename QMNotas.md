# 2DO Bimestre MI CUADERNO

## Matias Quinchiguano

## Programacion II

## GR3SW

## GITHUB

Github con las imagenes del Cuaderno

link Github: [GITHUB LINK NOTES](https://github.com/matiSae/QuinchiguanoNotes2DOBimestre)

## TEMA 1

### Arquitectura Empresarial

Usado en los aplicativos de alta demanda son importantes par adefinir como se trabajara un proyecto, se hablo en especial del N-TIer : El cual se enfoca en la filosofia de n capas , osea dividir el proyecto en distintas capas, donde la capa superior llama a la inferior y en viceversa la ultima llama al inmediato superior.

#### Capa Usuario(GUI)

Considerada la aplicacion que carrea la app, en la misma se debe considerar los controles de usuario, se puede leer carpetas distintas por medio de visualizaciones de la app mediante el uso de Controles de usuario customizado heredadi de UC UserCustom

#### Capa Business Logic (BL)

Existen distintas entidades que solucionan los problemas que presente un proyecto, el mismo usa controladores y es donde se definen las reglas del negocio, en esta capa se resuelve codigo por medio de informacion.

#### Capa Base de Datos (DAC)

En la misma se guarda la informacion y necesita objetos especiales de acceso como los DAO , la base de datos en SQL el cual recibe los datos, el DAO lee los datos. Otro componente necesario es el SqlHelper, el cual ayudara a evitar bloqueos.

El DTO es el objeto de transferencia de datos , los encapsula y manda los datos a las otras capas.

Para el 2Do Bimestre se uso SQlite como la data base para guardar la informacion en tablas, la informacion debe ser normalizzada.

### BASE DE DATOS

Existen normalizaciones para las tablas y su creacion como lo son relacion de uno a uno, uno a muchos y muchos a muchos.

#### Tablas

Las soluciones / tablas tendran siempre un PK que no se puede repetir un FK si es datos de una tabla distinta, PK unico, es el cluster de la tabla siendo normalmente la id de la tabla.

Seguidamente se realizaron ejemplos en tablas distintas como en tabla persona, donde se enseño a segregar datos , datos basicos y datos restantes, como relacionar distintas tablas usando las normalizaciones.

#### Pasos y Catalogo

Los pasos para realizar las tablas son : idealizar que realizar, ver como funciona el programa , observar los datos, observar los datos comunes, Campos calculado no se pueden poner como la edad que varia en el tiempo. Cuando hay mucho de algo es una tabla separada.

Existen distintas formas de crear tablas como Autorizadas o Compaetacion(Catalogos), los catalogos son un data Master, usan ORM , mapean los datos y crean clases.

Luego se explico como funciona el SQLite e instalar los jdbc.

### POO

Se explicaron algunas cosas extra de UML  como Composicion, Agregacion siendo de alta dependencia o de baja dependencia y palabras claves para saber que usar como Deriva, Implementacion o usar, como algunas pueden tener 1 o mas cantidad de veces de uso donde se les puede restringuir mucho mas.

### Arquitectura

En la siguiente clase se presento como sera la arquitectura para usar en los proyectos siendo un PresentLayer, BusinessLogic, DataAccesLayer, DTO y la base de datos.

## Clases Grabadas para eXobot

En las clases grabadas se mostraron como se usan los DAO , DTO, las clases que los compoenen y el codigo estandarizado que se usara para todos los DAO y DTO, incluyendo un IDAO para las acciones de DAO. Todos los DAO deben usar el DataHelper para organizar el DAO usando el CRUD, Create, Read, Update y Delet, si se usan tdatos cambiados el dataHelper no usara el CRUD.

El DTO tendra los datos de las tablas usando una sintaxis de codigo normal y estandarizando el uso del toString para presentar todos los datos usados.

### Exceptions

Se explico la importancia de los exceptions la cantidad que existe para mostrar errores usados para ejecutar el codigo si incluso genera un error, por lo que fue necesario el uso de Exceptions personalizadas para mostrar a la parte tecnica y la parte de usuario. El uso del Factory y las graficas del Mer para los diagramas

### Properties

Antes de la GUI se presento la importancia de el app properties que manejara el ruteo necesario para cuando se use en otra maquina, clave- valor.

Finalmente se vieron como las tablas fueron creadas y como se usaron controles customizados como botones o layers los cuales son necesarios ya que definen a la aplicacion y estandarizan que no cambien en el tiempo. Se explicaron los Labels y los paneles. Finalmente necesitamos la CMD para mostrar los datos ocultos al programador o al usuario.

## Fin

Se creo una carpeta con las fotografias de los apuntes de las clases a papel.
