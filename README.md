# Sinai Mantenimiento Integral 🇺🇾

Sitio web corporativo y de captación de clientes para **SINAI MANTENIMIENTO**, empresa de soluciones técnicas integrales de mantenimiento, sanitaria y obras en Uruguay, atendida directamente por sus directores **Andrés y Verónica**.

---

## 🚀 Diferenciales de Marca

- **Atención 365 días del año:** Guardia activa de urgencias para roturas de caños, destapes y problemas edilicios imprevistos.
- **Facturación Oficial con RUT:** Empresa formal registrada para facturar a consorcios, administraciones de copropiedad, industrias, comercios y particulares.
- **Cobertura Multirubro:** Centralización de 7 rubros clave en un único proveedor de confianza:
  1. **Sanitaria Integral y Destapes de Urgencia**
  2. **Herrería de Obra y Seguridad**
  3. **Albañilería y Reformas Llave en Mano**
  4. **Impermeabilizaciones de Azoteas y Techos**
  5. **Drywall, Yeso y Cielorrasos**
  6. **Pintura Profesional de Interiores y Fachadas**
  7. **Limpieza Final de Obra y Jardinería**
- **Trato Directo y Personalizado:** Supervisión directa en obra por Andrés y Verónica.

---

## 📞 Datos de Contacto Comercial

- **WhatsApp & Urgencias:** [+598 96 219 719](https://wa.me/59896219719) / `096 219 719`
- **Correo Electrónico:** `vegaandres7321@gmail.com`
- **Áreas de Cobertura:** Montevideo, Ciudad de la Costa, Canelones y todo Uruguay para proyectos medianos/grandes.

---

## 🛠️ Stack Tecnológico

- **Framework:** [Astro](https://astro.build/) (Arquitectura estática pre-renderizada de ultra alto rendimiento y SEO nativo).
- **Estilos:** [Tailwind CSS](https://tailwindcss.com/) v4 con motor Vite de compilación instantánea.
- **Hosting & Formularios:** [Netlify](https://www.netlify.com/) con soporte nativo para **Netlify Forms** (sin backend necesario, protección contra bots por honeypot).
- **SEO & Datos Estructurados:** Schema.org `HomeAndConstructionBusiness` JSON-LD, OpenGraph y Twitter Cards configurados.

---

## 📁 Estructura del Repositorio

```text
WebSinaiSanitaria/
├── netlify.toml                # Configuración de build, headers de seguridad y caché Netlify
├── package.json                # Dependencias y scripts npm
├── astro.config.mjs            # Configuración de Astro con integración Tailwind Vite
├── tsconfig.json               # Configuración TypeScript
├── public/
│   ├── favicon.svg             # Isotipo oficial Sinai en SVG
│   └── robots.txt              # Directivas para motores de búsqueda
├── src/
│   ├── layouts/
│   │   └── Layout.astro        # Layout base con SEO, OpenGraph y Schema JSON-LD
│   ├── styles/
│   │   └── global.css          # Tailwind CSS v4 y animaciones de marca
│   ├── components/
│   │   ├── Header.astro        # Barra de navegación adhesiva responsive con CTAs
│   │   ├── UrgencyBanner.astro # Cinta de urgencias 365 días con llamada inmediata
│   │   ├── Hero.astro          # Hero section con valor de marca y doble conversión
│   │   ├── Services.astro      # Cuadrícula detallada de los 7 rubros con CTAs pre-cargados
│   │   ├── WhyUs.astro         # Diferenciales competitivos (RUT, 365 días, trato directo)
│   │   ├── CoverageAreas.astro # Mapeo geográfico de cobertura (Montevideo, Canelones, Interior)
│   │   ├── Testimonials.astro  # Casos de éxito y testimonios locales uruguayos
│   │   ├── FAQ.astro           # Preguntas frecuentes con acordeón interactivo
│   │   ├── ContactForm.astro   # Formulario Netlify Forms con opciones de RUT y urgencia
│   │   ├── WhatsAppButton.astro# Botón flotante pulsante con tooltip inteligente
│   │   └── Footer.astro        # Pie de página completo con enlaces y mención legal
│   └── pages/
│       ├── index.astro         # Página principal (Landing integral)
│       ├── gracias.astro       # Página de agradecimiento y aceleración de contacto
│       └── servicios/
│           └── sanitaria.astro # Landing especializada en Sanitaria de Urgencia 24/7
```

---

## 💻 Desarrollo Local

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/lucasmantuani2000/WebSinaiSanitaria.git
   cd WebSinaiSanitaria
   ```

2. Instalar dependencias:
   ```bash
   npm install
   ```

3. Iniciar el servidor de desarrollo:
   ```bash
   npm run dev
   ```
   Abrir en el navegador: `http://localhost:4321`

4. Compilar para producción:
   ```bash
   npm run build
   ```

5. Previsualizar la versión compilada:
   ```bash
   npm run preview
   ```

---

## ☁️ Despliegue en Netlify

El proyecto está preparado para desplegarse con 1 solo clic en Netlify:
- **Build command:** `npm run build`
- **Publish directory:** `dist`
- Los envíos del formulario se gestionan automáticamente en la pestaña **Forms** del panel de Netlify gracias a los atributos `data-netlify="true"` y honeypot antispam integrados en `src/components/ContactForm.astro`.
