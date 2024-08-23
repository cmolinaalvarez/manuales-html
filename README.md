# HTML #

1. Que es HTML: 
    1. Lenguaje de marcado de hipertexto
    2. HTML describe la estructura de una página web
    3. HTML consiste en una serie de elementos. Los elementos etiquetan partes del contenido, como "esto es un encabezado", "esto es un párrafo", "esto es un enlace", etc.

2. Etiquetas Meta
    1. charset UTF8: Distrubución de letras y símbolos UTF8, la cual nos va a permitir tener la Ñ o símbolos especiales como los acentos.

3. Etiquetas Semánticas: Son elementos HTML que aportan estructura y significado al contenido de una página web.

    1. Header: Sirve para generar la cabecera del documento, o incluso para generar la cabecera de una sesión de contenido.

    Cabecera de nuestra web

    ```html
    <header>
        <h1>Título de la página</h1>

        <p>Subtítulo o descripción breve</p>

        <!-- Logotipo -->
        <!-- Barra de navegación -->
        <!-- Barra de búsqueda -->
        <!-- Enlaces a redes sociales -->        


    </header>    
    ```

    2. Nav: Barra de navegación que sirve para generar una barra de navegación principal o una navegación alternativa.

    ```html
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Quienes somos?</a></li>
            <li><a href="#">Servicios</a></li>
            <li><a href="#">Contacto</a></li>     
        </ul>
    </nav>    
    ```

    3. Sectioin: La etiqueta section nos permite definir una sección de contenido, si quisieramos crear un breve apartado sobre un producto o servicio.

    ```html
    <section>
        <h2>Sección importante</h2>
        <p>Contenido relevante</p>            
    </section>    
    ```

    3. Article: La etiqueta article nos permite definir una pieza de contenido independiente. Es decir, contenido que podría funcionar por si solo sin necesidad de todo lo que rodea: un producto, un servicio, una noticia, etcetera. 

    Generalmente los vamos a ver dentro de section pero no es obligatorio. 

    ```html
    <article>
        <h2>Título del artículo</h2>
        <p>Contenido del artículo</p>            
    </article>    
    ```

     3. Footer: Nos sirve para generar el pie de página principal del documento o el pie de página de una sección de contenido. Tradicionalmente, aquí van cosas como los derechos reservados y algunos enlaces adicionales de la web.

    Generalmente los vamos a ver dentro de section pero no es obligatorio. 

    ```html
    <footer>
       
        <p>Todos los derechos reservados</p>   
        <nav>
            <ul>
                <li><a href="#">Términos y condiciones</a></a></li>
                <li><a href="#">Mapa del sitio</a></li>
                <li><a href="#">Información legal</a></li>
                <li><a href="#">Contacto</a></li>     
            </ul>
        </nav>             
    </footer>    
    ```
4. Ventajas de las etiquetas semánticas: Las etiquetas semánticas en HTML ofrecen diversas ventajas que contribuyen a una mejor estructuración y comprensión del contenido de una página web.

    1. Claridad en el significado
    2. Mejora de la accesibilidad
    3. Fácil mantenimiento
    4. Beneficios de la SEO
   
5. Etiquetas de texto (Headings)

    1. h1. Es el título principal de toda la página, se recomienda que solo exista un h1 en toda la página.
    2. h2. Es el título secundario 
    3. h3. Es el título terciario
    4. h4. Es el título cuternario
    5. h5. Es el título quinario
    6. h6. Es el título sextenario

6. Parrafos

    1. h1. Es el título principal de toda la página, se recomienda que solo exista un h1 en toda la página.
    2. h2. Es el título secundario 
    3. h3. Es el título terciario
    4. h4. Es el título cuternario
    5. h5. Es el título quinario
    6. h6. Es el título sextenario

7. Formateo de texto: ver archivo index_5.html

8. Citas y referencias : ver archivo index_6.html

9. Links:  ver archivo index_7.html

10. Imágenes:  ver archivo index_8.html

11. Favicon:  ver archivo index_9.html

12. Tablas:  ver archivo index_10.html

13. Listas:  ver archivo index_11.html

14. Listas (más listas):  ver archivo index_12.html

15. Elementos de bloque y elementos de línea: ver archivo index_13.html

16. Div y Span: ver archivo index_14.html

17. Formularios: Permiten recopilar información interactivamente de los usuarios en una página web. Pueden contener diversos elementos como; campos de texto, casillas de verificación, botones de radio, menús desplegables y más.

    1. Estructura: <form> encierra los elementos.
    2. Entrada de datos: <input>, <select>, <textarea> para recopilar datos.
    3. Envío: Atributo method (GET, POST) define como se envían los datos al servidor.
    4. Destino: Atributo action en <form> indica la URL para procesar datos.
    5. Interactividad: Botones <input type="submit"> para enviar.
    6. Que son las etiquetas input: Se utilizan para crear campos de entrada; como cajas de texto, contraseñas, botones de radio, casillas de verificación, etc. 
    ```html
    <input type="text" name="nombre" placeholder="Nombre completo">
    <input type="password" name="contraseña" placeholder="Contraseña>
    <input type="radio" name="genero" value="masculino"> Masculino
    <input type="checkbox" name="suscripcion" checked> Suscribase al boletín
    ```
    7. Que son las etiquetas textarea: Se utilizan para crear áreas de texto de varias líneas en un formulario. A diferencia de la etiqueta <input type="text">, que crea una caja de texto de una sola línea. <textarea> permite a los usuarios ingresar y editar texto en un espacio más grande.
    ```html
    <textarea name="comentario" rows="4" cols="50"></textarea>
    ```
    8. Etiquetas select y option: Se utilizan para crear listas desplegables (también conocidas como menús desplegables o selectores) en formularios web. Estas etiquetas permiten a los usuarios seleccionar una opción de una lista predefinida.
    ```html
    <select name="ciudad">
        <option value="ny">Nueva York</option>
        <option value="la">Los Ángeles</option>
        <option value="chi">Chicago</option>
    </select>
    ```
    9. Botón submit: Es el element clave para enviar un formulario. Se puede usar la etiqueta <button> o la etiqueta <input> con el atributo type submit.
    ```html
    <button type="submit">Enviar</button>
    ```
    10. Métodos de envío: 

        1. Método Get: 
            1. Los datos del formulario se adjuntan a la URL como parámetros
            2. Es visible en la barra de direcciones del navegador
            3. Tiene limitaciones en la cantidad de datos que se pueden enviar
            4. Es menos seguro para información sensible como contraseñas, ya que los datos son visibles en la URL


    







    
   