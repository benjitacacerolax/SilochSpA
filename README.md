# SILOCH SpA - Sitio Web Profesional

## 📁 Archivos del Proyecto

- **index.html** - Página principal
- **sobre-nosotros.html** - Página "Sobre Nosotros"
- **servicios.html** - Página de servicios detallados
- **contacto.html** - Página de contacto con formulario
- **styles.css** - Estilos completos del sitio
- **script.js** - Funcionalidad interactiva

## 🚀 Características

### ✨ Diseño Profesional
- Diseño industrial moderno inspirado en construcción y logística
- Paleta de colores: Naranja (#D97706) como color primario, gris oscuro (#1E293B) como secundario
- Tipografía distintiva: Bebas Neue para títulos, Work Sans para texto
- Completamente responsive (móvil, tablet, desktop)

### 🎯 Funcionalidades
- Navegación sticky con menú hamburguesa en móvil
- Animaciones suaves al hacer scroll
- Botón flotante de WhatsApp
- Formulario de contacto funcional
- Smooth scroll entre secciones
- Efectos hover en todos los elementos interactivos

### 📱 Secciones Incluidas

**Página Principal (index.html):**
- Hero section impactante
- Resumen de 5 servicios principales
- Sección "Por qué elegirnos" con 6 beneficios
- Zona de cobertura (Valparaíso, Villa Alemana)
- Call-to-action para cotización

**Sobre Nosotros (sobre-nosotros.html):**
- Presentación de la empresa
- Qué hacemos (4 áreas principales)
- Cómo trabajamos (4 valores)
- Enfoque empresarial

**Servicios (servicios.html):**
- 5 servicios detallados con información completa
- Construcción y servicios especializados
- Transporte de carga
- Venta de materiales
- Venta por internet
- Servicios de publicidad

**Contacto (contacto.html):**
- Formulario de contacto completo
- Información de ubicación
- Horarios de atención
- Botón directo a WhatsApp

## 🛠️ Personalización

### Cambiar el número de WhatsApp
Buscar y reemplazar `56912345678` con tu número real en:
- Todos los archivos .html (botón flotante)
- contacto.html (botón de contacto rápido)

Formato: `56` + código de área + número (sin espacios ni guiones)

### Modificar colores
En `styles.css`, líneas 6-11, puedes cambiar:
```css
--primary: #D97706;        /* Color principal (naranja)
--primary-dark: #B45309;   /* Naranja oscuro */
--secondary: #1E293B;      /* Gris oscuro */
--accent: #F59E0B;         /* Naranja claro */
```

### Agregar tu logo
1. Guarda tu logo como `logo.png` en la misma carpeta
2. En todos los archivos .html, reemplaza:
```html
<div class="logo">
    <a href="index.html">
        <span class="logo-main">SILOCH</span>
        <span class="logo-sub">SpA</span>
    </a>
</div>
```

Con:
```html
<div class="logo">
    <a href="index.html">
        <img src="logo.png" alt="SILOCH SpA" style="height: 50px;">
    </a>
</div>
```

### Configurar el formulario de contacto
El formulario actualmente muestra un mensaje de éxito simulado. Para conectarlo a un backend real:

1. En `script.js`, línea 113, descomenta el código de producción
2. Reemplaza `YOUR_BACKEND_ENDPOINT` con tu endpoint real
3. Asegúrate de que tu backend acepte datos JSON con estos campos:
   - nombre
   - email
   - telefono
   - servicio
   - mensaje

### Agregar Google Analytics
Antes de `</head>` en cada archivo HTML, agrega:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TU-ID-AQUI"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TU-ID-AQUI');
</script>
```

## 📤 Publicación del Sitio

### Opción 1: Hosting Tradicional (cPanel, FTP)
1. Sube todos los archivos a la carpeta `public_html` o `www`
2. Mantén la estructura de archivos tal como está
3. El sitio estará disponible en tu dominio

### Opción 2: GitHub Pages (Gratis)
1. Crea un repositorio en GitHub
2. Sube todos los archivos
3. Ve a Settings > Pages
4. Selecciona la rama main como fuente
5. El sitio estará en `usuario.github.io/repositorio`

### Opción 3: Netlify/Vercel (Gratis)
1. Crea una cuenta en Netlify o Vercel
2. Arrastra la carpeta con todos los archivos
3. El sitio se publicará automáticamente
4. Puedes conectar tu dominio personalizado

## 🔧 Mejoras Futuras Sugeridas

1. **SEO:**
   - Agregar meta tags de Open Graph
   - Crear archivo sitemap.xml
   - Agregar archivo robots.txt

2. **Rendimiento:**
   - Optimizar y comprimir imágenes
   - Minificar CSS y JavaScript
   - Implementar caché del navegador

3. **Funcionalidad:**
   - Integrar Google Maps en página de contacto
   - Agregar galería de proyectos realizados
   - Implementar blog o sección de noticias
   - Agregar chat en vivo

4. **Marketing:**
   - Pixel de Facebook para remarketing
   - Integración con CRM
   - Newsletter signup
   - Testimonios de clientes

## 📞 Soporte

Este sitio web está completamente funcional y listo para usar. Solo necesitas:
1. Actualizar el número de WhatsApp
2. Configurar el formulario de contacto con tu backend
3. Subir los archivos a tu hosting
4. (Opcional) Agregar tu logo

## ✅ Checklist Pre-Lanzamiento

- [ ] Actualizar número de WhatsApp
- [ ] Revisar todos los textos
- [ ] Agregar logo (opcional)
- [ ] Configurar formulario de contacto
- [ ] Probar en móvil, tablet y desktop
- [ ] Verificar todos los enlaces
- [ ] Configurar Google Analytics
- [ ] Conectar dominio personalizado
- [ ] Probar velocidad de carga
- [ ] Verificar SEO básico

---

**Desarrollado para SILOCH SpA - Servicios Integrales de Construcción y Transporte**

*Versión 1.0 - Enero 2026*
