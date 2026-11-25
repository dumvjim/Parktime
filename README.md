# ParkTime 4.0 — demo web/PWA

Tarifas simuladas de $70–$100 MXN por hora. Código y QR de reserva escaneable, generado localmente. El QR contiene solo el código, no datos personales. Las reservas se guardan en el navegador; el panel Business valida únicamente las del mismo navegador. No hay pagos, servidor ni inventario comercial real.

## GitHub Pages
1. Crear repositorio público `parktime` en https://github.com/new.
2. Descomprimir el ZIP. Subir todos los archivos y la carpeta icons a la raíz del repositorio (no el ZIP ni la carpeta contenedora).
3. Commit changes a main.
4. Settings > Pages > Build and deployment > Deploy from a branch > main > / (root) > Save.
5. Abrir el enlace que muestra Pages. En Android, menú Chrome > Instalar aplicación; en iPhone, Safari > Compartir > Añadir a pantalla de inicio.

## Prueba
Reservar con datos ficticios, comprobar el importe, escanear el QR con otro celular y copiar el código al panel Business en el navegador donde se creó la reserva. Validar; un segundo intento se rechaza. El mapa requiere conexión.
