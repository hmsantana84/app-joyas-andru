# Las Joyas de Andru

Aplicación local para probar un catálogo de joyas, el mantenimiento de productos y el envío de pedidos por WhatsApp.

## Cómo abrirla

Abrí `index.html` en un navegador moderno. No requiere instalación ni conexión a un servidor.

## Administración de prueba

- Seleccioná **Administración** e ingresá el código inicial `1234`.
- Agregá joyas con foto, descripción, precio en pesos argentinos, categoría y stock.
- En **Datos de contacto**, revisá y guardá el número de WhatsApp. Debe incluir el código de país y de área, solo con dígitos.
- En **Cambiar clave de ingreso**, ingresá la clave actual y escribí y confirmá la nueva (mínimo 4 caracteres).
- Para editar una joya, se puede conservar la foto existente o elegir otra.

El número viene precargado como `5492975178589`, inferido del teléfono que figura en el logo. Confirmá que sea el número correcto antes de compartir la aplicación.

## Alcance de esta versión

Los productos y fotos se guardan en IndexedDB del navegador; el carrito, el teléfono y la clave de administración se guardan en el almacenamiento local del mismo navegador. Esta versión es para probar en un solo equipo: los cambios no se comparten con otros dispositivos y borrar los datos del navegador puede eliminarlos. La clave es solo una barrera de demostración, no un acceso seguro. Para publicar la tienda con catálogo compartido y administración protegida hace falta conectar un servidor, una base de datos y autenticación.

Enviar el carrito abre WhatsApp con el mensaje preparado. El pedido queda sujeto a confirmación del vendedor y no reserva ni descuenta stock automáticamente.
