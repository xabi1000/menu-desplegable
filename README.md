# Navbar Menu Totalmente Responsivo

Este código implementa un menú de navegación totalmente responsivo que se adapta a diferentes tamaños de pantalla. Está escrito en JavaScript y utiliza eventos de escucha para hacer que el menú sea interactivo.

-La función addClick se encarga de mostrar y ocultar los submenús al hacer clic en los elementos del menú. Utiliza la propiedad clientHeight para obtener la altura del submenú y scrollHeight para establecer su altura al mostrarlo. Además, cambia la clase del elemento del menú para reflejar su estado actual.

-La función deleteStyleHeight se utiliza para eliminar el estilo de altura en los submenús cuando la pantalla se amplía y se hace visible el menú completo. Esto asegura que el menú se muestre correctamente en pantallas grandes y previene problemas de visualización.

-El evento de escucha resize se encarga de detectar cambios en el tamaño de la pantalla y actualizar el menú en consecuencia. Si la pantalla es lo suficientemente grande, se llama a deleteStyleHeight para restablecer los estilos de los submenús. Si la pantalla es lo suficientemente pequeña, se llama a addClick para hacer que el menú sea interactivo.

-Finalmente, el evento de escucha click se utiliza para mostrar y ocultar el menú en pantallas pequeñas. Cuando se hace clic en el botón del menú hamburguesa, se agrega o elimina una clase CSS para mostrar u ocultar el menú.
