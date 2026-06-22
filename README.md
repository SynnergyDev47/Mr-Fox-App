# Mr Fox

Mr Fox es una aplicación móvil nativa Android para administrar un gimnasio en dispositivos ligeros, incluyendo Android 12 Go. Se eligió **Java + Android SDK nativo** porque genera APKs pequeños, evita runtimes pesados y ofrece acceso directo a almacenamiento de imágenes, persistencia local y notificaciones.

## Funcionalidades

- Autenticación inicial por PIN de administrador.
- Pantalla de inicio con la marca Mr Fox y una imagen de zorro.
- Gestión de clientes con nombre, teléfono y foto editable desde archivos del dispositivo.
- Registro de pagos con fecha, monto y estado pagado/pendiente.
- Reversión rápida del estado de pago tocando el registro.
- Dashboard con ingresos recibidos, pendientes y desglose por cliente.
- Listado de pagos pendientes con fecha de vencimiento.
- Alertas en la app para cuotas vencidas o próximas a vencer.
- Navegación clara por pestañas: Clientes, Pagos, Dashboard, Pendientes y Alertas.

## Paleta

- Acento: `#6cace3`
- Fondo: `#ffffff`
- Texto principal: `#1b1b1b`

## Compilar APK

Con Android SDK instalado:

```bash
gradle :app:assembleDebug --no-daemon
```

El APK se generará en `app/build/outputs/apk/debug/app-debug.apk`.
