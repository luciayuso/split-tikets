# Ticket Splitter OCR

Aplicación web local para repartir tickets entre varias personas.

## Cómo usar

1. Abre `index.html` en el navegador.
2. Sube una imagen del ticket.
3. Pulsa **Leer ticket con OCR**.
4. Revisa/corrige los artículos detectados.
5. Añade personas y asigna cada artículo a una o varias.
6. Exporta a CSV, Excel, JSON o PDF.

## Importante

- No hay base de datos.
- Los datos se guardan solo en memoria.
- Al refrescar la página, se eliminan.
- El OCR usa Tesseract.js desde CDN, por lo que necesitas conexión a internet para que funcione.
- Si no hay internet, puedes pegar el texto manualmente en “Texto bruto detectado” y pulsar “Parsear texto”.
