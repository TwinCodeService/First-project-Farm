# First-project-Farm

Resumen ejecutivo
Propósito: Diseñar y entregar un sitio web con E‑commerce y una landing page comercial para una de las mayores granjas de Aguada en Cienfuegos, que venda productos agrícolas y de ganadería.  
Alcance inicial asumido: tienda online con catálogo por categorías, carrito y checkout; landing page para promoción de marca y captación de clientes/contratos; panel administrativo para gestión de productos, pedidos y clientes; diseño responsive y optimizado para conexiones lentas.  
Entregables clave: prototipos UI, sitio E‑commerce funcional, landing page, manual de administración, capacitación y plan de mantenimiento.

---

Objetivos y público objetivo

Objetivos del negocio
- Vender en línea productos agrícolas y ganaderos a clientes locales y, si procede, a distribuidores.  
- Captar clientes comerciales (restaurantes, mercados, cooperativas) mediante la landing page.  
- Automatizar procesos de pedidos, inventario y facturación básica.  
- Mejorar la presencia digital y la confianza de marca.

Público objetivo
- Consumidores locales que compran por unidad o en pequeñas cantidades.  
- Compradores mayoristas (distribuidores, mercados, restaurantes).  
- Clientes institucionales (hoteles, cooperativas agrícolas).  
- Perfil técnico: uso mayoritario de móviles; conexiones variables; posible preferencia por contacto telefónico/WhatsApp para confirmaciones.

---

Requisitos funcionales y técnicos

Requisitos funcionales principales
- Catálogo de productos con categorías: Agricultura; Ganadería; Insumos; Servicios.  
- Búsqueda y filtros por categoría, precio, disponibilidad, peso/volumen.  
- Carrito y checkout con resumen, cálculo de envío y opciones de pago.  
- Gestión de pedidos (estado: recibido, en preparación, enviado, entregado).  
- Panel administrativo para crear/editar productos, gestionar stock, ver pedidos y clientes.  
- Landing page con formulario de contacto, CTA para pedidos mayoristas y sección de testimonios.  
- Integración de contacto directo (teléfono/WhatsApp) visible en todas las páginas.  
- Multimedia: galería de productos y fotos de la granja; posibilidad de videos cortos.

Requisitos técnicos y no funcionales
- Idioma: Español (Cuba).  
- Responsive y Mobile‑first.  
- Optimización para baja velocidad: imágenes comprimidas, lazy loading, versiones ligeras.  
- Accesibilidad básica (contraste, etiquetas, navegación por teclado).  
- SEO on‑page: URLs limpias, meta tags, sitemap.xml, robots.txt.  
- Escalabilidad: arquitectura que permita añadir más productos y módulos.  
- Backups y recuperación.

---

Arquitectura de información y UX UI

Estructura de páginas (mapa del sitio)
| Página | Propósito |
|---|---|
| Home | Presentación, productos destacados, CTA a tienda y landing |
| Tienda / Catálogo | Navegación por categorías y búsqueda |
| Página de producto | Detalles, fotos, precio, opciones de compra |
| Carrito | Resumen de compra |
| Checkout | Datos de envío, pago, confirmación |
| Landing Page | Oferta para clientes mayoristas; formulario de contacto |
| Nosotros | Historia de la granja, prácticas, certificaciones |
| Contacto | Teléfono, WhatsApp, dirección, mapa |
| Panel Admin | Gestión interna (no público) |

Principios de UX
- Flujo de compra corto: producto → carrito → checkout en máximo 3 pasos.  
- CTA claros: botones visibles para comprar y contactar.  
- Confianza: fotos reales de la granja, políticas claras de envío y devoluciones.  
- Soporte humano: opción de confirmar pedidos por teléfono/WhatsApp.

Lineamientos visuales (sugeridos)
- Paleta: tonos verdes y tierra para transmitir agricultura; acentos en color cálido para CTA.  
- Tipografía: legible en móviles; tamaños grandes para botones.  
- Fotografía: imágenes auténticas de la granja y productos; evitar stock genérico.

---

Integraciones, seguridad y cumplimiento

Integraciones recomendadas
- Pasarelas de pago: ofrecer varias opciones; si no hay pasarelas locales, contemplar pago contra entrega y transferencias bancarias; integrar pasarela internacional si el negocio lo permite.  
- Logística: módulo para cálculo de envío local; integración con transportistas locales o sistema propio de reparto.  
- Comunicación: WhatsApp Business link; formulario con notificaciones por email.  
- Contabilidad: exportación de pedidos a CSV para contabilidad manual.

Seguridad
- HTTPS obligatorio.  
- Protección de datos personales: almacenar solo lo necesario; políticas de privacidad claras.  
- Backups automáticos y control de accesos al panel admin.  
- Medidas anti‑fraude básicas en checkout.

Consideraciones legales y locales
- Cumplimiento fiscal y de facturación según normativa local (verificar requisitos de facturas y registros).  
- Política de envíos y devoluciones adaptada a productos perecederos.

---

Plan de proyecto, entregables y KPIs

Fases y entregables
1. Descubrimiento y requisitos (1 semana)  
   - Entrevistas con el cliente; lista final de productos y logística.  
2. Arquitectura y prototipos (2 semanas)  
   - Sitemap, wireframes, prototipo interactivo de la tienda y landing.  
3. Diseño visual (1–2 semanas)  
   - Mockups de Home, ficha de producto, landing y checkout.  
4. Desarrollo (3–5 semanas)  
   - Implementación front/back, integración de pagos y logística.  
5. Pruebas y ajustes (1–2 semanas)  
   - QA funcional, pruebas en móviles y conexiones lentas.  
6. Lanzamiento y capacitación (1 semana)  
   - Migración a producción, capacitación al equipo administrativo.  
7. Soporte inicial (1–3 meses opcional)  
   - Correcciones, monitoreo y optimizaciones.

Entregables concretos
- Documento de requisitos final.  
- Prototipos y diseños en Figma/archivo visual.  
- Sitio web en entorno de producción.  
- Manual de uso y video corto de capacitación.  
- Plan de mantenimiento y backups.

KPIs sugeridos para medir éxito
- Tasa de conversión (visitas → compras).  
- Valor promedio de pedido.  
- Tasa de abandono de carrito.  
- Tiempo de carga móvil.  
- Número de leads generados desde la landing.

---

Recomendaciones finales y próximos pasos
- Confirmar restricciones locales sobre pagos en línea y logística para definir la pasarela y el flujo de checkout.  
- Priorizar mobile y optimización de peso por la conectividad en zonas rurales.  
- Planificar fotografía propia de la granja para generar confianza.  
- Decidir modelo de ventas: venta al detalle, por bulto, suscripciones o contratos mayoristas.  
- Proponer una reunión con el jefe de la granja para validar inventario, condiciones de envío y métodos de pago; tras esa reunión se produce el presupuesto y cronograma final.
- 
