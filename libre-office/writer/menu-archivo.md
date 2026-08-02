# Menú Archivo de LibreOffice Writer

*Esquema revisado y ampliado con las opciones del cuadro de diálogo Imprimir*

- **Nuevo**
    - Crea un documento nuevo.
    - **Elementos:**
        - **Documento de texto (.odt) (CTRL + U):** Documento de LibreOffice Writer.
        - **Hoja de cálculo (.ods):** Libro de LibreOffice Calc.
        - **Presentación (.odp):** Presentación de LibreOffice Impress.
        - **Dibujo (.odg):** Dibujo vectorial de LibreOffice Draw.
        - **Fórmula (.odf):** Fórmula de LibreOffice Math; no realiza cálculos.
        - **Base de datos (.odb):** Base de datos creada o conectada mediante LibreOffice Base.
        - **Documento HTML (.html):** Página web creada con Writer.
        - **Documento de formulario XML (.odt):** Formulario XForms creado con Writer.
        - **Etiquetas (.odt):** Asistente de Writer para crear etiquetas postales.
        - **Tarjetas de presentación (.odt):** Asistente de Writer para crear tarjetas de presentación.
        - **Documento maestro (.odm):** Organiza como una unidad varios documentos de Writer.
        - **Plantillas:** Abre el gestor de plantillas:
            - Texto: **.ott**
            - Hoja de cálculo: **.ots**
            - Presentación: **.otp**
            - Dibujo: **.otg**
            - Documento maestro: **.otm**
            - Documento HTML: **.oth**

- **Abrir (CTRL + A o CTRL + O)**
    - Abre uno o varios documentos guardados.
    - **Opciones:**
        - **Versión:** Abre en modo de solo lectura una versión guardada dentro del archivo.
        - **Solo lectura:** Abre inicialmente el documento en modo de solo lectura.

- **Abrir remoto**
    - Abre documentos almacenados en un servidor o servicio remoto.
    - **Opciones:**
        - **Servicio:** Selecciona una conexión remota configurada.
        - **Gestionar servicios:** Permite añadir, modificar o eliminar conexiones.
        - **Tipo de servicio:**
            - **Google Drive:** Accede a los archivos de una cuenta de Google Drive.
            - **Servicios CMIS:** Permiten conectarse a servidores que implementan el estándar CMIS, como Alfresco, Nuxeo, OpenText, SharePoint u otros servicios compatibles.
            - **WebDAV:** Utiliza una extensión de HTTP para gestionar archivos y carpetas en un servidor remoto.
            - **Recurso compartido de Windows:** Accede a carpetas compartidas mediante los servicios de archivos de Windows.
            - **SSH:** Utiliza SFTP para transferir archivos de forma segura; esta conexión no está disponible en Windows.
        - **Datos de conexión:** Varían según el servicio y pueden incluir servidor, raíz, recurso compartido, repositorio, usuario, contraseña y etiqueta.
        - **Recordar contraseña:** Guarda la contraseña en el perfil de usuario de LibreOffice, protegida por la contraseña maestra cuando esta se ha configurado.
        - **Filtro:** Limita los archivos mostrados según su tipo.
        - **Nombre de archivo:** Permite indicar el documento que se desea abrir.

- **Documentos recientes**
    - Muestra los documentos abiertos recientemente.
    - **Límite:** Muestra 25 elementos de forma predeterminada; puede configurarse entre 0 y 100 mediante PickListSize, en la configuración experta.
    - **Vaciar lista:** Elimina las entradas de la lista, pero no borra los archivos.
    - **Solo módulo actual:** Muestra únicamente los documentos del módulo activo, como Writer o Calc.

- **Cerrar (CTRL + F4)**
    - Cierra el documento actual sin salir de LibreOffice.

- **Asistentes**
    - Facilita la creación guiada de determinados tipos de documentos.
    - **Opciones:**
        - **Carta:** Asistente de seis pasos para crear una plantilla de Writer (.ott) para cartas.
        - **Fax:** Asistente de cinco pasos para crear una plantilla de Writer (.ott) para faxes.
        - **Orden del día:** Asistente de seis pasos para crear una plantilla de Writer (.ott) para reuniones.
        - **Conversor de documentos:** Convierte documentos de Microsoft Word, Excel y PowerPoint a formatos OpenDocument.
        - **Origen de datos de direcciones:** Registra una libreta de direcciones existente, como la de Thunderbird, como origen de datos de LibreOffice.

- **Plantillas**
    - Permite guardar el documento actual como plantilla, editar plantillas existentes y abrir el Gestor de plantillas.
    - **Opciones:**
        - **Guardar como plantilla:**
            - Guarda el documento actual como una plantilla.
            - Permite asignarle un nombre y seleccionar la categoría en la que se almacenará.
            - Incluye la opción **Establecer como plantilla predeterminada**.
            - La plantilla guardada aparece automáticamente en el Gestor de plantillas.
        - **Editar plantilla:** Abre un diálogo para seleccionar una plantilla y modificarla en modo de edición. En el caso de las plantillas incorporadas, puede editarse una copia.
        - **Gestionar plantillas (CTRL + MAYÚS + N):** Abre el gestor para crear documentos a partir de modelos y administrar las plantillas instaladas.
            - **Buscar:** Localiza plantillas por su nombre.
            - **Filtro:** Limita las plantillas según el tipo de documento.
            - **Categorías:** Muestra las plantillas de una categoría concreta.
            - **Gestionar:**
                - **Categoría nueva:** Crea una categoría.
                - **Cambiar nombre de categoría:** Renombra la categoría seleccionada.
                - **Eliminar categoría:** Suprime la categoría seleccionada.
                - **Restablecer documento de texto predeterminado:** Recupera la plantilla predeterminada integrada de Writer.
                - **Importar:** Añade plantillas desde un archivo.
                - **Extensiones:** Busca nuevas plantillas en línea.
            - **Vistas:** Muestra las plantillas como miniaturas o como lista.
            - **Acciones sobre una plantilla:** Permite abrirla, editarla, establecerla como predeterminada, cambiarle el nombre, eliminarla, moverla a otra categoría o exportarla, según el tipo de plantilla.

- **Recargar**
    - Sustituye el documento actual por su última versión guardada y descarta los cambios posteriores.

- **Versiones**
    - Permite guardar, abrir, eliminar y comparar varias versiones del documento dentro del mismo archivo.

- **Guardar (CTRL + G)**
    - Guarda los cambios en el documento actual.

- **Guardar como (CTRL + MAYÚS + S)**
    - Guarda el documento con otro nombre, formato o ubicación.
    - El documento permanece abierto con el último nombre, formato y ubicación elegidos.
    - **Opciones:**
        - **Extensión de nombre de archivo automática:** Añade la extensión correspondiente al formato elegido.
        - **Guardar con contraseña:** Protege el documento mediante una contraseña, siempre que el formato seleccionado admita esta función.
        - **Cifrar con clave GPG:** Cifra el documento para los destinatarios seleccionados mediante OpenPGP.
        - **Firmar con certificado predeterminado:** Firma digitalmente el documento al guardarlo.
        - **Editar configuración de filtros:** Permite ajustar las opciones del formato de archivo seleccionado.

- **Guardar archivo remoto**
    - Guarda el documento en un servidor o servicio remoto.
    - Utiliza los mismos tipos de servicio y datos de conexión que **Abrir remoto**.

- **Guardar una copia**
    - Guarda una copia con otro nombre, formato o ubicación.
    - Mantiene abierto el documento original.
    - Ofrece opciones de archivo similares a **Guardar como**.

- **Guardar todo**
    - Guarda todos los documentos modificados de LibreOffice.
    - Si un documento es nuevo o procede de un archivo de solo lectura, abre el diálogo **Guardar como**.

- **Exportar**
    - Crea una copia del documento en otro formato y mantiene abierto el archivo original.
    - **Tipos:**
        - **XHTML (.html, .xhtml):** Página web en formato XHTML.
        - **PDF (.pdf):** Documento de diseño fijo para visualizar, compartir o imprimir.
        - **Documento EPUB (.epub):** Libro electrónico para lectores digitales y dispositivos móviles.
        - **MediaWiki (.txt):** Texto con el marcado utilizado por MediaWiki.
        - **XML de exportación de indización de Writer (.xml):** Datos del documento preparados para su indización.
        - **JPEG (.jpg, .jpeg, .jfif, .jif, .jpe):** Imagen de mapa de bits comprimida con pérdida.
        - **XML de disposición de Writer (.xml):** Información XML sobre la disposición calculada del documento.
        - **PNG (.png, .apng):** Imagen de mapa de bits comprimida sin pérdida.
        - **WebP (.webp):** Imagen comprimida en formato WebP.

- **Exportar a**
    - Exporta el documento directamente a PDF o EPUB.
    - **Opciones:**
        - **Exportar a PDF:** Permite configurar las opciones del archivo PDF antes de guardarlo.
        - **Exportar directamente a PDF:** Crea el PDF utilizando la configuración de exportación determinada previamente.
        - **Exportar a EPUB:** Permite configurar las opciones del libro electrónico antes de guardarlo.
        - **Exportar directamente a EPUB:** Crea el EPUB utilizando la configuración de exportación determinada previamente.

- **Enviar**
    - Envía una copia del documento actual a otras aplicaciones o formatos.
    - **Opciones:**
        - **Enviar documento por correo:** Adjunta el documento, en su formato actual, a un mensaje nuevo.
        - **Enviar como texto de OpenDocument:** Adjunta una copia en formato .odt.
        - **Enviar como Microsoft Word:** Adjunta una copia en formato de Microsoft Word.
        - **Por correo como PDF:** Exporta el documento a PDF y lo adjunta a un mensaje nuevo.
        - **A MediaWiki:** Exporta el contenido con el formato de marcado de MediaWiki.
        - **Enviar mediante Bluetooth:** Envía el documento a otro dispositivo mediante Bluetooth.
        - **Crear patrón de documento:** Crea un documento maestro y divide el original en subdocumentos según un estilo de párrafo o un nivel de esquema.
        - **Crear documento HTML:** Convierte el documento en una o varias páginas HTML.
        - **Esquema a presentación:** Crea una presentación de Impress a partir del esquema del documento.
        - **Esquema a portapapeles:** Copia el esquema en el portapapeles con formato RTF.
        - **Crear resumen automático:** Crea un documento con los títulos y párrafos principales.
        - **Resumen automático a presentación:** Crea una presentación de Impress a partir del resumen.

- **Previsualizar en el navegador**
    - Crea una copia HTML del documento en la carpeta de archivos temporales y la muestra en el navegador predeterminado.
    - La carpeta se configura en **Herramientas / Opciones / LibreOffice / Rutas / Archivos temporales**.
    - El archivo HTML se elimina al cerrar LibreOffice.

- **Previsualización de impresión (CTRL + MAYÚS + O)**
    - Muestra cómo quedará el documento al imprimirlo.

- **Imprimir (CTRL + P)**
    - Abre el cuadro de diálogo para configurar e iniciar la impresión.
    - Las opciones disponibles pueden variar según la impresora, el sistema operativo y el módulo activo.
    - **Previsualización:**
        - Muestra el aspecto de las páginas que se imprimirán.
        - La casilla **Previsualización** permite mostrar u ocultar este panel.
        - Los botones de navegación permiten desplazarse a la primera página, la página anterior, una página concreta, la página siguiente o la última página.
    - **Pestañas:**
        - **General:** Contiene las opciones comunes de selección de impresora, intervalo, copias y compaginación.
        - **LibreOffice Writer:** Contiene las opciones de impresión específicas de los documentos de texto.
    - **General:**
        - **Impresora:**
            - Permite seleccionar la impresora que se utilizará.
            - **Estado:** Muestra la disponibilidad de la impresora seleccionada.
            - **Propiedades:** Abre las propiedades de la impresora; las opciones dependen del dispositivo elegido.
        - **Intervalo y copias:**
            - **Todas las páginas:** Imprime el documento completo.
            - **Selección:** Imprime únicamente el contenido seleccionado; solo se activa cuando existe una selección imprimible.
            - **Páginas:** Imprime las páginas o intervalos indicados. Pueden combinarse páginas individuales e intervalos, por ejemplo, 3-6;8;10;12.
            - **Número de copias:** Establece cuántos ejemplares se imprimirán.
        - **Intercalación y caras del papel:**
            - **Incluir:** Permite imprimir páginas impares y pares, solo páginas pares o solo páginas impares.
            - **Caras del papel:** Permite imprimir en una cara o a doble cara cuando la impresora admite impresión dúplex.
            - **Intercalar:** Conserva el orden de las páginas al imprimir varias copias, de forma que se completa una copia antes de comenzar la siguiente.
            - **Crear tareas de impresión separadas para una salida intercalada:** Genera un trabajo de impresión independiente para cada copia.
            - **Imprimir en orden inverso:** Imprime las páginas desde la última hasta la primera.
        - **Compaginación:**
            - **Tamaño de papel:** Selecciona el tamaño del papel utilizado para la impresión.
            - **Orientación:** Permite elegir la orientación automática, vertical u horizontal, según las opciones disponibles.
            - **Páginas por hoja:** Reduce y distribuye varias páginas del documento en una misma cara de una hoja.
            - **Orden:** Establece la secuencia de colocación de las páginas dentro de la hoja.
            - **Trazar borde alrededor de cada página:** Dibuja un borde en torno a cada página colocada en la hoja.
            - **Folleto:** Reorganiza las páginas para imprimirlas como un folleto que pueda plegarse y leerse en el orden correcto.
            - **Páginas por hoja** y **Folleto** son modalidades alternativas de compaginación.
    - **Botones:**
        - **Imprimir:** Inicia el trabajo de impresión con la configuración seleccionada.
        - **Cancelar:** Cierra el diálogo sin imprimir.
        - **Ayuda:** Abre la ayuda correspondiente al cuadro de diálogo.

- **Configuración de impresora**
    - Abre el diálogo de configuración de impresora para seleccionar el dispositivo y ajustar sus opciones para el documento actual.

- **Propiedades**
    - Muestra información y metadatos del documento.
    - **General:** Muestra los datos básicos del archivo y permite modificar algunas opciones.
        - **Información:**
            - **Nombre:** Nombre del archivo.
            - **Tipo:** Tipo de documento.
            - **Ubicación:** Carpeta donde está guardado.
            - **Tamaño:** Espacio ocupado por el archivo.
            - **Creado el:** Fecha y hora de creación.
            - **Modificado el:** Fecha y hora de la última modificación.
            - **Plantilla:** Plantilla empleada para crear el documento.
            - **Firmado digitalmente:** Indica si contiene firmas digitales.
            - **Última impresión el:** Fecha y hora de la última impresión.
            - **Tiempo de edición total:** Tiempo acumulado de edición.
            - **N.º de modificación:** Número de veces que se ha guardado.
        - **Opciones:**
            - **Cambiar contraseña:** Modifica o elimina la contraseña del documento.
            - **Firmas digitales:** Permite añadir, eliminar o consultar firmas digitales.
            - **Aplicar datos de identidad:** Aplica los datos personales configurados en LibreOffice.
            - **Guardar imagen de previsualización con este documento:** Incluye una miniatura en el archivo.
            - **Resolución preferida para imágenes:** Establece la resolución preferida en puntos por pulgada.
            - **Restablecer propiedades:** Restablece los datos de uso y determinadas propiedades generales.
    - **Descripción:** Permite añadir metadatos como el título, el asunto, las palabras clave y los comentarios.
    - **Propiedades personalizadas:** Permite crear campos propios, indicando su nombre, tipo y valor.
    - **Seguridad:** Establece opciones de apertura y seguimiento de cambios.
        - **Abrir documento solo para lectura:** Hace que se abra inicialmente en modo de solo lectura.
        - **Grabar cambios:** Registra las modificaciones realizadas.
        - **Proteger:** Impide desactivar la grabación o aceptar y rechazar cambios sin introducir una contraseña.
    - **Tipo de letra:** Permite incrustar en el archivo los tipos de letra utilizados.
        - **Incrustar tipos de letra en el documento:** Guarda en el archivo las fuentes empleadas para conservar su apariencia en otros equipos.
        - **Incrustar solo tipos de letra utilizados en los documentos:** Incluye únicamente las fuentes realmente usadas.
        - **Sistemas de escritura que incrustar:**
            - **Tipos de letra latinos:** Incrusta las fuentes empleadas para alfabetos latinos.
            - **Tipos de letra asiáticos:** Incrusta las fuentes utilizadas para escrituras asiáticas.
            - **Tipos de letra complejos:** Incrusta las fuentes utilizadas para sistemas de escritura complejos.
    - **Estadísticas:** Muestra el recuento de páginas, tablas, imágenes, objetos OLE, párrafos, palabras, caracteres, caracteres sin espacios y renglones.
        - **Actualizar:** Recalcula las estadísticas del documento.

- **Firmas digitales**
    - Permite firmar documentos y comprobar las firmas existentes.
    - **Opciones:**
        - **Firmas digitales:** Añade o elimina firmas digitales del documento actual y permite consultar sus certificados.
        - **Firmar PDF existente:** Abre un PDF en Draw, en modo de solo lectura, para añadirle una firma digital.

- **Salir de LibreOffice (CTRL + Q)**
    - Cierra todos los documentos y finaliza LibreOffice.
