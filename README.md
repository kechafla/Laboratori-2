# Laboratorio-2
Laboratorio de Programacion Integrativa de Componentes Web

1. index.html
Esta página sirve como mi presentación personal. En ella, incluyo:
Componentes principales:
<app-header> y <custom-menu>: Como en las otras páginas, para una experiencia de usuario consistente.
<mi-tarjeta>: Es un componente personalizado que he creado para mostrar mi tarjeta de presentación. Este componente tiene tres ranuras:
imagen: Donde incluyo una foto de perfil.
titulo: Aquí aparece mi nombre.
descripcion: Una breve descripción sobre mí, mis intereses y mis metas.
<mi-footer>: Pie de página reutilizado para cerrar la página.
Estilos y scripts:
Utilizo custom-menu2.css y footer.cs para estilizar el menú y el pie de página.
La funcionalidad de mi tarjeta de presentación está implementada en tarjeta_presentacion.js.

2. galeria_json.html
Esta página está orientada a presentar una galería que consume datos de una API JSON. He integrado lo siguiente:
Componentes principales:
<app-header> y <custom-menu>: Igual que en api.html, para mantener consistencia.
<galeria-json>: Este componente conecta con https://jsonplaceholder.typicode.com/users y renderiza los datos como una galería. Está implementado en galeria/galeria_jason.js.
<mi-footer>: Reutilizo el pie de página común.
Estilos y scripts:
Uso estilos.css para la presentación visual.
Mantengo la modularidad con scripts específicos y estilos compartidos.

3. api.html
Esta página está pensada para mostrar información sobre razas de perros. Utilizo varios componentes personalizados para estructurar el contenido:
Componentes principales:
<app-header>: Un encabezado reutilizable, implementado mediante header.js.
<custom-menu>: Un menú dinámico definido en custom-menu2.js, que facilita la navegación.
<mi-api>: Un componente encargado de mostrar información sobre las razas de perros, cargado desde api/api.js.
<mi-footer>: Un pie de página común que reutilizo en todas las páginas, definido en footer.js.

Recursos adicionales:
Incluyo librerías externas como CryptoJS para funcionalidades específicas, como encriptación.
Aplico estilos personalizados desde custom-menu2.css y footer.cs.



