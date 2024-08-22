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
   
