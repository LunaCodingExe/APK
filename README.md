# Mi Finanzas — app web instalable para Android

## Funciones
- Registrar ingresos y gastos en MXN.
- Balance total y resumen del mes.
- Gráfica de gastos por categoría y periodos semana/mes/año/todo.
- Crear, editar y eliminar movimientos.
- Buscar y filtrar movimientos.
- Informes y exportación/importación de respaldo JSON.
- Interfaz adaptada a móvil y modo offline después de la primera carga.
- Los datos se guardan en el almacenamiento local del navegador; no se conectan cuentas bancarias.

## Instalar en Android
Para que Android ofrezca la instalación PWA, los archivos deben publicarse en un sitio HTTPS (por ejemplo, un hosting estático). Después:
1. Abre la dirección publicada en Chrome para Android.
2. Abre el menú ⋮ y elige **Instalar aplicación** o **Añadir a pantalla de inicio**.
3. Confirma. Aparecerá como una app en tu teléfono.

`index.html` permite probar la interfaz, pero abrirlo como archivo local no habilita todas las funciones PWA. Este proyecto no es todavía un APK nativo; es una PWA instalable.

## Privacidad y respaldos
No introduzcas contraseñas bancarias. Los datos se almacenan en el navegador de ese dispositivo. En Ajustes puedes exportar/importar un respaldo JSON. Borrar datos del navegador puede borrar tus movimientos.
