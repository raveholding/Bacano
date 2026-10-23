# Bacano · Sistema de gestión (demo)

Demo funcional del sistema de gestión para **Bacano Show Room · Barber Shop** (Salta Capital).
Es un único archivo `index.html`: se abre en cualquier navegador, sin servidor ni instalación.

## Cómo probarla
- **Panel del negocio**: abrí `index.html`.
- **Página pública para clientes** (reservas, club, WhatsApp): `index.html#reservar`. También se abre con el botón “Ver página pública” del panel.
- **Tarjeta personal del club**: `index.html#tarjeta=<id-del-cliente>` (se envía por WhatsApp desde la ficha del cliente).

## Qué incluye
- **Página pública**: servicios con precios, equipo, sucursales con “Cómo llegar”, botón de WhatsApp y reserva de turno en 4 pasos (servicios, sucursal y barbero, día y horario, datos). Confirmación por WhatsApp y Google Calendar.
- **Agenda de turnos**: por día, sucursal y barbero, con estados (a confirmar, confirmado, atendido, no vino, cancelado), confirmación por WhatsApp y cobro directo desde el turno.
- **Club Bacano**: tarjeta de sellos (10 visitas = corte gratis, configurable). Los clientes se suman desde la web, consultan su tarjeta con su WhatsApp y el premio se canjea en el mostrador.
- **Marketing**: campañas por WhatsApp que se arman solas (recordatorio de turnos, recuperar inactivos, cumpleaños, a un sello del premio, segunda visita, pedir reseña en Google) y cupones de descuento que se aplican en el mostrador.
- **Multi-sucursal**: Bacano Centro y Bacano Norte, con vista global o por sucursal.
- **Mostrador / POS**: cobro rápido con sucursal, cliente (CRM), uno o más servicios, barbero, medio de pago y propina. Cola de espera para tomar turnos y cobrar después.
- **Modelos de trabajo**: alquiler de silla (monto fijo mensual) y comisión por corte (% configurable). Cada cobro guarda su liquidación.
- **Ranking y trazabilidad**: servicios, facturación, aporte a Bacano, ticket promedio, clientes que vuelven y registro de quién hizo cada servicio.
- **CRM**: 150 clientes con historial, corte preferido, barbero de confianza, segmentos (VIP, frecuentes, nuevos, inactivos) y contacto por WhatsApp.

## Datos de demo
Al abrir se generan ~60 días de movimientos relativos a la fecha actual. Lo que se cargue durante la presentación queda guardado en el navegador; el botón **Restablecer datos de demo** vuelve al estado inicial.

Desarrollado por Rave Holding.
