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

1. Haz clic en el botón flotante **"Imprimir CV"**.
2. Asegúrate de que en las opciones de impresión:
   - Los **márgenes** estén en "Ninguno" o "Predeterminado".
   - Los **gráficos de fondo** estén activados (opcional, para ver los colores y badges).
   - El tamaño de papel sea **A4**.

## ✨ Características

- 🎨 **Estética Premium:** Tipografía moderna (Outfit & Inter) y diseño limpio.
- 📱 **Responsive:** Se adapta a móviles y tablets.
- 🖨️ **Optimizado para PDF:** Layout de dos columnas que se mantiene al imprimir.
- ⚡ **Astro 5:** Rendimiento ultrarrápido.
