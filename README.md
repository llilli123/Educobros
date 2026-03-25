# Educobros

Educobros es un sistema web de gestión de cobros escolares desarrollado con **HTML, CSS y JavaScript**.  
Permite visualizar estudiantes, registrar pagos, consultar historial y guardar la información localmente en el navegador mediante **localStorage**.

## Funcionalidades

- Panel de control con:
  - Total de estudiantes
  - Total recaudado
  - Pendientes
  - Mora
- Tabla de estudiantes y balances
- Buscador de estudiantes
- Registro de pagos mediante formulario
- Historial de pagos dinámico
- Eliminación de pagos
- Persistencia de datos con `localStorage`
- Pantalla de éxito después de registrar un pago
- Favicon y logo personalizados

## Tecnologías usadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **localStorage**

## Estructura básica

- `index.html` → página principal del sistema
- `exito.html` → página de confirmación de pago
- `images/` → carpeta de imágenes, logo, favicon y confirmación visual

## Cómo funciona

1. El usuario selecciona un estudiante.
2. Completa los datos del pago.
3. El sistema valida la información.
4. El pago se guarda en `localStorage`.
5. Se actualizan el historial y el dashboard.
6. Se muestra una pantalla de éxito.
7. Después de 3 segundos, el sistema regresa automáticamente al inicio.

## Personalización realizada

Como parte del toque personal del proyecto, se agregaron:

- Logo en el encabezado
- Favicon del sistema
- Pantalla de éxito personalizada
- Buscador de estudiantes
- Estilo visual mejorado

## Autor

Proyecto desarrollado por **Jorge Cabrera**.