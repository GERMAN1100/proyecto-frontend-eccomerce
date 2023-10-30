# proyecto-frontend-eccomerce

El proyecto se baso en la creacion de un eccomerce, en este caso, optamos por que este sea de celulares.

El mismo, se llama TIENDARG, y su pagina principal, se ve un header , el cual da la bienvenida,muestra su logo, un form en donde registrase para recibir en caso que quieran informacion acerca de ofertas o productos nuevos, y la presentacion de carrito.

Luego pasa a mostrarse todo el catalogo de celulares que se encuentran en el momento a la venta, y por ulltimo, un footer, el cual contiene la informacion de la empresa, el contacto y los medios de pago.

Al seleccionar cualquiera sea de los productos, este los llevara a su pagina Detalle, en el cual, podra observarse con mas detalle el smartphone como sus caracteristicas, en esta, tambien se encontraran los botones para agregar al carrito y la cantidad que desea.

Al seleccionar la cantidad deseada, y  al poner agregar, se agregara inmediatamente a Carrito, que es la pagina en la cual, se vera lo que esta comprando, su valor, y para terminar de comprar. En el caso de arrepentirse de su comprar, puede presionar en eliminar,
el cual eliminara inmediatamente el producto que se estaba guardando en el carrito.

En el caso de seguir con la compra, al pulsar el boton pagar ahora, se abrira otra pagina, en la cual podra finalizar el pago seleccionando un tipo de tarjeta, llenando todos los campos correctamente, y por ultimo presionar pagar.

Cuando presiona en pagar, este los llevara a otra pagina, en la que los felicitara y agradecera por su compra.

Se utilizo una API personalizada para cargar la lista de productos. 
los productos seleccionados y sus cantidades son colocados en un array que es almacendado en el LocalStorage del navegador y de alli son enviados a un nuevo array que almacena las ultimas compras, en caso de que los productos sean elimidados por haber sido cancelada la compra, soy eliminados del array de manera permamente.

Se utilizo html, para la creacion de la pagina, css para la estilizacion de la misma, y js, para acceder y modificar elementos HTML y CSS en una página web, permitiendo crear interactividad, cambiar el contenido de la página y responder a eventos del usuario.
