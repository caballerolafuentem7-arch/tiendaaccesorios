# AURELIA - Tienda Online de Joyería con Carrito y Pago QR

## Estructura de carpetas
- `index.html` -> Estructura principal de la tienda, catálogo, carrito lateral y modal de pago.
- `css/styles.css` -> Estilos personalizados, animaciones y barra de desplazamiento.
- `js/app.js` -> Lógica del catálogo (precios en Bolivianos Bs), carrito, imagen QR y envío por WhatsApp.
- `img/` -> Carpeta para colocar tu imagen de código QR (`mi-qr.png`).

## Cómo subir tu imagen QR y configurar tu WhatsApp por código
1. Copia la imagen de tu QR bancario dentro de la carpeta `img/` y nómbrala `mi-qr.png` (quedará como `img/mi-qr.png`).
2. Si tu archivo tiene otro nombre o extensión (por ejemplo `qr-banco.jpg`), abre `js/app.js` y cambia la línea:
   `defaultQRImage: "./img/qr-banco.jpg"` (y también el `src` en `index.html`).
3. En `js/app.js`, edita `whatsappNumber: "59170000000"` con tu número real.
