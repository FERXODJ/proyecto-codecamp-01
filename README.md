# proyecto-codecamp-01

# Elementos de Marcado:

1) H1: Se utiliza para definir el título más importante de su contenido, normalmente el título principal de la página o una sección principal.
 
 * Consejo: Coloque los títulos de menor importancia debajo de los de mayor importancia.

2) H2: Se utiliza para definir un encabezado de segundo nivel en su contenido, generalmente se usa para títulos de subsecciones o encabezados que son un poco menos importantes que el título principal (h1).

3) P: Se utiliza para definir párrafos en HTML, lo que le permite estructurar y separar el contenido del texto en párrafos distintos en una página web.

4) <!-- Coment -->: Permiten dejar mensajes sin afectar a la visualización del navegador. También le permite hacer que el código sea inactivo.

5) Main: Se utiliza para representar el contenido principal del cuerpo de un documento HTML. El contenido dentro del elemento main debe ser único para el documento y no debe repetirse en otras partes del documento.

* Consejo: Lo que este en el main se denomina anidamiento. Los elementos anidados deben colocarse dos espacios más a la derecha del elemento en el que están anidados.

6) Img: Es utilizado para agregar imagenes en nuestra pagina web, tienen una etiqueta de apertura sin etiqueta de cierre. Una etiqueta para un elemento sin etiqueta de cierre se conoce como etiqueta de autocierre.

7) Src= "URl": Se usa comúnmente en HTML para especificar la fuente (URL) de recursos externos, como imágenes, audio, video, iframes y scripts. Este atributo ayuda a los navegadores a localizar y mostrar el contenido externo correctamente en una página web. 

NOTA: Los atributos HTML son palabras especiales que se utilizan dentro de la etiqueta de apertura de un elemento para controlar su comportamiento.

8) Alt= "Text": El texto del atributo alt se utiliza para que los lectores de pantalla mejoren la accesibilidad y se muestra si la imagen no se carga.

* Consejo: Todos los elementos img deben tener un atributo alt.

9) Anchor (a): Se utiliza para crear hipervínculos en HTML, lo que le permite vincular a otras páginas web, archivos, direcciones de correo electrónico o partes específicas de la misma página. Es un elemento fundamental para la navegación y la conexión de contenidos a través de la web.

10) Href= "URL": Se usa comúnmente con la etiqueta "a" (ancla) en HTML para especificar la URL de destino o la ubicación a la que debe apuntar un hipervínculo. Este atributo es crucial para definir hacia dónde debe navegar el usuario cuando hace clic en el enlace.

NOTA: El texto de un enlace debe colocarse entre las etiquetas de apertura y cierre de un elemento de anclaje (a).

11) Target: Se utiliza a menudo junto con la etiqueta "a" (ancla) para especificar dónde se debe abrir el contenido vinculado al hacer clic. Le permite controlar si el contenido vinculado se abre en la misma pestaña, en una nueva pestaña o en un marco específico.

NOTA: Cuando establece el atributo destino en "_blank" en un atributo target le indica al navegador que abra el documento vinculado en una nueva pestaña o ventana sin nombre. 

NOTA: Otros tipos de contenido también pueden convertirse en un enlace envolviéndolo en etiquetas de anclaje.

12) Section: Se utiliza para definir secciones en un documento, como capítulos, encabezados, pies de página o cualquier otra sección del documento. Es un elemento semántico que ayuda con el SEO y la accesibilidad.

* Consejo: Antes de añadir cualquier contenido nuevo, debe utilizar un elemento de sección para separar el contenido de las fotos de gatos del contenido futuro.

13) H3: Se utiliza para definir un encabezado de tercer nivel en su jerarquía de contenido, que generalmente indica títulos de subsecciones o encabezados que son menos destacados que los encabezados "h1" y "h2". Ayuda a estructurar y organizar el contenido de una página web.

14) Ul: Se utiliza para crear una lista desordenada en HTML, que normalmente representa una lista de elementos sin ningún orden numérico o secuencial. Cada elemento de una lista desordenada está marcado con una viñeta de forma predeterminada.

15) Li: Se utiliza para definir elementos de lista dentro de listas ordenadas (ol) o desordenadas (ul) en HTML. Ayuda a estructurar y organizar el contenido en un formato de lista, ya sea numerada o con viñetas. 

16) Figure: Se utiliza para encapsular contenido multimedia, como imágenes, vídeos, ilustraciones, diagramas o fragmentos de código, junto con sus títulos relacionados (normalmente insertados con la etiqueta "figcaption").

17) Figcaption: Se utiliza para añadir una leyenda que describa la imagen contenida en el elemento de figura.

18) Em: Se Utiliza para enfatizar una palabra o frase concreta.

19) Ol: Es similar al de una lista desordenada, pero los elementos de una lista ordenada se numeran cuando se muestran.

20) Strong: Se utiliza para indicar que un texto es de gran importancia o urgente.

21) Form: Se utiliza para crear un formulario interactivo en una página web, lo que permite a los usuarios ingresar datos que pueden enviarse a un servidor para su procesamiento. Sirve como contenedor para elementos de formulario como campos de entrada, botones, casillas de verificación y más.

22) Action= "URL": Se utiliza dentro de la etiqueta "formulario" para especificar la URL donde se deben enviar los datos del formulario para su procesamiento cuando se envía el formulario. Determina el script del lado del servidor o el punto final que manejará los datos del formulario.

23) El elemento input permite varias formas de recoger datos de un formulario web. Al igual que los elementos img, los elementos input se cierran solos y no necesitan etiquetas de cierre.

24) Type: Se utiliza en varios elementos HTML para especificar el tipo de contenido o entrada esperada. Por ejemplo, en elementos de formulario como entrada, define el tipo de datos que se pueden ingresar (p. ej., texto, correo electrónico, contraseña).

25) Name: Se usa comúnmente en elementos de formulario como entrada, selección y área de texto para identificar los datos que se envían al servidor cuando se envía el formulario. Proporciona un par clave-valor para los datos del formulario, lo que permite a los servidores procesar e identificar los campos de entrada correctamente.

26) Placeholder: Se utiliza en elementos de formulario como entrada y área de texto para mostrar una breve sugerencia o texto de ejemplo dentro del campo de entrada. Este texto desaparece tan pronto como el usuario comienza a escribir, lo que proporciona orientación sobre el formato o contenido esperado de la entrada.

27) Required: Se utiliza en elementos de formulario como entrada, selección y área de texto para especificar que un usuario debe completar ese campo en particular antes de enviar el formulario. Ayuda a garantizar que se proporcione información esencial, agregando una capa de validación para formar entradas. 

28) Button:  Se utiliza para crear un botón en el que se puede hacer clic.

29) Label: Se utiliza para asociar una etiqueta de texto con un elemento de formulario, como un campo de entrada. Esta asociación mejora la accesibilidad y la experiencia del usuario al dejar claro para qué sirve cada campo del formulario.

30) Id: Se utiliza para identificar de forma única un elemento dentro de un documento HTML. Es crucial para varios propósitos, como vincular a un elemento específico con anclajes, asociar etiquetas con elementos de formulario usando el atributo "para" en las etiquetas y apuntar a elementos para diseñar o crear secuencias de comandos con CSS y JavaScript.

31) Value: Se usa comúnmente en elementos de formulario como entrada para definir el valor inicial o predeterminado del campo de entrada. Especifica los datos que se enviarán al servidor cuando se envíe el formulario. Este atributo es particularmente útil para completar previamente campos de formulario con valores predeterminados o ingresados ​​previamente. 

32) Fieldset: Se utiliza para agrupar elementos de formulario relacionados dentro de un formulario web. Ayuda a estructurar formularios al agrupar visualmente entradas relacionadas y, a menudo, va acompañado de la etiqueta "leyenda" para proporcionar un título o descripción de los elementos agrupados. Esta etiqueta ayuda a organizar y presentar formularios complejos de una manera más estructurada y accesible.

33) Legend: Actúa como título para el contenido del elemento fieldset. Ofrece a los usuarios contexto sobre lo que deben introducir en esa parte del formulario.

34) Label For: Se utiliza para asociar explícitamente la etiqueta con un elemento de formulario haciendo coincidir la "id" del elemento de formulario. Esta asociación mejora la accesibilidad y la experiencia del usuario al permitirles hacer clic en la etiqueta para centrarse o seleccionar el elemento de formulario asociado. Es particularmente útil para mejorar la usabilidad, especialmente para los usuarios que navegan por el formulario utilizando tecnologías de asistencia.

35) Checked: Marca una casilla o un radio por defecto en el formulario.

36) Footer: Se utiliza para definir un pie de página para un documento o sección. Un pie de página suele contener información sobre el autor del documento, datos de copyright, enlaces a las condiciones de uso, información de contacto, etc.