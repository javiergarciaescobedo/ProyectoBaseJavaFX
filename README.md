# ProyectoBaseJavaFX
Proyecto que puede servir de base para una aplicación que utilice la librería gráfica JavaFX.

Utiliza gradle como herramienta para automatizar la compilación del proyecto y descarga de las librerías necesarias.

Se ha configurado para que genere un archivo ejecutable JAR multiplataforma, que podrá encontrarse en la carpeta build/libs.

Ha sido generado con NetBeans 12.0 y JDK 11

## Personalización del proyecto
Cambia el **nombre del proyecto** en el archivo *settings.gradle*

El **nombre del paquete** (ProyectoBaseJavaFX) se debe indicar en el archivo *build.gradle*, por lo que si cambias el nombre
del paquete en el que se encuentre la clase principal (Main) o el lanzador (Launcher), debes cambiarlo en estas líneas:

`mainClassName = 'ProyectoBaseJavaFX.Main'`

`attributes 'Main-Class': 'ProyectoBaseJavaFX.Launcher'`