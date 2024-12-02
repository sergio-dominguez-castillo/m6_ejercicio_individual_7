## Diseño MovieDB App

Para este punto ya deben estar listas las configuraciones del Backend, es decir, 
la API debe responder los datos que le estamos pidiendo y nuestra base de datos SQLite 
debe estar correctamente configurada para poder interactuar con ella.

1. Crea una vista que contenga una TopBar con su respectivo título y un botón que permita 
agregar una nueva película.
-  Al momento de dar clic al botón se deben pedir los datos a la API y en el mismo proceso 
almacenarse en la base de datoss.

2. Es importante que cada nueva película se pueda visualizar en el LazyColum que va a mostrar la 
totalidad que agreguemos.
- Importante: Algunas API’s suelen agrupar los datos en pages de 10 o más elementos, de ser ese el 
caso debes generar una paginación interna que permita acceder a las películas de las páginas siguientes.

3. Crea una Card para el diseño de las películas que componen la vista.
- Incluye todos los datos del model.
- Incluye un botón de eliminar dentro de la Card.
- El tamaño de la Card debe ser tal, que al momento de iniciar nuestra aplicación debe verse máximo 
dos películas en la columna.

4. En caso de que quieras realizar un diseño más novedoso, puedes modificar el Model para obtener 
más datos de la API, especialmente la ruta del “backdrop_path” que puede servir para generar una
Card más llamativa.
- Este punto es opcional, pero le podría dar un plus extra al diseño de tu aplicación.

5. Una vez los cambios solicitados estén listos, actualiza el repositorio de GitHub y comparte 
nuevamente el enlace en el nodo.