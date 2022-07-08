# desafio-final-m11

> Proyecto realizado por: **Matías Toledo**, **Francisco Ibarrola** y **Álvaro Bastía**.

## Brief:

 - **MARCA**: BOMARKET.
  
 - **MISION**: Centralizar el mercado de hardware que existe en Bolivia-La Paz.
 
 - **TARGET**: Tiendas que no cuentan con su propia pagina web, personas que tienen su negocio informal.
 
 - **PROPUESTA**: Crear una WebPage estilo mercadolibre que muestre los productos y ofrezca contacto directo con el vendedor por medio de whatsapp- facebook, ofrecer a todos los vendedores tener su propio catalogo en la web gratis.
 
 - **MVP**: Una pagina que muestre todos los productos (descripciones/especificaciones/precio) , que cuente con un buscador, en cada producto un enlace directo para comunicarse con el vendedor, y cada vendedor pueda tener su propio catalogo de productos.
 
 - **PROYECTOS SIMILARES**: 
    - **MARKETPLACE-FACEBOOK**: Es el que actualmente mas se utiliza,si bien los vendedores dejan su numero de whatsapp en algunas publicaciones en cada publicacion hay que copiar pegar un numero de facebook a celular ya que no ofrece acceso directo y no todos los vendedores ofrecen una atencion rapida por medio de messager. 
    - **MERCADOLIBRE**: Es una pagina que no tiene ingerencia en el mercado, solo algunas publicaciones. 

 
## Web:
  - **URL**: https://bomarket.vercel.app/

## Scrum:

  > **Planning Sprint 1**:
    - Organizando la planning con lo que se necesita realizar de código.
    - Viendo cómo distribuir los datos en la base de datos de la forma más óptima.
    - Escribimos los user stories en trello.
    - Definimos roles:
        **FrontEnd**:
	        Alvaro Bastía.
        **Backend**:
	        Fran Ibarrola.
        **Fullstack**:
	        Matías Toledo.
    - Tareas:
      **FrontEnd**:
        - Alva:
          Poder publicar los productos.
          Estilar la home de la webpage.
          Permitir actualizar los datos del perfil del usuario.
        - Mati:  
          Modificar los estilos del perfil del usuario.
          Estilar las cards de los productos.
      **BackEnd**:	
	- Mati:
          Hacer form para cargar los productos (Back y front).
	- Fran:
          Actualizar los datos del perfil del usuario.
	- Definimos el día y el horario de los dailys.
        1er día: 30 de junio 2022, hora a (19:00 hs, Arg).

### Daily 1: 30/06/22 a las 19hs Arg:
  
  - Se habla del back para cambiar el editar perfil, y hacerlo en el frontEnd.
  - Se discute cómo encarar una problemática del backend con la base de datos.
  - Para hacer: Comparar si el token del usuario que está en la página es el mismo que el del vendedor del catálogo y si no, no dejar editar productos.
  - Agregar un icono de la foto de perfil del ususario con su nombre desde el header de pc.
  - Agregar las sweetalert en el login y cuando se edita/publica un producto.
  - Agregar categoría y stock de un producto.
  - Agregar la sync entre algolia y airtable (en back y front).

### Daily 2: 01/07/22 a las 20hs Arg:
  
  - Realizamos las tareas que habíamos denominado para cada uno el daily anterior.
  - Actualizamos componentes con estilos nuevos.
  - (yo) Creé una página y un componente para mostrar el catálogo de un vendedor.
  - (yo) Creé los hooks necesarios para los nuevos componentes añadidos.

### Daily 3: 02/07/22 a las 19hs Arg:

  - Matias realizó endpoint con los productos en el back.
  - El frontEnd no sube productos, debe arreglarse.
  - Hablamos de hacer el loader un componente (para así escribir menos código repetitivo).
  - Realicé los componentes de editar y publicar productos, y mejoré estilos del menú de la página, también cambiamos el título de la página.
  - Voy a realizar nuevos cambios virtuales en el frontEnd.
  - Cambiar el menú de mobile.
  - Sacar las redes sociales del footer.
  
  Para hacer:
    - Corregir errores del back.
    - Corregir errores del front.
    - Añadir nuevas funcionalidades tanto en el front como en el back.
    - Hacer el hook del sync.

### Daily 4: 05/07/22 a las 15hs Arg:
  
  - cosas a corregir:

    - Pagination del front.
    - SearchHeader del front.
    - Agregar la foto de perfil y descripción del vendedor en el catálogo.
    - Agregar “Mi catálogo” al header de pc y footer.
    - Agregar un link para compartir el catálogo.
    - Hacer lo de whatsapp más llamativo.
    - Optimizar “productos destacados” en el back y front.

  - Hablamos de lo que nos falta hacer a cada uno y de lo que hicimos para ese daily.

### Daily 5: 06/07/22 a las 17hs Arg:

  - Cosas para hacer (se realizar antes de hacer el retro):
    
    - Sacar redes del footer.
    - Palabra “Encuentra” en vez de "Encontrá" en el buscador.
    - Cards con precio de los productos en peso boliviano.
    - Pagination (sacarla de catálogo). Agrandar las flechas y darles ```css cursor: pointer;```
    - Ajustar las cards para que todas tengan el mismo tamaño.
    
### Retro: 06/07/22 a las 17hs Arg:

  #### Mi opinión sobre el proyecto y el desafío final:
  
  Yo creo que todo fue bastante fluido, nos adaptamos a la formas distintas de trabajar que teníamos los 3 contribudores del proyecto y lo llevamos adelante. El estilo de trabajo de cada uno varía bastante y la forma de pensar la lógica para el código también, hubiese sido mejor todavía si tomábamos un estilo de trabajo como base.
    
  Me gustó mucho que hayamos creado una branch `prueba` y que para otras pruebas más "complejas" de código hayamos creado una rama aparte basándonos en `prueba` para no romper la branch de producción `main`. Nuestra organización fue clave para el proyecto, escribíamos todo lo que hacíamos y faltaba hacer en `Trello`, de esta forma, todos los días entrabamos para ver qué bugs teníamos que corregir y a quién se le asignaba cada tarea.
    
  No hubo errores graves que nos hayan complicado las cosas a la hora de codear/trabajar, cada vez que alguno de los contribudores tenía un problema, siempre estábamos en whatsapp ayudándonos a pensar como solucionarlo y seguir adelante con el proyecto.
    
  Me pareció interesante realizar un brief con una problemática de otro país (Bolivia), ya que casi siempre apuntamos a mejorar cosas que ocurren solo en nuestro país o hasta en nuestra ciudad/provincia, está bueno indagar y entender que está pasando en otros países también.
    
  Para que nuestra experiencia haya sido de solo un año y sea la primera vez en la que trabajamos en un grupo, pudimos llevar adelante una metodología para poder manipular los repositorios entre los 3 contribuyentes sin chocarnos el uno con el otro y nunca hubo un problema de ese estilo, lo cuál me alegra mucho ya que demuestra nuestro nivel de organización y responsabilidad.
  
  A pesar de que los dailys no se tenían que obligatoriamente en días consecutivos, todo el grupo tuvo la predisposición para hacer que los dailys sean consecutivos y así poder hablar en un daily lo que planteamos resolver en el anterior.
  
  Disfruté mucho este desafío y este proyecto, muy buen grupo y se nota cuando todas las personas quieren y están dispuestas a trabajar.
  
### Proyecto Desafío Final Módulo 11: BOMARKET (Carrera apx).
