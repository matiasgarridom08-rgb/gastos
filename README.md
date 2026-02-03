# 📊 Analizador de Cartola Bancaria | Virtual Keys

Aplicación web para analizar y categorizar automáticamente los movimientos de tu cartola bancaria del Banco Santander Chile.

![Virtual Keys](https://virtualkeys.store/cdn/shop/files/VK_logo_2.png?v=1699564158&width=200)

## ✨ Características

- **📤 Carga fácil**: Arrastra y suelta tu archivo `.txt` de cartola
- **🏷️ Categorización automática**: Clasifica transacciones basándose en palabras clave
- **✏️ Categorías editables**: Agrega, modifica o elimina categorías y reglas
- **📈 Dashboard visual**: Gráficos de distribución de gastos e ingresos
- **🔍 Filtros**: Filtra por tipo (ingreso/gasto) y categoría
- **💯 100% privado**: Todo se procesa en tu navegador, sin enviar datos a ningún servidor

## 🚀 Uso

### Opción 1: Usar directamente
1. Descarga el archivo `index.html`
2. Ábrelo en tu navegador
3. Arrastra tu archivo de cartola del Santander

### Opción 2: GitHub Pages
1. Haz fork de este repositorio
2. Ve a Settings > Pages
3. Selecciona "Deploy from a branch" > main > / (root)
4. Tu app estará disponible en `https://tu-usuario.github.io/cartola-analyzer`

## 📁 Formato de archivo soportado

El archivo debe ser el `.txt` de "Cartola Movimientos" descargado desde el Banco Santander Chile (Office Banking).

## 🏷️ Categorías predefinidas

### Ingresos
| Categoría | Palabras clave |
|-----------|----------------|
| Ventas | FLOW S A, Transf. FLOW |
| Otros Ingresos | RADAR CHILE |

### Gastos
| Categoría | Palabras clave |
|-----------|----------------|
| Publicidad | FACEBK, FACEBOOK |
| Suscripciones | CLAUDE.AI, CHATGPT, SHOPIFY, KLAVIYO, AIRTABLE, HEYGEN, ELEVENLABS, MIDJOURNEY, FREEPIK, REAMAZE, GOOGLE Workspace, CapCut |
| Proveedores | Alibaba, WESTERN UNION, SKR*Skrill, HYPERREALS |
| Impuestos | S.I.I., T.G.R., PAGO EN LINEA |
| Créditos | Cuota Crédito, Pago Cuota |
| Comisiones Bancarias | MANTENCION PLAN, COM.MANTENCION |
| Retiro Socio | Transf a Matias GAR, 0215719960 |
| Honorarios | Transf a Jhosep, Transf a Carolina, Transf a Isabel, Impulsah |
| Otros Gastos | MERCADOPAGO, COPEC, Cajero Automatico, etc. |

## 🛠️ Personalización

Puedes modificar las categorías directamente en la pestaña "⚙️ Categorías":

1. **Agregar palabra clave**: Escribe en el campo de texto de cada categoría y presiona "+"
2. **Eliminar palabra clave**: Haz clic en la "✕" junto a cada palabra
3. **Crear nueva categoría**: Usa el formulario al final de la página

## 📱 Tecnologías

- HTML5 / CSS3 / JavaScript (Vanilla)
- Chart.js para gráficos
- Google Fonts (Plus Jakarta Sans)
- Sin dependencias de backend

## 🔒 Privacidad

Esta aplicación:
- ✅ Funciona 100% en tu navegador
- ✅ No envía datos a ningún servidor
- ✅ No almacena información
- ✅ No requiere registro

## 📄 Licencia

MIT License - Desarrollado para Virtual Keys SpA

---

**Virtual Keys** - Licencias 100% Originales  
🌐 [virtualkeys.store](https://virtualkeys.store)
