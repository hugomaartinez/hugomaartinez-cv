# CV Imprimible con Astro

Este es un CV diseñado para ser visualizado en la web y perfectamente imprimible en formato A4.

## 🚀 Cómo empezar

1. **Instalar dependencias:**

   ```bash
   bun install
   ```

2. **Iniciar el servidor de desarrollo:**

   ```bash
   bun run dev
   ```

3. **Compilar para producción:**
   ```bash
   bun run build
   ```

## 🛠️ Cómo mantenerlo

Para actualizar el contenido de tu CV, solo tienes que modificar el archivo:
`src/data/cv.ts`

He separado los datos de la estructura para que sea extremadamente fácil de mantener. No necesitas tocar el HTML ni el CSS para actualizar tu experiencia, educación o habilidades.

## 📄 Impresión

El proyecto incluye estilos específicos para impresión (`@media print`).

1. Haz clic en el botón flotante **"Imprimir / PDF"** (o `Ctrl + P`).
2. Para descargarlo, elige **"Guardar como PDF"** como destino.
3. En las opciones de impresión:
   - **Márgenes:** "Predeterminado" (los márgenes ya vienen definidos en el CSS; con "Ninguno" el texto toca el borde del papel).
   - **Escala:** "Predeterminado" / 100 %.
   - **Tamaño de papel:** A4.
   - **Encabezados y pies de página:** desactivados.

El PDF sale siempre con la paleta clara, aunque la web esté en modo oscuro, y los fondos de las etiquetas se imprimen aunque "Gráficos de fondo" esté desactivado.

## ✨ Características

- 🎨 **Estética Premium:** Tipografía moderna (Outfit & Inter) y diseño limpio.
- 📱 **Responsive:** Se adapta a móviles y tablets.
- 🖨️ **Optimizado para PDF:** Layout de dos columnas que se mantiene al imprimir.
- ⚡ **Astro 5:** Rendimiento ultrarrápido.
