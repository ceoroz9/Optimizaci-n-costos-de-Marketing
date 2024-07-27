# Optimización-costos-de-Marketing

## Introducción
Como pasante en el departamento de análisis de Yandex.Afisha, mi primera tarea es ayudar a optimizar los costos de marketing. Tengo registros del servidor con datos sobre las visitas a Yandex.Afisha desde junio 2017 a mayo de 2018, un archivo de volcado con todos los pedidos del período y estadísticas de gastos de marketing.

Planeo averiguar cómo la gente usa el producto, cuánto tiempo pasa desde el momento en que el cliente visita el sitio hasta la primera compra, cuánto dinero aporta cada cliente y la efectividad de las fuentes de adquisición de clientes.

## Descripción de los datos
La tabla visits (registros del servidor con datos sobre las visitas al sitio web):

- Uid: identificador único del usuario;
- Device: dispositivo del usuario;
- Start Ts: fecha y hora de inicio de la sesión;
- End Ts: fecha y hora de término de la sesión;
- Source Id: identificador de la fuente de anuncios de la que proviene el usuario.

Todas las fechas de esta tabla están en formato AAAA-MM-DD.
La tabla orders (datos sobre pedidos):

- Uid: identificador único del usuario que realiza un pedido;
- Buy Ts: fecha y hora del pedido;
- Revenue: ingresos de Y.Afisha de este pedido.

La tabla costs (datos sobre gastos de marketing):

- source_id: identificador de la fuente de anuncios
- dt: fecha;
- costs: gastos en esta fuente de anuncios en este día.
