# 🥖 Carta Digital y Catálogo con Pedidos por WhatsApp

Aplicación web ligera y ultrarrápida (100 % estática en un único archivo `index.html`) diseñada para bares, bocaterías, cafeterías, tiendas de barrio y comercios locales que desean recibir pedidos directamente en su WhatsApp **sin pagar comisiones ni cuotas mensuales**.

---

## ✨ Características principales

* **Catálogo interactivo estilo app móvil:** Navegación por categorías, buscador instantáneo en tiempo real y filtros rápidos (*Sin Gluten*, *Vegetariano*, *Top Ventas*).
* **Carrito inteligente y cálculo automático:** Suma unidades, calcula importes al instante y permite añadir notas personalizadas por pedido.
* **Pedidos directos por WhatsApp (0 % comisiones):** Soporta modalidad de **Recogida en local**, **Consumo en mesa** (indicando número de mesa) o **Entrega a domicilio**, generando el mensaje formateado y listo para enviar.
* **Modo Dueño integrado (`PIN: 1234`):** Panel de administración accesible desde el propio navegador para:
  * Cambiar el nombre del negocio y el teléfono de WhatsApp de recepción.
  * Marcar platos o productos como **Agotados** con un solo toque.
  * Editar precios o añadir nuevos productos al catálogo.
* **Generador de Código QR listo para imprimir:** Crea automáticamente el código QR de la carta para colocarlo en mesas, escaparates o mostradores.
* **Sin costes de servidor:** Funciona de forma autónoma sin bases de datos externas, ideal para desplegar gratis en **GitHub Pages**, **Netlify** o **Vercel**.

---

## 🚀 Despliegue rápido

1. Sube el archivo `index.html` a un repositorio de GitHub.
2. Conecta el repositorio a **Netlify** o activa **GitHub Pages** desde `Settings > Pages`.
3. Abre el enlace generado en tu móvil y pulsa **⚙️ Modo Dueño** en el pie de página (PIN por defecto: `1234`) para personalizar los datos del local.

---

## 🛠️ Personalización

Puedes modificar los valores iniciales del negocio, categorías y productos directamente dentro de las constantes `DEFAULT_BIZ`, `DEFAULT_CATEGORIES` y `DEFAULT_PRODUCTS` en el bloque `<script>` de `index.html`.
