# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```
## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).


Quiero desarrollar una aplicación web completa llamada TallerOnline.do, enfocada en conectar talleres mecánicos y proveedores de repuestos con clientes en Santo Domingo, República Dominicana.

El objetivo es permitir:

Agendar citas en línea para mantenimiento o reparación.

Solicitar cotizaciones según tipo de vehículo y servicio.

Mantener historial de servicios y recordatorios automáticos.

Conectar talleres con suplidores de repuestos.

⚙️ Requerimientos funcionales

Módulo de usuario (cliente):

Registro/login (email, Google, teléfono).

Selección de taller por ubicación o tipo de servicio.

Solicitud de cita o cotización.

Chat o mensajes con el taller.

Historial de servicios y facturas.

Recordatorios de mantenimiento (por km o fecha).

Módulo de taller:

Registro del taller (nombre, dirección, horario, servicios, precios).

Panel de administración de citas.

Gestión de cotizaciones (crear, aprobar, rechazar).

Historial de clientes y vehículos atendidos.

Integración con proveedores de repuestos.

Módulo de proveedor (repuestos):

Registro de empresa.

Catálogo de productos (nombre, marca, modelo, precio).

Opción de responder solicitudes de talleres.

Administrador del sistema:

Panel de control con estadísticas de uso.

Gestión de usuarios, talleres y proveedores.

Control de pagos o suscripciones.

💳 Monetización

Plan gratuito con límite de citas mensuales.

Plan Premium para talleres con estadísticas, recordatorios automáticos y más visibilidad.

Comisión por venta de repuestos o servicios.

🧩 Funciones avanzadas opcionales

Integrar Google Maps API para localizar talleres cercanos.

Enviar notificaciones por correo o WhatsApp Business API.

Dashboard con gráficas de rendimiento del taller.

API REST para apps móviles futuras.
