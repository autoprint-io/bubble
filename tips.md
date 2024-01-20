## Tabla de Contenido

1. [Introducción][## Introducción]
2. [Optimizaciones Generales de la Aplicación](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#optimizaciones-generales-de-la-aplicaci%C3%B3n)
3. [Optimización de Búsquedas y Velocidad](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#optimizaci%C3%B3n-de-b%C3%BAsquedas-y-velocidad)
4. [Trucos de Diseño](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#trucos-de-dise%C3%B1o)
5. [Flujos de Trabajo en el Backend](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#flujos-de-trabajo-en-el-backend)
6. [Organizar tu Aplicación para Escalar](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#organizar-tu-aplicaci%C3%B3n-para-escalar)
7. [Mis Plugins Favoritos](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#mis-plugins-favoritos)
8. [Mis APIs Favoritas](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#mis-apis-favoritas)
9. [Consejos Variados](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#consejos-variados)
10. [Recursos Adicionales](https://chat.openai.com/c/5648716d-7e1c-4d51-82db-bed3d83792cc#recursos-adicionales)

## Introducción


**Consejos de JJ para Convertirse en un Desarrollador Profesional de Bubble**

La optimización de WU no es todo. Es importante encontrar un equilibrio entre el costo, el rendimiento y la seguridad al realizar tus optimizaciones.

**Más información sobre este archivo de deslizamiento**

Esta es una colección de consejos, trucos, hacks y consejos generales que he recopilado mientras aprendía Bubble junto con miembros increíbles de la comunidad.

## Optimizaciones Generales de la Aplicación


Cosas que deberías incluir en todas tus aplicaciones:


1. **Búsqueda en la Vista de Base de Datos**: Limitar tu BD utilizando la opción de vistas. Cosas como 'campo está vacío' o 'campo contiene' son ideales para obtener resultados rápidos.
2. **Flujos de Trabajo**: Colocar un correo electrónico interno dentro de los pasos para obtener información adicional sobre ese proceso. La misma idea se aplica a procesos importantes como el registro de usuarios o la realización de una compra.
3. **Uso de JavaScript en un RG (Grupo Repetidor)**: Utilizar el fragmento de código `window.open("dynamicdata")` para abrir una nueva pestaña dentro de un RG. Requiere el complemento de caja de herramientas para ejecutar JavaScript de esta manera.
4. **Eventos Personalizados**: Convertir flujos de trabajo del lado del cliente que uses más de una vez en eventos personalizados.
5. **Manejo de Datos en el Lado del Servidor**: Especificar el tipo de datos y el campo de datos que deseas que tu aplicación espere y una vez que eso suceda, se activará el evento personalizado que has configurado en el frente.
6. **Optimización de Flujos de Trabajo**: Siempre que crees dos flujos de trabajo (que sean iguales, por ejemplo, el flujo de trabajo de registro de usuario) o más en la misma página, utiliza un evento personalizado. Luego, haz que cada acción (clic) active el evento personalizado para desencadenar.
7. **Orden de Ejecución de Flujos de Trabajo**: Utilizar un evento personalizado para forzar que tus flujos de trabajo se ejecuten en orden.
8. **Agregar una Pausa en Flujos de Trabajo**: Agregar una pausa a tus flujos de trabajo en el lado del cliente no pausará todas las acciones del flujo de trabajo (solo se aplican a las interacciones del lado del cliente).
9. **Eliminación de un Tipo de Datos/Conjunto de Opciones**: Cuando elimines un tipo de datos, a veces encontrarás elementos eliminados dentro de tus expresiones que no están causando advertencias de error, pero están rompiendo tus expresiones. Para exponer estos elementos, intenta restaurar tu aplicación (hasta unos segundos antes).
10. **Control de Versiones**: Intenta mantener tus ramas de desarrollo siempre listas para una corrección urgente o una implementación.
11. **Puntos de Guardado**: Antes de comenzar a trabajar en una nueva función, crea un punto de guardado.
12. **Enlaces Profundos**: Usa parámetros de URL para tus indicadores visuales (mostrar/ocultar grupos, etc.).
13. **Formateado como Texto**: Utiliza formateado como texto para establecer diferentes valores, uno para cuando la expresión sea sí y otro para cuando sea no.
14. **El Texto Arbitrario es tu Amigo**: Utiliza "Texto arbitrario: convertido a número" para forzar operaciones matemáticas en un cierto orden.
15. **Conjuntos de Opciones**: Los conjuntos de opciones se cargan automáticamente cuando se carga la página. No coloques información sensible en los conjuntos de opciones, ya que son accesibles públicamente.
16. **Cómo Cargar Conjuntos de Opciones**: Por defecto, los conjuntos de opciones no se pueden cargar utilizando el cargador CSV. Pero si descargas la extensión de Chrome llamada "Bubble Option Sets Helper", podrás hacerlo.
17. **Conteo**: Ejecutar expresiones de "conteo" no carga todos los datos que están asociados con las "cosas" que estás contando.
18. **Reciclar tus Búsquedas**: Con la adición de las Unidades Web (WU), trata de reutilizar tus búsquedas tanto como sea posible para ahorrar en los costos de WU.
19. **Encontrar Áreas para Optimizar**: Descubrir áreas para optimizar es mucho más fácil con las nuevas herramientas de WU que Bubble lanzó recientemente.

**Próximamente: Optimización de Búsquedas y Velocidad.**

## Optimización de Búsquedas y Velocidad


Es hora de acelerar.


1. **Creación de Tipos de Datos**: Crea más tipos de datos en lugar de agregar más campos a un tipo de datos.
2. **Límites en Campos de Lista**: Mantener tus listas por debajo de 100 elementos. Si imaginas un futuro en el que tus listas puedan superar los 100 elementos en cada una y definitivamente los 1,000 elementos, entonces deberías convertir esa lista en su propio tipo de datos.
3. **Uso de Tipos de Datos Satélite**: Para tipos de datos más pesados, trata de usar un tipo de datos satélite. Tu tipo de datos satélite debe incluir los elementos que necesitan cargarse al cargar la página y nada más.
4. **Manejo de Elementos Visibles al Cargar la Página**: Cuando algo necesita estar visible al cargar la página pero contiene condiciones para mostrar u ocultar basadas en condiciones, trata de usar "elemento es visible al cargar la página".
5. **Procesamiento de Declaraciones Condicionales**: Las declaraciones condicionales se procesan de arriba a abajo.
6. **Mantener el Tipo de Datos de Usuario Ligero**: Siempre trata de mantener tu tipo de datos de usuario lo más liviano posible.
7. **Optimización de Búsquedas**: Trata de limitar tus búsquedas tanto como sea posible.
8. **Búsqueda y Filtrado entre Diferentes Tipos de Datos**: Si necesitas buscar y filtrar entre dos tipos de datos diferentes, pero el tipo de datos A no tiene una relación con el tipo de datos B, puedes buscar por el tipo de datos A. Luego cargas tu búsqueda para el tipo de datos B en un popup que tiene un "RG oculto" en él.
9. **Uso de Llamadas del Lado del Cliente**: Siempre usa llamadas del lado del cliente como la primera expresión en tu condicional cuando también estés utilizando llamadas del lado del servidor.
10. **Cadena de Flujos de Trabajo**: Dentro de una cadena de flujos de trabajo, en lugar de colocar una condición en cada paso dentro del flujo de trabajo, coloca la condición al principio del flujo de trabajo.
11. **Mostrar u Ocultar un Grupo que Contiene un Grupo Repetidor**: Cuando necesites mostrar u ocultar un grupo que contiene un grupo repetidor dentro de él, establece el grupo como "no visible al cargar la página" y colapsa ese grupo.
12. **Carga de Página vs. Hacer Cuando para Cargar Datos**: Al decidir entre "carga de página" o "hacer cuando" para cargar datos, opta por "hacer cuando la condición" y configúrala para que se ejecute cada vez.
13. **Operaciones de :Filtrado**: Las operaciones de :filtrado ocurren en el lado del servidor, excepto para el filtro avanzado que ocurre en el lado del cliente.

**Próximamente: Trucos de Diseño.**

## Trucos de Diseño


Demuestra tus habilidades construyendo aplicaciones hermosas.


1. **Preparación de Estilos y Colores**: Al comenzar una nueva aplicación, prepara tus estilos, colores de la aplicación y otros valores predeterminados. Si necesitas ayuda para elegir colores complementarios para tu marca, visita [coolors.co](https://coolors.co/).
2. **Dimensiones de Página**: Comenzar con una de las siguientes dimensiones de página: 1280, 1440, 960.
3. **Uso de Columnas**: La mayoría de las páginas deberían ser columnas al principio.
4. **Acceso a la Propiedad Centrada en la Altura Vertical**: Cuando necesites acceder a la propiedad centrada en la altura vertical, convierte la alineación de tu contenedor en una fila en lugar de una columna cuando sea posible.
5. **Uso de Espaciado de Relleno**: En la mayoría de los casos, es mejor utilizar espaciado de relleno en lugar de espaciado de margen.
6. **Diseño para Dispositivos Móviles**: Al diseñar para dispositivos móviles, establece un ancho mínimo de 320 píxeles para tus elementos de contenedor.
7. **Reformateo a un Diseño Móvil**: Cuando tengas dificultades para reformatear tu diseño a un diseño móvil, busca ocultar/mostrar elementos según la propiedad "ancho de página actual" en tu pestaña de condicionales.
8. **Uso de Márgenes Negativos**: Los márgenes negativos en elementos que requieren superposición funcionan sorprendentemente bien.
9. **Configuración de Contenedores**: Al configurar tus contenedores, trata de aprovechar al máximo el "espaciado de espacio".
10. **Formateo de Imágenes Grandes de Manera Dinámica**: Al formatear imágenes grandes de manera dinámica, puedes utilizar el procesamiento con Imgix.
11. **Configuración de Calidad de Imágenes**: Siempre configura la calidad al 100% junto con el cambio de tamaño para ajustar las dimensiones de la imagen.
12. **Imágenes de Perfil**: Para imágenes más pequeñas, como imágenes de perfil, combina estas configuraciones con la representación en el modo de ejecución "estirar".
13. **Imágenes de Portada o Fondos**: Para imágenes más grandes, como imágenes de portada o fondos, utiliza la representación en el modo de ejecución "zoom".
14. **Uso de Imágenes Estáticas**: Cuando utilices imágenes estáticas, introduce la relación de aspecto de la imagen original que estás cargando.
15. **Uso de Grupos**: Trata de utilizar la menor cantidad de grupos posible.
16. **Elementos con Altura Completa**: Cuando desees que un elemento tenga una altura completa, puedes utilizar la altura mínima del 100%.
17. **Alineación de Imágenes/Iconos**: Cuando necesites mantener una imagen/icono en un lugar muy específico, utiliza la alineación del contenedor "alinear al padre".
18. **Uso de Elementos Arrastrables**: Al utilizar elementos arrastrables, haz que tus áreas de soltar sean lo más grandes posible.
19. **Boceto de Páginas**: Para hacer un boceto de tus páginas, comienza con el color #111111 y añade una opacidad del 10%.

**Siguiente tema: Flujos de Trabajo en el Backend**

## Flujos de Trabajo en el Backend


Potencia tus flujos de trabajo en el backend con estas estrategias.


1. **Flujos de Trabajo que Cambian Datos**: Siempre que tenga un flujo de trabajo que cambia datos en 2 pasos o más, conviértelo en un flujo de trabajo en el backend.
2. **Creación de Flujos de Trabajo de API**: Siempre que tenga que crear la misma serie de flujos de trabajo, crea un flujo de trabajo de API.
3. **Uso de Flujos de Trabajo en el Backend**: En general, intenta crear un flujo de trabajo en el backend siempre que sea posible.
4. **Desencadenadores de Base de Datos**: Los desencadenadores de base de datos son especialmente útiles para gestionar tus relaciones en curso.
5. **Sistema de Registro para Flujos de Trabajo Largos y Complejos**: Cuando creas flujos de trabajo largos y complejos, es útil crear un sistema de registro que proporcione puntos de control y estados en tiempo real. Para ello, puedes crear un nuevo tipo de dato y llenarlo con todos los campos/información que deseas supervisar. 6. **Creación Masiva de Datos**: Cuando necesites crear una gran cantidad de datos de una sola vez, expón la API de tu propia aplicación y llama a la API de tu aplicación utilizando el punto final de Creación Masiva.
7. **Actualización de un Tipo de Dato**: Cuando necesites actualizar un tipo de dato, crea un flujo de trabajo de API que utilice un tipo de dato principal.
8. **Copiar la Base de Datos en Vivo en la Base de Datos de Desarrollo**: Ampliando la idea del punto #5, si necesitas actualizar una gran cantidad de datos, puede ser mejor copiar tu base de datos en vivo en tu base de datos de desarrollo.
9. **Operaciones Masivas**: Las operaciones masivas funcionan mejor en listas de 5,000 o menos.

*Actualizado el 4/13/22: Una vez que estés en un entorno dedicado, comenzará a afectar tu capacidad del servidor (pero no en entornos compartidos en este momento).*


10. **Consideraciones sobre Llamadas a la API**: En algunas situaciones, crearé el elemento en el frontend, pasaré los resultados a mi componente de navegación y luego completaré la creación de las relaciones restantes en el backend mediante un flujo de trabajo de API.
11. **Obtén una Respuesta de tu Propio Flujo de Trabajo**: ¿Alguna vez has deseado poder obtener directamente la respuesta de uno de tus propios flujos de trabajo en el backend?
12. **Flujos de Trabajo de Actualización y Creación**: ¿Tienes un flujo de trabajo que maneja tanto la creación como la actualización (si el elemento ya existe) de algún registro?

**Siguiente tema: Organiza tu Aplicación para Escalar**

## Organizar tu Aplicación para Escalar


La organización es fundamental, especialmente cuando varios desarrolladores de Bubble comienzan a trabajar juntos.


1. **Numeración de tus Flujos de Trabajo**: Numero todos mis flujos de trabajo: el primer número es el flujo de trabajo principal (por ejemplo, 10), y si hay otros flujos de trabajo que dependen de ese primer flujo de trabajo, etiqueto los flujos de trabajo secundarios como 10-1, 10-2 (etc).
2. **Carpetas de Flujos de Trabajo**: Similar a lo anterior, agrupo todos mis flujos de trabajo principales y secundarios en una carpeta.
3. **Colorea tus Flujos de Trabajo, Parte 1**: Estos son los colores que hemos intentado usar en el pasado, pero honestamente, se volvió demasiado difícil de administrar y no funcionó tan bien como se pretendía:
	- Rojo = Programado para eliminación cuidadosa
	- Verde = Completado
	- Morado = Relacionado con errores
	- Naranja = En desarrollo
	- Azul = Listo para pruebas
	- Marrón = Programado para actualización
	- Cian = Necesita ser revisado
4. **Colores, Parte 2**: Para páginas/aplicaciones que están completas, cambiamos a este esquema de colores:
	- Rojo = Eliminando elementos
	- Verde = Creando elementos
	- Morado = Navegación
	- Naranja = Eventos personalizados
	- Azul = Configuración de estados personalizados/Administración de la interfaz de usuario (restableciendo grupos, etc.)

*Estos colores nos permiten ver fácilmente el significado de cada flujo de trabajo y estado del flujo de trabajo desde lejos.*


5. **Notas Internas**: Cuando creamos flujos de trabajo detallados, nos gusta agregar notas internas a cada uno de ellos que brinden una descripción general de lo que hace el flujo de trabajo. Usamos un emoji de cuaderno para indicar que ese flujo de trabajo tiene una nota interna adjunta. Para obtener puntos adicionales, incluye un enlace de Loom dentro de la sección de notas para proporcionarte a ti mismo/a tu equipo una descripción más completa de los flujos de trabajo realmente complicados.
6. **Nombrar tus Elementos**: Esto no es algo que haya dominado aún, ni mi equipo. Lo importante es que encuentres un sistema que funcione para ti. Siempre mantengo el tipo de elemento dentro del nombre (por ejemplo, Grupo Contenedor Interno / Nombre del Atributo de Entrada). También puede ser útil incluir la posición de esos contenedores dentro del nombre (por ejemplo, Grupo Contenedor Lado Izquierdo).
7. **Subaplicaciones**: Si estás buscando una solución de marca blanca más personalizable, puedes probar las subaplicaciones de Bubble. Te permiten crear una duplicación de tu aplicación, que luego se convierte en una subaplicación.

**Siguiente tema: "Mis Plugins Favoritos"**

## Mis Plugins Favoritos


A veces, los plugins son la única manera de avanzar. Aquí están mis favoritos.


1. **VideoJS Advanced**: El plugin de reproductor de video más potente que incluye muchas APIs completamente integradas en él, incluida mi API favorita, MUX.
2. **Canvas JS**: El plugin más potente para agregar formas, texto y elementos a un lienzo para aplicaciones como Canva y otras características que requieren algún tipo de anotaciones.
3. **Generador de Contenido Dinámico**: La herramienta definitiva de búsqueda y reemplazo útil para permitir que tus usuarios utilicen "etiquetas de combinación" en su contenido, que luego puedes ejecutar para convertir todas esas etiquetas en contenido dinámico personalizado.
4. **Tiempo Relativo**: Uso este plugin todo el tiempo. ¡Es genial para mostrar marcas de tiempo como "30 minutos después" y muy fácil de usar!
5. **Imágenes de Perfil Alfabéticas**: Me encanta usar este plugin para los nuevos usuarios que aún no han subido una foto de perfil.
6. **Input Watcher**: ¡El plugin Input Watcher de Eli Beachy! Es la forma más rápida de crear menús desplegables con búsquedas y de rellenar otros campos de entrada.
7. **Herramientas de CSS**: Te permite encontrar la altura de un elemento específico, entre otras funciones que te brindan un mayor control sobre tu aplicación.

**Siguiente tema: Mis APIs Favoritas**

## Mis APIs Favoritas


Potencia tu aplicación hasta la luna y más allá con estas APIs.

**: La API definitiva para cuando estás haciendo cualquier cosa con videos para tu aplicación**. Mux me permite hacer esto de manera escalable y económica. [Más información en mux.com](https://mux.com/)


- **LOB**: Esta API es fantástica para aquellos que buscan verificar direcciones dentro de su aplicación para asegurarse de que el correo estándar pueda ser entregado. Además, proporciona un servicio que te permite enviar correo/tarjetas postales a esas direcciones en tu nombre. [Más información en lob.com](https://www.lob.com/)
- **CloudConvert**: Ingresa todo tipo de archivos multimedia, transfórmalos a diferentes formatos de medios y obtén los resultados de vuelta (piensa en .mp4 a .gif). [Más información en cloudconvert.com](https://chat.openai.com/c/www.cloudconvert.com)

**Siguiente tema: Consejos Variados**

## Consejos Variados


Consejos aleatorios que te ayudarán en toda tu aplicación.


1. **Acceder a Datos Dentro de un RG**: Cuando necesitas acceder al contenido dentro de un grupo repetitivo, hay dos formas principales: Agregar un elemento reutilizable dentro de la celda actual de ese grupo repetitivo y luego agregar tus "menús desplegables, grupos de enfoque y otros elementos de acción que deseas realizar dentro de esa celda actual dentro de tu elemento redimensionable. También puedes usar el plugin llamado Musicians para acceder a datos dentro del RG que luego puedes usar con otras acciones/flujos de trabajo en esa página.
2. **Clasificación Condicional**: Las condiciones van de arriba a abajo en orden de importancia. La condición inferior es la más importante y anulará otras condiciones si están presentes en múltiples ocasiones (aunque siempre debes tratar de evitar tener múltiples condiciones).
3. **Reutilizar tus Datos**: Trata de reutilizar la información en tus llamadas que ya ha sido cargada, en lugar de hacer una nueva llamada a la base de datos.
4. **El Primer Elemento Está Vacío**: En lugar de usar un "conteo es 0", utiliza un "el primer elemento está vacío".
5. **Usuarios Fantasma**: Mientras las cookies estén habilitadas en tu aplicación web, Bubble guardará automáticamente la información del "usuario actual" durante 72 horas.
6. **Texto Arbitrario**: Si apilas varias expresiones juntas, considera usar "texto arbitrario" como el primer operador en tu expresión.

**Siguiente tema: Recursos Adicionales**

## Recursos Adicionales


Recursos adicionales para que estudies y te informes más.


- **La Guía Definitiva de Bubble**: [Aprende Más](https://bubble.io/)
- **La Guía Definitiva de Seguridad de Bubble**: Aprende Más
- **Domina el Editor Responsivo con Flexcamp**: [Aprende Más](https://flexcamp.com/)
- **Atomic Fusion para la Mejor Forma de Reutilizar tus Elementos de Interfaz de Usuario y Crear Diseños Limpios y Rápidos**: [Atomic Fusion](https://atomicfusion.com/)
- **Extensión para Desarrolladores de Bubble para Ayudarte a Construir y Diseñar Aplicaciones Más Rápido**: [chrome.google.com](https://chrome.google.com/)

**Enlaces y Recursos Adicionales**:


1. Generador de paletas de colores: [coolors.co](https://coolors.co/)
2. Optimización de tus imágenes: [tinypng.com](https://tinypng.com/)
3. Generador de texto falso: [loremipsum.io/generator/](https://loremipsum.io/generator/)
4. Clips de video, música y efectos de sonido de stock: [pexels.com](https://www.pexels.com/)
5. Fotos y videos de stock: [icons8.com/creator](https://icons8.com/creator)
6. Fotos de stock con un impresionante creador de fotos: [unscreen.com](https://www.unscreen.com/)
7. Eliminación de fondos de video: [remove.bg](https://www.remove.bg/)
8. Eliminación de fondos de fotos: [generated.photos/faces](https://generated.photos/faces)
9. Generador de imágenes de usuario y fotos de perfil: [unsplash.com](https://unsplash.com/)
10. Ilustraciones de fotos de stock: [openpeeps.com](https://www.openpeeps.com/)
11. Ilustraciones dibujadas a mano: [usesmash.com](https://usesmash.com/)
12. Personajes de moda: [opendoodles.com](https://opendoodles.com/)
13. Ilustraciones esbozadas: [control.rocks](https://control.rocks/)
14. Personajes personalizables: [icons8.com/illustrations](https://icons8.com/illustrations)
15. Personajes e ilustraciones vectoriales: [getavataaars.com](https://getavataaars.com/)
16. Generador de avatares de personajes: [worldvectorlogo.com](https://worldvectorlogo.com/)
17. Biblioteca de logotipos vectoriales y paletas de colores: [colormixer.web.app](https://colormixer.web.app/)
18. Mezclador de colores: [colorsinspo.com](https://colorsinspo.com/)
19. Hermosas paletas de colores: [mycolor.space](https://mycolor.space/)
20. Generador de colores: [palettte.app](https://palettte.app/)
21. Generador de paletas de colores: [colorable.jxnblk.com](https://colorable.jxnblk.com/)
22. Elementos de marcador de posición: [via.placeholder.com](https://via.placeholder.com/)
23. Degradados de malla: [meshgradient.in](https://meshgradient.in/)
24. Iconos: [iconer.app](https://iconer.app/)
25. Cargadores: [uiball.com/loaders/](https://uiball.com/loaders/)

