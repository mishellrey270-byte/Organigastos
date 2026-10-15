# Organigastos — primera versión

## Qué incluye
- Inicio con saldo, ingresos, gastos y últimos movimientos.
- Registro manual de gastos, ingresos y apartados de ahorro.
- Historial con filtros y opción de eliminar movimientos.
- Presupuesto mensual y resumen de gastos por categoría.
- Metas de ahorro editables.
- Recordatorios de pagos recurrentes (no se registran como pagados automáticamente).
- Exportar e importar respaldo JSON.
- Diseño adaptable a móvil y preparado como PWA para instalarse desde Safari.

## Importante sobre el saldo
La app inicia con Q1,022.16 como saldo inicial porque fue el último saldo real reportado. Los movimientos que se registren después se suman o restan a ese saldo. Para que no se dupliquen gastos, no precargué los movimientos históricos: cambiá el saldo inicial o importá/registrá tu historial según cómo querás empezar.

## Cómo probarla en computadora
Abrí `index.html` en el navegador. Para probar la instalación PWA y el modo sin conexión, servila mediante HTTPS o un servidor local.

## Cómo instalarla en iPhone
Para que Safari permita “Añadir a pantalla de inicio”, publicá estos archivos en una URL HTTPS (por ejemplo, GitHub Pages):
1. Creá un repositorio en GitHub y subí `index.html`, `manifest.json` y `sw.js`.
2. En el repositorio, abrí Settings → Pages y publicá desde la rama principal.
3. Abrí la URL publicada en Safari en tu iPhone.
4. Tocá Compartir → Añadir a pantalla de inicio.

## Datos y privacidad
Los datos se guardan en el almacenamiento local del navegador. No se conectan a Banrural ni se sincronizan automáticamente entre dispositivos. Exportá respaldos periódicamente. Borrar los datos del navegador puede eliminar el registro local.

## Próximos pasos recomendados
- Mejorar la experiencia de edición de movimientos.
- Agregar un calendario mensual y gráficos más completos.
- Añadir sincronización segura entre iPhone y computadora si se desea.
- Personalizar categorías, colores e icono de la app.
