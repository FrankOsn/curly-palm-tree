# 🏷️ Generador de Tags de Precio - Carnicería

Una herramienta web interactiva para crear y exportar etiquetas de precio (pricetags) profesionales para carnicerías y comercios.

## 🎯 Características

### Pricetag Simple
- **📊 Display dinámico** - Visualización en tiempo real del pricetag
- **💱 Control de precios** - Ingresa precio en enteros y centavos
- **📈 Gestión de rebajas** - Modo descuento con precio original personalizable
- **📋 Selector de unidades** - Elige entre Kg, CAJA o PZA
- **🎨 Control total de estilos**:
  - Tamaño individual de cada elemento (símbolo, número, centavos, unidad)
  - Color de texto y fondo personalizables
  - Contorno ajustable o sin borde
  - Banner de rebaja con colores y tamaños propios
  - Precio original con estilos independientes

### Pricetag Completo
- **📝 Secciones por línea** - Nombre, descripción y precio
- **🖼️ Tamaños en CM** - Plantillas predefinidas (10x8, 15x12, 20x15 cm) o personalizadas
- **🎨 Estilos por sección** - Color de texto y fondo global
- **👁️ Visibilidad controlada** - Mostrar/ocultar cada línea con checkboxes
- **⚙️ Controles avanzados** - Espaciado, alineación, tamaño de fuente por elemento

### Exportación
- **📸 PNG de ultra alta calidad** - Escala 6x para máxima resolución
- **🎯 Tamaño fijo** - No se ve afectado por el tamaño de la ventana del navegador
- **📋 Copiar al portapapeles** - Un clic para usar en PPT, Word, etc.

## 🚀 Cómo usar

1. Accede a la herramienta: [https://frankosn.github.io/curly-palm-tree/](https://frankosn.github.io/curly-palm-tree/)
2. Ingresa el precio (enteros y centavos)
3. Selecciona la unidad de medida (Kg, CAJA, PZA)
4. Activa el modo "¿Es Rebaja?" si aplica y añade precio anterior
5. Haz clic en **"📋 Copiar Pricetag a Portapapeles"**
6. Pega la imagen en tu editor favorito (Word, Excel, Canva, etc.)

## 💻 Tecnologías

- **HTML5** - Estructura
- **CSS3** - Estilos modernos (Flexbox, Gradientes)
- **JavaScript** - Lógica interactiva
- **html2canvas** - Captura y exportación de imágenes PNG
- **Fuente Supermercado One** - Tipografía personalizada de Google Fonts

## 📝 Especificaciones del Pricetag

### Pricetag Simple
- **Dimensiones**: 400px de ancho, altura auto
- **Colores base**: Negro (#000000) con detalles rojo rebaja (#d32f2f)
- **Tipografía**: Supermercado One
- **Exportación**: PNG de ultra alta calidad (6x escala) con fondo transparente

### Pricetag Completo
- **Tamaños**: Desde 10x8cm hasta 20x15cm (o personalizados)
- **Tipografía**: Supermercado One (precio), Roboto (nombre), Lato (descripción)
- **Exportación**: PNG de ultra alta calidad (6x escala) con fondo transparente

## 🛠️ Desarrollo local

```bash
# Clonar repositorio
git clone https://github.com/FrankOsn/curly-palm-tree.git

# Abrir en navegador (no requiere servidor)
open index.html
```

## 📦 Estructura del proyecto

```
curly-palm-tree/
├── index.html          # Archivo principal (HTML + CSS + JS)
└── README.md           # Este archivo
```

## 🔄 Actualizaciones recientes

- ✨ **v1.1.0** - Controles completos de estilos
  - Tamaño individual de cada elemento en pricetag simple
  - Control de color de texto y fondo en ambos pricetags
  - Estilos completamente personalizables para rebajas
  - Banner de rebaja con colores propios
  - Precio original con estilos independientes
  - Contorno ajustable o sin borde
  - Mejora de calidad PNG a 6x escala
  - Secciones colapsables en formularios
  - Checkboxes para mostrar/ocultar líneas

- ✨ v1.0 - Lanzamiento inicial
  - Selector de unidades (Kg, CAJA, PZA)
  - Función de exportación a PNG
  - Modo rebaja con precio original
  - Interfaz responsive

## 📋 Roadmap

- [ ] Descarga directa como PNG
- [ ] Presets de productos favoritos
- [ ] Historial de precios recientes
- [ ] Soporte para múltiples monedas
- [ ] Tema oscuro/claro

## 📄 Licencia

Este proyecto está disponible bajo licencia MIT.

## 👤 Autores

- **Francisco Osnaya** - Concepto, diseño y especificaciones
- **GitHub Copilot** - Desarrollo e implementación

---

**¿Preguntas o sugerencias?** Abre un [issue](https://github.com/FrankOsn/curly-palm-tree/issues) en el repositorio.
