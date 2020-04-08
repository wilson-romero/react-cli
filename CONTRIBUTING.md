# Introducción

### React CLI - La utilidad que React merece!

Antes que nada, gracias por considerar contribuir con React CLI. Son las personas como tu las que hacen que este proyecto sea una herramienta tan genial.  


### Contribuyendo a React CLI.

Tómese un momento para revisar este documento así el proceso de contribución sera fácil y efectivo para todos los involucrados. 

Seguir estas pautas ayuda a comunicar que respeta el tiempo de los desarrolladores que administran este proyecto de código abierto. A cambio, nosotros debemos corresponder ese respeto al abordar su issue, evaluar los cambios y ayudarlo a finalizar sus pull request.


### Buscamos contribuciones.  

React CLI es un proyecto de código abierto y a nosotros nos gustaría recibir contribuciones de nuestra comunidad - de tí! Hay muchas formas de contribuir, desde escribir tutoriales o publicaciones en blogs, mejorar la documentación, generar reportes de nuevos bugs y solicitudes de mejoras o escribir codigo que pueda ser incorporado en React CLI como tal.  


### Preguntas de soporte.

Por favor, no uses el panel de issues para [preguntas de soporte]. Si tu problema no es estrictamente específico de React CLI vale la pena intentar describiendo o buscando el error en Stack Overflow.


# Reglas de base

### Responsabilidades 

* Asegurate de la compatibilidad entre plataformas para cada cambio aceptado. Windows, Mac, Debian y Ubuntu Linux.
* Asegurate de que el código que va al core cumple con los requerimientos de la siguiente checklist: https://URL
* Crea issues para cualquier cambio mayor y mejora que desearias hacer. Discute las cosas de manera transparende y obten los comentarios de la comunidad.    
* Manten el versionamiento de nuevas caracteristicas tan cortas como sea posible.  
* Se amable con las y los recién llegados y apoya la diversidad de nuevas y nuevos contribuidores de todo tipo de antecedente. Revisa el [Código de Conducta](https://URL).


# Tu primera contribución

Aun no sabes como empezar a contribuir con React CLI? 
Puedes empezar revisando los issues con etiquetas principiante (beginner) y se-necesita-ayuda (help-wanted):

* Principiante (beginner) - los issues con esta etiqueta deberían de requerir unicamente unas pocas lineas de código y uno o dos tests.

* Se necesita ayuda (help-wanted) - Estos son issues que pueden ser un poco más complicados que los issues de principiantes.  

Ambas listas de issues están ordenadas por la cantidad de comentarios que tienen. Aunque no es perfecto, la cantidad de comentarios es un proxy rasonable para saber el impacto que tendrá el cambio.  


### Si nunca has contribuido anteriormente.  

Trabajando en tu primer Pull Request? Puedes aprender como en esta *free* series, [Cómo contribuir a un proyecto de Código abierto en GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

En este punto, ya estas preparada o preparado para hacer cambios! Sientete libre de pedir ayuda; todos fuimos principiantes una vez :smile_cat:

Si un maintainer te pide que hagas un "rebase" al PR, ellos se refieren a que muchisimo código a cambiado y que deberías actualizar la rama para que sea más facil unirla al resto del código.

# Empezando

Para cualquier cosa que sea mayor a una o dos lineas para corregir:  

1. Crea tu propio fork del código
2. Haz los cambios en tu fork
3. Si te gusta el cambio y crees que el proyecto podría utilizarlo:
    * Crea un issue con la problematica a resolver
    * Asegurate de haber seguido el estilo de código del proyecto.  
    * Envia un pull request indicando el issue
    

### Si tienes un proceso diferente para correcciones pequeñas u "obvias", hazlo saber.  

Pequeñas contribuciones como errores de ortografía, donde el contenido es lo suficientemente pequeño como para no considerado propiedad intelectual, puede ser agregado como un patch de contribuidor.  

Como regla de oro, los cambios pueden ser considerados "correcciones obvias" si estos no introducen una nueva funcionalidad o pensamiento creativo. Media vez el cambio no afecte la funcionalidad, algunos ejemplos incluyen los siguientes:  

* Correcciones de Ortografía / Gramática  
* Corrección de un error en la escritura de una palabra, espacios en blanco y cambios de formato  
* Limpieza de comentarios
* Corrección de Bugs que cambian los valores que se retornan o códigos de error guardados en constantes 
* Agregar mensajes de logueo o salidas de debugging
* Cambios a los archivos de ‘metadata’ como Gemfile, .gitignore, scripts de construcción, etc.
* Mover archivos con código de un directorio o paquete a otro  


# Cómo reportar un bug

Si encuentras una vulnerabilidad de seguridad, NO abras un issue con la explicación. En vez de eso, envía un email a seguridad@xxxxx.

Para poder determinar si estas tratando con un error de seguridad, hazte las siguientes preguntas:  

* Puedo accesar a algo que no es mío, o algo que no debería de tener acceso?  
* Puedo deshabilitar algo para otras personas?

Si la respuesta a cualquiera de esas dos preguntas es "Si", entonces probablemente estas lideando con un problema de seguridad. Nota que aún cuando la respuesta es "no" a ambas preguntas, aún podrías estar lideando con un issue de seguridad, si no estas seguro, envianos un email a security@xxxxx.


### Como crear un reporte de bug.

Cuando llenas un issue, asegurate de responder estas cinco preguntas:

1. Qué version de React CLI estas usando(react-cli --version)?
2. Qué sistema operativo y que procesador estas usando?
3. Qué hiciste?
4. Qué esperabas ver?
5. Qué viste en lugar de ello?


# Cómo sugerir una nueva característica
### Si tienes un plan en particular, metas, o filosofía de desarrollo, compartela aquí.
Esta información le dara a los contribuidores contexto antes de hacer sugerencias que puede no estén alineadas con lo que el proyecto necesita.

> La filosofía Express se trata de proveer un pequeño pero robusto set de herramientas para servidores HTTP, haciendolo una gran solución para aplicaciones de una sola página, web sites, híbridos, APIs HTTP publicas.
>
> Express no te forza a utilizar ningún ORM específico. Con soporte para al rededor de 14 motores de plantillas vía Consolidate.js, puedes facilmente crear un framework perfecto.

[fuente: [Express](https://github.com/expressjs/express#philosophy)] **Necesitas más inspiración?** [Active Admin](https://github.com/activeadmin/activeadmin#goals)

### Explica tu proceso deseado para sugerir una nueva característica.
Si hay una ida y vuelta o cierre de sesion requerido, dilo. Pideles que escriban el alcance de la nueva caracteristica, con la idea de porque es necesaria y como podría funcionar.

> Si te encuentras desdeando una característica que no existe en Elasticsearch, probablemente no estas solo. Puede ser que otras personas tengan necesidades similares. Muchas de las características que Elasticsearch tiene el día de hoy han sido agregadas gracias a que nuestros usuarios vieron la necesidad. Abre un issue en la lista de issues de GitHub que describa la característica que te gustaría ver, porqué la necesitas y como debería funcionar.

[fuente: [Elasticsearch](https://github.com/elastic/elasticsearch/blob/master/CONTRIBUTING.md#feature-requests)] **Necesitas más inspiración?** [1] [Hoodie](https://github.com/hoodiehq/hoodie/blob/master/CONTRIBUTING.md#feature-requests) [2] [Ember.js](https://github.com/emberjs/ember.js/blob/master/CONTRIBUTING.md#requesting-a-feature)

# Revisión del código

El core team revisa los Pull Requests y luego de que se da la retroalimentación se esperan respuestas en las siguientes semanas. Luego de ello puede que se cierre el pull request debido a la inactividad.
