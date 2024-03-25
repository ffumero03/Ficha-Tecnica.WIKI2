<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
En esta sección, presentamos la estructura organizativa de la aplicación médica, "SIMEDCI", diseñada para el hospital "Su Salud Primero". Desde el frontend, donde los usuarios interactúan con la aplicación, hasta el backend, donde se maneja toda la lógica y la gestión de datos, se examinará cómo se distribuyen y conectan los diferentes componentes de la aplicación en cuestión, para ofrecer una experiencia coherente y eficiente.
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
Para mostrar la organización de la aplicación "SIMEDCI", se proporcionará imágenes con fines ilustrativos que representan las carpetas, clases e interfaces que podrían estar presentes en cada proyecto. Es importante destacar que estas representaciones son útiles como referencia inicial, pero pueden estar sujetas a cambios en informes posteriores a medida que avancemos en el desarrollo de la aplicación.
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
Para la parte del frontend, la hemos organizado en un único directorio llamado WEB-UI.
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> WEB-UI: Este proyecto contiene subdirectorios importantes correspondientes al patrón MVC (Modelo-Vista-Controlador):
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
En la carpeta "wwwroot" se encuentran todos los recursos estáticos que son necesarios para la interfaz de usuario web. 
Esto incluye archivos CSS para definir estilos visuales, scripts JavaScript para añadir interactividad y funcionalidades dinámicas, así como imágenes para elementos visuales como logotipos, iconos y fotografías. Estos recursos son esenciales para la experiencia del usuario en nuestra aplicación web.
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
Views: Aquí se encontrarán los archivos de vistas (archivos".cshtml") que los usuarios verán en sus navegadores. Estos interactúan con los controladores.
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
Controllers: Contiene la lógica que maneja las acciones del usuario y se comunica con el backend. Por ejemplo, reciben las solicitudes del usuario desde las vistas y ejecutan las acciones correspondientes.
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
En la Figura 3 se muestra la estructura del proyecto MVC proporcionada por Visual Studio. Esta estructura incluye carpetas predeterminadas como "Controllers", "Models" y "Views", las cuales están diseñadas para organizar el código de acuerdo con el patrón de diseño Modelo-Vista-Controlador (MVC).
</p>


<center>

**Figura 3.
Proyecto WEB-UI.**

![ProyectoWebUI.JPG](/.attachments/ProyectoWebUI-0b26389a-991e-491e-a945-4c99cb71a997.JPG)

**Fuente**: Elaboración propia.

</center>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
Para la parte del backend, se cuenta con cuatro proyectos principales que conforman la aplicación:
</p>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
DTO: En este proyecto se definen los modelos de datos que se utilizan para transferir información entre las diferentes capas de la aplicación. Estos objetos suelen ser simples contenedores de datos y no contienen lógica de negocio. La organización propuesta para estos objetos se expone en la Figura 4.
</p>

<center>

**Figura 4.
Proyecto DTO.**

![Proyecto DTO.JPG](/.attachments/Proyecto%20DTO-9406d2bd-a5c7-4024-9955-b2ef0d0da5ba.JPG)
**Fuente**: Elaboración propia.

</center>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
API: Este proyecto sirve como punto de entrada al backend de nuestra aplicación. Aquí se encuentran los controladores que gestionan las solicitudes HTTP y coordinan las respuestas con el resto de la aplicación. La organización propuesta para este tipo de proyecto se expone en la Figura 5.
</p>

<center>

**Figura 5.
Proyecto API.**

![Proyecto API.JPG](/.attachments/Proyecto%20API-58180769-c9b3-4365-8c40-2d70656300a6.JPG)

**Fuente**: Elaboración propia.
</center>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;">
AppLogic: En este proyecto se desarrolla la lógica principal de la aplicación. Aquí se definen las reglas de negocio, se procesan los datos y se llevan a cabo las operaciones más complejas. La organización propuesta para este tipo de proyecto se expone en la Figura 6.
</p>

<center>

**Figura 6.
Proyecto App-Logic.**

![ProyectoApplogic.JPG](/.attachments/ProyectoApplogic-f1e3e4fe-3c9c-47f6-92ab-8afc38b840d0.JPG)
**Fuente**: Elaboración propia.
</center>

<p style="text-indent:20px; line-height:2; font-family: Arial, sans-serif; font-size: 12pt; text-align: justify;"> DataAccess: Este proyecto gestiona la interacción con la base de datos. Contiene una carpeta Crud para las operaciones CRUD, una carpeta "Dao" para gestionar la comunicación con la base de datos, que incluye clases para definir operaciones y establecer conexiones y una carpeta Mapper para mapear objetos de la base de datos a objetos DTO y viceversa. Dentro de Mapper, hay una subcarpeta llamada interfaces donde se definen los métodos para estas conversiones. La organización propuesta para este tipo de proyecto se expone en la Figura 7.
</p>

<center>

**Figura 7. 
Proyecto DataAccess.**

![Proyecto DataAccess.JPG](/.attachments/Proyecto%20DataAccess-742ff0f3-1744-4b14-a8b1-34f10d02b460.JPG)
**Fuente**: Elaboración propia.
</center>
