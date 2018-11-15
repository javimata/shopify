# shopify
Personalización de theme


## page-faqs.liquid
El tema utilizado tenia una section de Faqs muy limitada, debías poner 10 preguntas, no podías poner más y si ponías menos de todos modos se mostraban los 10 cuadros, con esta modificación las faqs son ilimitadas, manejadas como blocks, además de que se puede poner un titulo de Sección para poder separar las preguntas por Temas, además de ponerlas en accordion, ej:

### General
- Pregunta 1  
  - Respuesta 1  
- Pregunta 2   
  - Respuesta 2  

### Envíos
- Pregunta 3    
  - Respuesta 3  
- Pregunta 4  
  - Respuesta 4  

## Como se usa
- Respaldamos el archivo actual de las Faqs, comunmente llamado page-faqs.liquid dentro de sections, dependiendo del tema puede ser diferente.  
- Crear un nuevo archivo o sobreescribir el actual (ya respaldado) con el código de mi archivo page-faqs.liquid.  
- Dentro de editor del Tema nos dirigimos a la página de **Preguntas frecuentes** y nos deberia aparecer la sección del lado derecho llamada **FAQs**.  
- Al entrar en la section de **FAQs** tenemos la sección de Configuración con un check que permite que todas las preguntas se muestren abiertas, recuerda que se muestran en un accordion, si deseamos que solo una pregunta (o ninguna) salga abierta debemos dejar este Check como desactivado, esto hara que se carguen todas las respuestas como cerradas.  
- En la sección de CONTENT veremos el botón **Add Content**, si damos click en el tendremos 2 opciones: **Section separator** y **Faqs**.  
  - **Section separatod** Es un separador de bloques de preguntas y solo requiere que le indiquemos el nombre del bloque dentro del campo **Heading**  
  - **Faqs** Es el contenido de la pregunta frecuente, en el tenemos las siguientes opciones:
    - **Question** que será la pregunta
    - **Answer** es un richtext para la respuesta  
    - **Abrir al cargar** Permite seleccionar manualmente si queremos que esta pregunta cargue abierta
  
Y Listo, con esto configuramos nuestras Preguntas frecuentes.  
  
