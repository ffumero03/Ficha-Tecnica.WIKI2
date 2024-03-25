<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
Esta sección incluirá los estándares para csHTML, C#, JS y SQL los cuales tendrán el desarrollo del código del proyecto, esto considerando que determine la forma en la que se modificara el proyecto. 

### **Estándares Generales**

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben validar las funciones del código que lo requieran.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Los idiomas utilizados en el código es español e inglés cualquiera que no sea ninguno de los mencionados no serán permitidos.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Cualquier parte del código que tenga un nivel de complejidad alto será obtendrá un comentario explicándolo

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Las carpetas se van a crear acorde la estructura de navegación, no se deben crear carpetas que no sigan la estructura. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Carpeta y archivos en la codificación tendrán nombres únicos. 


<center>

**Tabla 1.**
**Nomenclatura de Variables** 

|Tipo|Descripción  |Estilo  |Ejemplo  |
|--|--|--|--|
| Global | Nombres de las variables golables deben ser descriptivas | PascalCase | UsuarioId |
| Variables Locales | Variables dentro de metodos deben ser descriptiva y especificar el tipo de dato | camelCase | nombreDeUsuario |
| Constante | Nombres de constantes, deben ser lo mas descriptivas posible y deben representar su uso | PascalCase | UsuarioId |

**Fuente**: Elaboración propia.

</center>

<center>

**Tabla 2. Abreviaturas Definidas**


| Abreviatura | Palabra |
|--|--|
| sec | seccion |
| form | formulario |
| rep | reporte |
|sed|sede|
|nom |nombre|


**Fuente**: Elaboración propia.

</center>



### **Estandares csHTML** 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se utilizará la versión ASP.NET para aquellos documentos tipo .html.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se utilizará la declaración DOCTYPE al inicio del archivo csHTML.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- No está permitido utilizar tildes ni la ene(ñ) en el nombramiento de ID ni clases. La ñ será sustituida por doble nn por ejemplo “mannana” o “annejo”. Excepto la palabra año, la cual sería sustituida por la palabra “anio”. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- En la sección de los headers se deben incluir los enlaces de los estilos de los archivos. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Todas las etiquetas y elementos csHTML deberán ser declarados tipo camelCase. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se prohíbe implementar estilos en archivos csHTML, en caso de estilos cada uno deberá tener su archivo CSS.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Los archivos csHTML deberán cumplir con su formato, “nombreDeArchivo.html”.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Los archivos csHTML y CSS deberán obtener su carpeta correspondiente. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben seguir los estándares de indentación csHTML y CSS. 

<center>

**Tabla 3. Nomenclaturas csHTML**

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 

|Tipo|Descripción  |Estilo  |Ejemplo  |
|--|--|--|--|
|List  |Para definir elementos de tipo lista   | camelCase  | lstDeFormulario |
|Table  | Para definir elementos de tipo tabla  | camelCase | tblDeFormulario |
|Select | Para definir elementos de tipo select |camelCase |slcFecha | 
|Input dateTime  | Espacio para entrada de dato tipo datetime | camelCase |dtConsulta|
|Input time  |Espacio para entrada de dato tipo time   | camelCase | tDia |
|Input date  | Espacio para entrada de dato tipo date  | camelCase | dDeConsulta |
|Input button  |Espacio para entrada de dato tipo button   | camelCase | bConfirmarCita |
| Input number | Espacio para entrada de dato tipo number  | camelCase | nDeEdad |
| Input checkbox | Espacio para entrada de dato  tipo checkbox  | camelCase | chkFemeninoOMasculino |
| Input texto | Espacio para entrada de dato tipo texto en una sola línea | camelCase | txtNombre |

**Fuente**: Elaboración propia
</center>


### **Estandares C#**

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- El código utilizar la versión más reciente y estable de C#.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe mantener una indentación consistente en todo el código.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben utilizar nombres descriptivos para los métodos, variables y clases.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe hacer uso de comentarios en partes complejas del código. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe hacer uso de interfaces para definir contratos. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben manejar las excepciones de manera adecuada, evitando el uso de bloques try-catch genéricos al proporcionar mensajes de error. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe utilizar operaciones asincrónicas para evitar el bloqueo de interfaz así como async/await. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben utilizar pruebas unitarias para el correcto funcionamiento de clases y métodos. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe utilizar LINQ para consultas y manipulación de datos de manera eficiente. 

<center>


**Tabla 4. Nomenclaturas C#**

|Tipo|Descripción  |Estilo  |Ejemplo  |
|--|--|--|--|
| Clase  | Nombre de clase | Pascal | Usuario |
| Interfaz | Nombre de interfaz | Pascal | 1erServicio |
| Metodo | Nombre de método | Pascal | ObtenerNombre |
| Variable | Nombre de variable | camelCase | edad |
| Constante | Nombre de constante | Pascal | Edad |
| Namespace | Nombre de los namesspace | Pascal | Clinica |
| Propiedad | Nombre de las propiedades | Pascal | NombreDeClinica |
| Evento | Nombre de los eventos | Pascal | CitaDeUsuario |
| Enum | Nombre de los enumerados | Pascal | Estado |

**Fuente**: elaboración propia.

</center>

### **Estandares JS**

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se utilizara la version mas reciente y estable de JavaScript para lograr los objetivos de software.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe mantener una indentacion consistente en todo el codigo, de 2 o 4 espacios para cada nivel.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- El codigo debera seguir las convenciones de nomenclatura establecidas, utilizando camelCase para nombres de variables y funciones, ademas, PascalCase para clases y constructores. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben utilizar nombres descriptivos y significativos para las variables, funciones y clases.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben utilizar comentarios para las partes complejas del codigo, para proporcionar aclaraciones.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe usar "use strict" al inicio de los archivos JavaScript para habilitar el modo strict y evitar errores comunes.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se debe modularizar el codigo utilizando el patron de modulos por ejemplo utilizando los import y export.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben escribir pruebas unitarias para las funciones y modulos JavaScript al utilizar frameworks de prueba. 

<center>

**Tabla 5. Nomenclaturas JS**


|Tipo|Descripción  |Estilo  |Ejemplo  |
|--|--|--|--|
| Namespace | Nombre de los namespaces | PascalCase | ClinicaOnline |
| Evento | Nombre de los eventos | camelCase | citaDeUsuario |
| Metodo | Nombre de los metodos de clase | camelCase | obtenerNombre |
| Clase | Nombre de clases | Pascal | UsuarioProducto |
| Funcion  | Nombre de las funciones | camelCase | obtenerUsuarios |
| Constante | Nombres de las constantes | Constante | PI |
| Variable | Nombre de las variables | camelCase | edadNombreUsuario |

**Fuente**: Elaboración propia.
</center>

### **Estandares SQL**

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Los nombres de las tablas deben ser en plural y representar la entidad que almacenan.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Los nombres de las columnas deben ser descriptivos y estar singular.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben utilizar indices en las columnas que se utilizan frecuentemente en clausulas WHERE y JOIN para mejorar el rendimiento.

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben utilizar constraints para garantizar la integridad de datos, como claves primarias, claves foraneas y restricciones de unicidad. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben escribir las consultas SQL de manera estructurada, utilizando indentacion y saltos de linea. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben parametrizar las consultas SQL para mejorar la seguridad. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben utilizar transacciones para la garantizar la consistencia de los datos en operaciones. 

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> 
- Se deben realizar copias de seguridad regulares de la base de datos para proteger contra perdida de datos. 

<center>

**Tabla 6. Estándares SQL**

|Tipo|Descripción  |Estilo  |Ejemplo  |
|--|--|--|--|
|  Tabla| Nombre de las tablas | snake_case | usuarios |
| Columna | Nombre de las columnas | snake_case | fecha_creacion |
| Constraint | Nombre de los constraints | snake_case | fk_pedido |
| Vista | Nombre de las vistas | snake_case | vs_producto |
| Indice | Nombre de los indices |  snake_case| ind_usuarios |
| Procedimiento | Nombre de los procedimientos | snake_case | proc_actualizar |
| Trigger | Nombre de los triggers |  snake_case| trg_actualizar |

**Fuente**: Elaboración propia.

</center>



