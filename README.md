# NagiStream - Plataforma de Servicios Digitales

Una página web moderna y profesional para la venta de servicios digitales premium como Netflix, Spotify, Canva Pro, IPTV y más. Diseñada con un enfoque en la usabilidad y la confianza del usuario, similar a plataformas como KiosTeam.

## 🎨 Características del Diseño

### Paleta de Colores
- **Fondo principal**: Tonos oscuros (negros/grises oscuros)
- **Texto**: Blancos y grises claros para contraste
- **Acentos**: Verde vibrante (#00ff88) para elementos interactivos
- **Gradientes**: Efectos sutiles en botones y elementos destacados

### Tipografía
- **Fuente principal**: Poppins (sans-serif moderna)
- **Jerarquía visual**: Diferentes pesos y tamaños para títulos, subtítulos y texto
- **Legibilidad**: Optimizada para todos los dispositivos

## 🚀 Funcionalidades

### Frontend
- ✅ **Diseño Responsivo**: Adaptable a móviles, tablets y escritorio
- ✅ **Navegación Móvil**: Menú hamburguesa para dispositivos móviles
- ✅ **Animaciones**: Efectos de scroll y hover suaves
- ✅ **Contadores Animados**: Estadísticas con animación de números
- ✅ **Smooth Scroll**: Navegación suave entre secciones
- ✅ **Efectos Parallax**: Animaciones sutiles en el hero section
- ✅ **Tooltips**: Información adicional en precios
- ✅ **Efecto de Escritura**: Animación en el título principal

### Secciones Implementadas
1. **Header**: Navegación fija con logo y menú
2. **Hero Section**: Banner principal con llamadas a la acción
3. **Servicios**: Grid de tarjetas con precios mayorista/minorista
4. **Cómo Funciona**: Proceso paso a paso
5. **Precios**: Planes de precios con características
6. **Comunidad**: Estadísticas y canales de comunicación
7. **Footer**: Enlaces y información de contacto

## 📁 Estructura del Proyecto

```
NagiStream/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
└── README.md           # Documentación
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: 
  - Grid y Flexbox para layouts
  - Variables CSS para consistencia
  - Media queries para responsividad
  - Animaciones y transiciones
- **JavaScript ES6+**:
  - Intersection Observer API
  - Event listeners optimizados
  - Funciones utilitarias
  - Debouncing para rendimiento

## 🚀 Instalación y Uso

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, para desarrollo)

### Instalación Rápida
1. Descarga o clona el proyecto
2. Abre `index.html` en tu navegador
3. ¡Listo! La página está funcionando

### Desarrollo Local
```bash
# Si tienes Python instalado
python -m http.server 8000

# Si tienes Node.js instalado
npx serve .

# Si tienes PHP instalado
php -S localhost:8000
```

Luego visita `http://localhost:8000` en tu navegador.

## 📱 Responsividad

La página está optimizada para:
- **Móviles**: 320px - 768px
- **Tablets**: 768px - 1024px
- **Escritorio**: 1024px+

### Breakpoints Implementados
- `@media (max-width: 768px)`: Navegación móvil, layouts de una columna
- `@media (max-width: 480px)`: Ajustes para pantallas muy pequeñas

## 🎯 Servicios Incluidos

### Catálogo de Servicios
- **Netflix Premium**: 4K, múltiples pantallas
- **Spotify Premium**: Sin anuncios, descarga offline
- **Canva Pro**: Herramientas profesionales de diseño
- **IPTV Premium**: Miles de canales en vivo
- **YouTube Premium**: Sin anuncios, YouTube Music
- **Apple One**: Suite completa de servicios Apple

### Precios
- **Mayorista**: Precios especiales para distribuidores
- **Minorista**: Precios para clientes finales
- **Transparencia**: Ambos precios visibles en cada servicio

## 🔧 Personalización

### Colores
Modifica las variables CSS en `styles.css`:
```css
:root {
    --color-primary: #00ff88;        /* Color principal */
    --color-primary-dark: #00cc6a;   /* Color principal oscuro */
    --color-dark: #0a0a0a;           /* Fondo principal */
    --color-secondary: #1a1a1a;      /* Fondo secundario */
    /* ... más variables */
}
```

### Contenido
- Edita `index.html` para cambiar textos y estructura
- Modifica `styles.css` para ajustar estilos
- Personaliza `script.js` para funcionalidades específicas

### Agregar Nuevos Servicios
1. Copia una tarjeta de servicio existente en `index.html`
2. Cambia el ícono, título, descripción y precios
3. Ajusta los estilos si es necesario

## 🌟 Características Avanzadas

### Optimización de Rendimiento
- **Lazy Loading**: Para imágenes (preparado)
- **Debouncing**: En eventos de scroll
- **Intersection Observer**: Para animaciones eficientes
- **CSS Optimizado**: Variables y reutilización de estilos

### Accesibilidad
- **Semántica HTML**: Estructura correcta
- **Contraste**: Colores accesibles
- **Navegación por teclado**: Enlaces y botones accesibles
- **Alt text**: Preparado para imágenes

### SEO Preparado
- **Meta tags**: Título y descripción
- **Estructura semántica**: Headers y secciones
- **Enlaces internos**: Navegación optimizada

## 🔮 Próximas Funcionalidades

### Backend (Para implementación futura)
- Sistema de autenticación de usuarios
- Panel de control para distribuidores
- Gestión de pedidos y pagos
- Base de datos de servicios y precios
- API REST para integraciones

### Frontend Adicional
- Carrito de compras
- Sistema de reseñas
- Chat en vivo
- Notificaciones push
- Modo oscuro/claro

## 📞 Soporte y Comunidad

### Canales de Comunicación
- **WhatsApp Clientes**: Soporte técnico
- **WhatsApp Vendedores**: Comunidad de distribuidores
- **Discord**: Comunidad general

### Estadísticas de Comunidad
- 5,000+ usuarios activos
- 1,200+ distribuidores
- 50,000+ servicios vendidos

## 📄 Licencia

Este proyecto está disponible para uso personal y comercial. Se recomienda personalizar el contenido y branding según las necesidades específicas.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:
1. Fork el proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## 📧 Contacto

- **Email**: info@nagistream.com
- **Teléfono**: +1 (555) 123-4567
- **Ubicación**: Ciudad, País

---

**Desarrollado con ❤️ para la comunidad de servicios digitales** 