# Brotes · Tu solución saludable

Tienda online simple para **Brotes**, un emprendimiento de productos saludables de Córdoba (harinas, semillas, frutos secos, yerbas, condimentos y más).

El cliente elige sus productos desde el celular, completa su nombre y forma de entrega, y el pedido se abre en **WhatsApp ya escrito**, listo para enviar a Rodri o a Vero. No hace falta WhatsApp Business, ni base de datos, ni pagos online: el emprendimiento confirma disponibilidad y forma de pago por chat, como siempre.

![Capturas de la tienda en el celular](captura.png)

## Qué hace

- Catálogo de 180 productos en 15 categorías, con buscador que ignora acentos.
- Pantalla de inicio limpia: buscador y categorías como pastillas; los productos aparecen al elegir una categoría.
- Pedido con cantidades, total estimado y datos de entrega (envío o retiro).
- Botón para enviar el pedido por WhatsApp a la persona que el cliente elija.
- Los precios se leen de una **planilla de Google Sheets** publicada como CSV: el emprendimiento actualiza precios y stock sin tocar código.
- Si la planilla no responde, la tienda usa una lista de precios de respaldo incluida en el archivo.
- El pedido en curso queda guardado en el navegador del cliente.
- Diseño pensado para celular y para personas de cualquier edad: botones grandes, textos claros, modo oscuro automático.

## Tecnología

Un solo archivo `index.html` con HTML, CSS y JavaScript sin frameworks ni dependencias. 
