# archimate


# Ejercicio Diagramas en Archimate
Universidad Francisco Jose de Caldas
Presentado a:
Ingeniero Alejandro Daza - Informatica 1

# Integrantes:
 - Wilson Heli Villamizar Valencia (20201099050)
 - Jhon Fredy Torres Ramírez (20201099048)
 - Alejandro Lopez Castañeda (20201099037)


# Objetivo de la solución
Elaboración de 3 puntos de vista en Archimate para un sistema que permita realizar la gestión correspondiente a la revisión y seguimiento de proyectos de grado en la universidad Distrital Francisco José de Caldas.

# Punto de vista de la organización
![WhatsApp Image 2020-05-04 at 8 53 21 PM](https://user-images.githubusercontent.com/28465837/81029280-ed1bcb80-8e49-11ea-98db-33011df1f406.jpeg)
# Punto de vista de las funciones de negocio
![WhatsApp Image 2020-05-04 at 8 53 21 PM (1)](https://user-images.githubusercontent.com/28465837/81029328-0fade480-8e4a-11ea-8828-ebab305c50c0.jpeg)
# Punto de vista del proceso de negocio

# Estructura de Aplicación
![Estructura de Aplicación](https://user-images.githubusercontent.com/42079368/82276677-87503900-994b-11ea-9aca-899b3910b6f9.jpg)

# Analisis de  landscape Map Viewpoints 

landscape Map Viewpoints son una técnica para visualizar arquitecturas empresariales, también presentan elementos arquitectónicos en forma de un "mapa" 2D fácil de entender. 
landscape Map Viewpoints en arquitecturas proporciona a los interesados no técnicos, como los gerentes, una visión general de alto nivel, sin sobrecargarlos con tecnicismos de dibujos arquitectónicos.
El uso y las técnicas de los landscape Map Viewpoints. Presenta un modelo formal para mapas de paisajes como base de las técnicas de visualización e interacción, también puede mostrar cómo se puede generar un mapa de paisaje a partir de su modelo subyacente y varias técnicas de interacción, 

Los puntos de vista de los landscape Map se utilizan, por ejemplo, para publicar una descripción general para los administradores y propietarios de procesos o sistemas, o los arquitectos los emplean como una herramienta conveniente para el análisis de cambios o para encontrar patrones en la asignación de recursos. landscape Map, como lo definen Van der Sanden y Sturm , es una matriz que representa un sistema de coordenadas tridimensional que representa las relaciones arquitectónicas. 

![landscape Map ](https://user-images.githubusercontent.com/28465837/83329251-0ac43100-a24e-11ea-883d-54d4f9eb4e39.png)

esta un ejemplo de un landscape Map que muestra qué sistemas de información respaldan las operaciones de una compañía de seguros. El eje vertical representa el negocio de la empresa.

funciones; El eje horizontal muestra sus productos de seguros. Un rectángulo de aplicación que cubre una o más celdas significa que este par particular de función / producto está respaldado por la aplicación, por ejemplo, la contratación de un seguro de asistencia legal está respaldada por el sistema de oficina de asistencia legal.

Las dimensiones landscape Map se pueden elegir libremente de la arquitectura que se está modelando. En la práctica, las dimensiones a menudo se eligen entre diferentes dominios arquitectónicos, por ejemplo, funciones comerciales, productos y aplicaciones, etc. En la mayoría de los casos, el eje vertical representa un comportamiento como procesos o funciones comerciales; el eje horizontal representa "casos" para los que se deben ejecutar esas funciones o procesos. Estos 'casos' pueden ser diferentes productos, servicios, segmentos de mercado o escenarios. La tercera dimensión representada por las celdas de la matriz se usa para asignar recursos como sistemas de información, infraestructura o recursos humanos. El valor de las celdas se puede visualizar mediante rectángulos de colores con etiquetas de texto.
 
 
# Analisis de LayeredViewpoint


Esta vista muestra varias capas y aspectos de una arquitectura empresarial en un diagrama. Hay dos categorías de capas, a saber, capas dedicadas y capas de servicio. Las capas son el resultado del uso de la relación de "agrupamiento" para una partición natural de todo el conjunto de objetos y relaciones que pertenecen a un modelo.


La tecnología, aplicación, proceso y actorLas capas / role pertenecen a la primera categoría. El principio estructural detrás de un punto de vista completamente en capas es que cada capa dedicada expone, por medio de la relación de "realización", una capa de servicios, que están más "sirviendo" a la siguiente capa dedicada. Por lo tanto, podemos separar fácilmente la estructura interna y la organización de una capa dedicada de su comportamiento externo observable expresado como la capa de servicio que realiza la capa dedicada.

![Uploading Nueva imagen de mapa de bits.jpg…]()
