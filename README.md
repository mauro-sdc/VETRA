**Zonda IT**

Zonda IT es una web estática para productores de seguros que reúne un Chatbot, un CRM y herramientas de gestión.
Su objetivo es automatizar la atención y centralizar la gestión de pólizas en una plataforma simple, mobile-first y amigable.

🧩 **Funcionalidades**

Automatización de mensajes
Respuestas automáticas para consultas frecuentes (vencimientos, coberturas, envíos de documentos).

Gestión de clientes y pólizas
Visualización y actualización de datos de pólizas, pagos y renovaciones.

Envío automático de documentación
Cupones, certificados y reportes sin intervención manual.

Consultas de estado en tiempo real
Información inmediata por cliente y póliza.

Informes y seguimientos
Reportes mensuales automáticos.

Aseguradoras integradas
Carrusel con logos de compañías conectadas.

Equipo Zonda IT
Sección con perfiles de roles (Founder, Comercial, Devs, QA/CS, etc.).

🗂️ **Estructura del proyecto**
/ ← raíz del sitio
├── index.html ← Inicio (beneficios, acordeón, carrusel de logos)
├── pages/
│ ├── chatboot.html ← Página del Chatboot
│ ├── servicios.html ← Servicios (chatbot, CRM y gestión)
│ ├── nosotros.html ← Quiénes somos + Equipo Zonda IT
│ └── contacto.html ← Formulario de contacto
├── Style/
│ ├── style.css
│ ├── style.css.map
│ ├── variables.css
│ └── variables.css.map
└── sass/
├── style.scss
├── index.scss
└── variables.scss

🧰 **Tecnologías**

HTML5 + CSS (compilado desde Sass)

Bootstrap 5.3.7 vía CDN

Animate.css (en páginas con animaciones)

📱 **Responsive**

Mobile-first con Bootstrap 5.

Soporte aproximado 320px–1200px.

Grillas (.container, .row, .col-\*) e imágenes fluidas.

♿ **Accesibilidad**

Formularios con label asociados; campos principales con required / aria-required="true" (contacto).

Un solo h1 por página (logo sin h1; título principal en <main>).

alt descriptivo en imágenes (logos y fotos).

🚀 **Performance**

Scripts con defer (Bootstrap) para no bloquear el render.

loading="lazy" en imágenes no críticas (carrusel, demo, equipo).

Uso de .webp donde es posible.

Animación del logo con @keyframes.

🔎 **SEO**

SEO On-Page (aplicado)

Meta description y meta keywords por página.

Jerarquía de encabezados corregida (h1 único en <main>).

Optimización de imágenes: alt descriptivo y loading="lazy".

URLs amigables: estructura simple.

SEO Técnico (aplicado en HTML)

Velocidad de carga: defer en scripts + lazy en imágenes.

Optimización mobile: meta viewport + Bootstrap.

SEO Técnico (pendiente para dominio propio)

/robots.txt y /sitemap.xml en la raíz.

Minificación y caché en servidor para producción.

☁️ **Hosting**

Realizado en Vercel

Dominio: https://vetra-lake.vercel.app/
