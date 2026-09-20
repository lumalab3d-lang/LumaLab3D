# LUMA LAB 3D

App de gestión para LUMA LAB 3D: calculadora de precios de impresión 3D, perfiles de impresora con recuperación de costo, inventario de insumos y productos con QR de precio, y registro de ventas.

Es una app de una sola página (index.html), sin servidor ni base de datos: cada dispositivo guarda sus propios datos en la memoria de su navegador (localStorage).

## Publicar en Vercel

1. Sube esta carpeta a un repositorio de GitHub.
2. En vercel.com → "Add New" → "Project" → importa ese repositorio.
3. Vercel detecta que es un sitio estático (no requiere Build Command ni Output Directory especiales) y lo publica.
4. Cada cambio que subas a GitHub (git push) se vuelve a publicar solo en Vercel.
