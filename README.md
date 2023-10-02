**PRUEBA FINAL DE TRATAMIENTO DE DATOS**

**ANTECEDENTE**

Con el fin de aplicar los conocimientos adquiridos en la materia de tratamientos de Datos de las tres clases se plantea la prueba final.

Consigue extraer datos de una fuente de datos online.

Almacenar esta información de forma estructurada en una base de datos en la nube, puede
ser tipo MongoDB.

Contiene el código relacionado con la extracción de datos, un archivo requirements.txt con las dependencias necesarias y los archivos .py que se requieran

**OBJETIVO**

El objetivo de la prueba final, es aplicar los conocimientos recibidos en la materia, la cual consiste en registrar información obtenida desde un servicio web en una base de datos MongoDB.

**REQUISITO BASICOS**

- Crear y configurar una cuenta github.
- Instalar y configurar PyCharm, Postman y Mongo DB.
- Conocer el lenguaje de la programación Python de manera básica.
- Conocer Flask de manera básica.
- Conocer la base de datos Mongo DB de manera básica.

**DESCRIPCIÓN DE LA SOLUCIÓN**

- Crear y configurar una base de datos Mongo DB.
- Utilizar librerías flask, pymongo, Python y requests.
- Utilizar un servicio web.
- Realizar el proceso de extracción de información.
- Realizar el proceso de almacenamiento en la Base de datos Mongo DB.
- Guardar los cambios de la solución del servicio web en un repositorio GitHub.

**DISEÑO DE LA SOLUCION**

- **DIAGRAMA DE ARQUITECTURA**

![Diagrama_Arquitectura.PNG](Diagrama%2FDiagrama_Arquitectura.png)

- **ESRUCTURA DE BASE DE DATOS**

Motor de Base de datos MongoDB

Colección: REGISTROS\_PRUEBA-FINAL

Campo 1: COMPANIA

Campo 2: PRECIO

Campo 3: FECHAREGI

- **DIAGRAMA DE FLUJO**

![Diagrama_flujo.PNG](Diagrama%2FDiagrama_flujo.png)

**DESARROLLO**

Para desarrollar el proyecto, se sigue los siguientes pasos:

- Tener instalado y configurado el ambiente de la base de datos Mongo DB y PyCharm.
- Configurar una cuenta github y crear el repositorio CiberseguridadGA-Prueba-Final para guardar los versionamientos del proyecto 
- Crear el archivo requirements.txt para incluir las librerías necesarias para el servicio web como flask, pymongo, Python y requests.
- Crear los archivos en el  proyecto CiberseguridadGA-Prueba-Final

![](Aspose.Words.efa6a8c4-3b56-4e85-9187-b2eb62cf17b3.003.png)
![Proyecto.PNG](Diagrama%2FProyecto.png)

- EL archivo requirements.txt para incluir las librerías necesarias para el servicio web como flask, pymongo, Python y requests.
- El archivo utils.py, mismo que contiene la consulta de información a ser utilizada para el registro en la base de datos.
- El archivo mongodb, contiene la clase MongoDriver con sus atributos y métodos a ser consumidos en otros procesos. 
- El archivo app.py, mismo que ejecuta las consultas y posterior registro de información obtenida (colección de registros) en la base de datos.

**CONCLUSIONES**

- Se aplico los conocimientos adquiridos en la materia de tratamientos de Datos e investigando y realizando las practicas se reforzo los conocimientos.

**REFERENCIAS**

<https://readme.so/>

<https://account.mongodb.com/account/login>

https://github.com/session
