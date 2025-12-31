# BioCongreso.com 🧬

Sitio web oficial de BioCongreso Internacional - El evento más importante de Biodesprogramación a nivel mundial.

## 🎨 Colores Institucionales

- **Azul Oscuro Principal**: `#1a2332`
- **Azul Medio**: `#2a3f5f`
- **Amarillo/Dorado (Acento)**: `#FFC107`
- **Verde (WhatsApp)**: `#25D366`

## 📁 Estructura del Proyecto

```
biocongreso.com/
├── header-web-biocongreso.html          # Header del sitio web
├── footer-web-biocongreso.html          # Footer con shortcode Elementor
├── hero-biocongreso-2026.html           # Hero principal con fechas 2026
├── sobre-nosotros.html                  # Página Sobre Nosotros
├── ediciones-anteriores.html            # Página Ediciones Anteriores
├── contacto.html                        # Página de Contacto
└── README.md                            # Este archivo
```

## 🚀 Componentes del Sitio Web

### 1. Header Web
**Archivo**: `header-web-biocongreso.html`

Header sticky para el sitio web con navegación completa.

**Características:**
- Logo BioCongreso con emoji 🧬
- Navegación: Inicio, Sobre Nosotros, Ediciones, Contacto
- Menú hamburguesa responsive para móvil
- Sticky header (se mantiene fijo al hacer scroll)
- Gradiente institucional (#1a2332 → #2a3f5f)

**Uso en Elementor:**
1. Agregar widget HTML en el header
2. Copiar contenido completo del archivo
3. Pegar en el widget

### 2. Footer Web
**Archivo**: `footer-web-biocongreso.html`

Footer completo con 4 secciones y shortcode de Elementor.

**Características:**
- **Sección 1**: Sobre BioCongreso + Redes Sociales
- **Sección 2**: Enlaces Rápidos
- **Sección 3**: Acceso (Panel, Registro, Login)
- **Sección 4**: Contacto (Email, Teléfono, WhatsApp)
- **Shortcode Elementor**: `[elementor-template id="625"]`
- Copyright y créditos

**Redes Sociales:**
- Facebook: https://facebook.com/biocongreso
- Instagram: https://instagram.com/biocongreso
- YouTube: https://youtube.com/biocongreso
- WhatsApp: https://whatsapp.com/channel/0029VbB4sIw9mrGZcf6T0Z0F

### 3. Hero BioCongreso 2026
**Archivo**: `hero-biocongreso-2026.html`

Hero principal con información de los eventos 2026.

**Características:**
- Título: "BioCongreso Internacional 2026"
- **6º BioCongreso**: Bogotá, Colombia - Sábado 30 Mayo 2026 🇨🇴
- **7º BioCongreso**: Guadalajara, México - Sábado 21 Noviembre 2026 🇲🇽
- 3 pilares: Transformación, Sanación, Consciencia
- Botón CTA "Mantente Informado"
- Animaciones flotantes con burbujas doradas
- Sin border-radius (bordes rectos para integración)
- Mismo gradiente que header/footer

### 4. Sobre Nosotros
**Archivo**: `sobre-nosotros.html`

Página institucional con información de BioCongreso.

**Contenido:**
- ¿Qué es BioCongreso?
- Nuestra Misión
- Nuestros Valores (4 cards):
  - 🧠 Transformación
  - 💫 Sanación
  - 🌟 Consciencia
  - 🤝 Comunidad

**Diseño:**
- Fondo blanco con cards grises (#f9fafb)
- Borde izquierdo dorado en bloques de contenido
- Grid responsive de valores

### 5. Ediciones Anteriores
**Archivo**: `ediciones-anteriores.html`

Histórico de todas las ediciones de BioCongreso.

**Contenido:**
- **5º BioCongreso** (2025): Sanar Emocional - Guadalajara
- **4º BioCongreso** (2024): Guadalajara
- **3º BioCongreso** (2023): Guadalajara
- **2º BioCongreso** (2022): Guadalajara
- **1º BioCongreso** (2021): Guadalajara

**Diseño:**
- Cards con gradiente institucional
- Número de edición grande y destacado
- Badges especiales para primera y última edición
- Hover effect con elevación y sombra dorada

### 6. Contacto
**Archivo**: `contacto.html`

Página de contacto con múltiples canales de comunicación.

**Contenido:**
- 📧 **Email**: info@biocongreso.com
- 📱 **Teléfono**: +52 333 405 4655
- 🌐 **Redes Sociales**: Facebook, Instagram, YouTube
- 💬 **Canal WhatsApp**: Comunidad BioCongreso
- 📍 **Ubicación**: Guadalajara, Jalisco, México

**Diseño:**
- Grid de cards de contacto
- Card especial de WhatsApp con gradiente verde
- Placeholder para mapa de Google Maps
- Hover effects en todas las cards

## 🔗 URLs Importantes

### Sitio Web
- **Principal**: https://biocongreso.com
- **Sobre Nosotros**: https://biocongreso.com/sobre-nosotros
- **Ediciones**: https://biocongreso.com/ediciones-anteriores
- **Contacto**: https://biocongreso.com/contacto

### Panel de Usuario
- **Dashboard**: https://panel.biocongreso.com
- **Login**: https://panel.biocongreso.com
- **Registro**: https://panel.biocongreso.com/registro
- **Usuario**: https://panel.biocongreso.com/usuario

### Redes Sociales
- **Facebook**: https://facebook.com/biocongreso
- **Instagram**: https://instagram.com/biocongreso
- **YouTube**: https://youtube.com/biocongreso
- **WhatsApp Canal**: https://whatsapp.com/channel/0029VbB4sIw9mrGZcf6T0Z0F

### Soporte
- **WhatsApp**: https://wa.me/5213334054655
- **Email**: info@biocongreso.com

## 📝 Uso en WordPress/Elementor

### Estructura de Página Recomendada

```
┌─────────────────────────────────────┐
│     Header (header-web-biocongreso) │
├─────────────────────────────────────┤
│     Hero (hero-biocongreso-2026)    │
├─────────────────────────────────────┤
│     Contenido de la Página          │
│     (sobre-nosotros / ediciones /   │
│      contacto)                      │
├─────────────────────────────────────┤
│     Footer (footer-web-biocongreso) │
└─────────────────────────────────────┘
```

### Método de Integración

1. **Crear página en WordPress**
2. **Editar con Elementor**
3. **Agregar widgets HTML** para cada sección
4. **Copiar y pegar** el contenido de cada archivo HTML
5. **Guardar y publicar**

### Notas de Integración

- ✅ **Sin padding externo**: Los componentes no tienen padding externo
- ✅ **Colores consistentes**: Todos usan la paleta institucional
- ✅ **Responsive**: Diseño adaptable a todos los dispositivos
- ✅ **Font Awesome**: Algunos iconos usan emojis, otros Font Awesome
- ✅ **Shortcode Elementor**: Footer incluye `[elementor-template id="625"]`

## 🎯 Eventos 2026

### 6º BioCongreso
- **Ubicación**: Bogotá, Colombia 🇨🇴
- **Fecha**: Sábado 30 de Mayo de 2026
- **Estado**: Próximamente

### 7º BioCongreso
- **Ubicación**: Guadalajara, México 🇲🇽
- **Fecha**: Sábado 21 de Noviembre de 2026
- **Estado**: Próximamente

## 📱 Compatibilidad

- ✅ WordPress 5.0+
- ✅ Elementor 3.0+
- ✅ Chrome, Firefox, Safari, Edge
- ✅ Responsive (Desktop, Tablet, Mobile)
- ✅ Font Awesome 6.4.0+ (opcional)

## 🎨 Características de Diseño

### Paleta de Colores
- Gradiente principal: `linear-gradient(135deg, #1a2332 0%, #2a3f5f 100%)`
- Acento dorado: `#FFC107`
- Hover dorado claro: `#FFD54F`
- WhatsApp verde: `#25D366`

### Tipografía
- Font Family: `-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`
- Títulos: 900 weight
- Subtítulos: 700 weight
- Texto: 400-600 weight

### Efectos
- Hover: `translateY(-5px)` + sombra
- Transiciones: `all 0.3s ease`
- Sombras: `rgba(255, 193, 7, 0.3)`
- Border radius: 16-20px

## 📄 Archivos del Proyecto

| Archivo | Propósito | Tipo |
|---------|-----------|------|
| `header-web-biocongreso.html` | Header navegación | Componente |
| `footer-web-biocongreso.html` | Footer + shortcode | Componente |
| `hero-biocongreso-2026.html` | Hero eventos 2026 | Sección |
| `sobre-nosotros.html` | Página institucional | Página |
| `ediciones-anteriores.html` | Histórico eventos | Página |
| `contacto.html` | Información contacto | Página |
| `README.md` | Documentación | Docs |

## 🛠️ Personalización

### Cambiar Fechas de Eventos

En `hero-biocongreso-2026.html`:
```html
<!-- 6to BioCongreso -->
<div class="event-date">📅 Sábado 30 Mayo 2026</div>

<!-- 7mo BioCongreso -->
<div class="event-date">📅 Sábado 21 Noviembre 2026</div>
```

### Cambiar URLs de Redes Sociales

En `footer-web-biocongreso.html` y `contacto.html`:
```html
<a href="https://facebook.com/biocongreso">Facebook</a>
<a href="https://instagram.com/biocongreso">Instagram</a>
<a href="https://youtube.com/biocongreso">YouTube</a>
```

### Cambiar Información de Contacto

En `contacto.html`:
```html
<a href="mailto:info@biocongreso.com">Email</a>
<a href="tel:+5213334054655">Teléfono</a>
```

### Cambiar Shortcode de Elementor

En `footer-web-biocongreso.html`:
```html
[elementor-template id="625"]
```

## 📞 Soporte

Para soporte técnico o consultas:
- **Email**: info@biocongreso.com
- **WhatsApp**: +52 333 405 4655
- **Canal WhatsApp**: https://whatsapp.com/channel/0029VbB4sIw9mrGZcf6T0Z0F

---

**BioCongreso Internacional** © 2025 - Evento Anual de Biodesprogramación

Desarrollado por [Instituto de Biodesprogramación](https://fernandosanchezinstituto.com.mx)
