# ASLAN Plastik · Demo del Módulo 0

Demo navegable del **Módulo 0 (Base del sistema y arranque)** del sistema de trazabilidad e inventario de **ASLAN PLASTIK S.A.S.**, para validar el diseño con el cliente antes de construir.

**Ver el demo:** https://andriuxone.github.io/aslan-plastik-demoM0/

> Este no es el sistema final. Es un prototipo en un solo archivo HTML, con datos de ejemplo. El desarrollo del producto está en otro repositorio.

## Usuarios de prueba

La pantalla de ingreso tiene la lista de usuarios: al tocar una fila se llenan el usuario y la clave.

| Usuario | Rol | Clave |
|---|---|---|
| `lmendez` | Administrador | `Aslan2026` |
| `cperez` | Extrusor y Perfilador | `1032456789` (cédula; primer ingreso) |
| `jramirez` | Perfilador | `Aslan2026` |
| `nsuarez` | Recepción y Despacho | `Aslan2026` |
| `rvargas` | Consulta / Gerencia | `Aslan2026` |

Nombres, cédulas, clientes y proveedores son **inventados**. Los calibres y pesos del tubo son los confirmados por ASLAN.

## Qué incluye

Ingreso con bloqueo por intentos fallidos, cierre por inactividad y cambio rápido de usuario; recuperación de clave a través del Administrador (la persona pide ayuda desde el ingreso y el Administrador restablece la clave a la cédula); primer ingreso con aceptación de términos y cambio de clave; usuarios, roles y permisos; turnos por rol con simulador; aprobación de turnos; maestros (clientes, calibres, máquinas, proveedores, colores, tipos de material y productos); anulación y corrección con reversión de inventario; bitácora, auditoría y exportación a Excel; estaciones y parámetros.

La página **Acerca del demo** relaciona cada historia de usuario (HU-M0-001 a HU-M0-036) con la pantalla donde se ve.

## Cómo funciona

- Archivo único `index.html`, sin instalación ni servidor propio.
- Lo que cada persona cambie se guarda solo en **su navegador**. Para volver a los datos de ejemplo: **Acerca del demo › Reiniciar el demo**.
- Los registros de recepción, extrusión, perfilado y despacho son de ejemplo: los aportan los módulos M1 a M5.
- La página no se indexa en buscadores (`noindex`), pero cualquiera con el enlace puede abrirla.

## Propiedad

Desarrollado para ASLAN PLASTIK S.A.S. La marca, el logo y los textos de la política de datos (borrador v0.1, en revisión por ASLAN) son de ASLAN. No se autoriza su uso ni distribución fuera de este proyecto.
