# Bacano · Sistema de gestión (demo)

Demo funcional del sistema de gestión para **Bacano Show Room · Barber Shop** (Salta Capital).
Es un único archivo `index.html`: se abre en cualquier navegador, sin servidor ni instalación.

## Cómo probarla
Igual que las demás demos del Sistema RAVE: **adelante la página pública, detrás el panel del equipo**.

- **Página pública** (al abrir el link): servicios, productos, turnero online, Club Bacano y WhatsApp.
- **Acceso del equipo**: botón al pie de la página pública (o `#acceso`). Se elige el usuario y se ingresa con PIN:

| Usuario | Rol | PIN | Qué ve |
|---|---|---|---|
| Administrador | Dueño | 1111 | Todo, las dos sucursales (incluye alta y edición de productos) |
| Julián Ferreyra | Encargado · Centro | 2222 | Su sucursal: dashboard, agenda, mostrador, inventario, ranking, clientes y marketing |
| Lucas Medina | Encargado · Norte | 3333 | Ídem, sucursal Norte |
| Tomás Gutiérrez | Barbero · Centro | 4444 | Agenda, mostrador, clientes y sus números |

- **Tarjeta personal del club**: `#tarjeta=<id-del-cliente>` (se envía por WhatsApp desde la ficha del cliente).

## Qué incluye
- **Página pública**: servicios con precios, equipo, sucursales con “Cómo llegar”, botón de WhatsApp y reserva de turno en 4 pasos (servicios, sucursal y barbero, día y horario, datos). Confirmación por WhatsApp y Google Calendar.
- **Productos en la página pública**: catálogo por categorías (peinado, barba, cuidado, accesorios y merch) con precio y disponibilidad por sucursal. El cliente arma su pedido y lo envía por WhatsApp a la sucursal para retirar y pagar en el local. No deja reservar más de lo que hay en stock.
- **Inventario** (administrador y encargados): stock por sucursal, alertas de stock bajo y agotado, productos más vendidos, margen y valor del stock. Registra ingresos de mercadería, conteos y ajustes, y transferencias entre sucursales, con historial de movimientos por producto. Genera el pedido de reposición agrupado por proveedor. Solo el administrador crea o edita productos y precios; cada encargado ve y mueve el stock de su sucursal.
- **Agenda de turnos**: por día, sucursal y barbero, con estados (a confirmar, confirmado, atendido, no vino, cancelado), confirmación por WhatsApp y cobro directo desde el turno.
- **Club Bacano**: tarjeta de sellos (10 visitas = corte gratis, configurable). Los clientes se suman desde la web, consultan su tarjeta con su WhatsApp y el premio se canjea en el mostrador.
- **Marketing**: campañas por WhatsApp que se arman solas (recordatorio de turnos, recuperar inactivos, cumpleaños, a un sello del premio, segunda visita, pedir reseña en Google) y cupones de descuento que se aplican en el mostrador.
- **Multi-sucursal**: Bacano Centro y Bacano Norte, con vista global o por sucursal.
- **Mostrador / POS**: cobro rápido con sucursal, cliente (CRM), uno o más servicios, productos (descuentan stock de la sucursal), barbero, medio de pago y propina. Se puede vender solo un producto sin cargar cliente. Los productos no suman sellos del club y van 100% para Bacano. Cola de espera para tomar turnos y cobrar después.
- **Modelos de trabajo**: alquiler de silla (monto fijo mensual) y comisión por corte (% configurable). Cada cobro guarda su liquidación.
- **Ranking y trazabilidad**: servicios, facturación, aporte a Bacano, ticket promedio, clientes que vuelven y registro de quién hizo cada servicio.
- **CRM**: 150 clientes con historial, corte preferido, barbero de confianza, segmentos (VIP, frecuentes, nuevos, inactivos) y contacto por WhatsApp.

## Datos de demo
Al abrir se generan ~60 días de movimientos relativos a la fecha actual. Lo que se cargue durante la presentación queda guardado en el navegador; el botón **Restablecer datos de demo** vuelve al estado inicial.

Sistema RAVE · Desarrollado por **VINCULAR BUSINESS** · Único celular (387) 4484132 · vincularbusiness@gmail.com · *“Tu idea, en buenas manos.”*
