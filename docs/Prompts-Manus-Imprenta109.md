# Prompts para Implementación con Manus - Imprenta 109

## Prompt Principal para Implementación Completa

**Contexto:** Eres un desarrollador web experto especializado en WordPress y WooCommerce. Tu tarea es implementar un sitio web completo para Imprenta 109, una empresa mexicana especializada en photobooks personalizados.

**Objetivo:** Crear un sitio web de comercio electrónico que replique fielmente el prototipo de Figma proporcionado, manteniendo la identidad gráfica de la marca y optimizando la experiencia de usuario para la venta de photobooks personalizados.

**Especificaciones Técnicas:**
- Plataforma: WordPress con WooCommerce
- Tema: Personalizado basado en las especificaciones de diseño, utilizando **Bootstrap** o **Tailwind CSS**
- Responsive: Compatible con dispositivos móviles, tablets y desktop
- Paleta de colores: Amarillo #F6D42A y Negro #373435
- Tipografía: Impact Regular para títulos, fuente corporativa para cuerpo de texto
- Plugin de personalización: **Lumise** (https://demo.lumise.com/woocommerce/product/photobook/) para la selección y personalización del Photobook)
- Integración de pagos: **OpenPay** (como dummy para el prototipo, la integración real se hará posteriormente por el cliente)


**Funcionalidades Requeridas:**
1. Página de inicio con hero section y secciones informativas
2. Configurador de photobooks paso a paso (5 etapas)
3. Sistema de carga de archivos para imágenes del cliente
4. Integración completa con WooCommerce para procesamiento de pedidos
5. Formularios de contacto y recolección de datos de envío
6. Área de testimoniales con carrusel
7. Footer con información de contacto y redes sociales

**Assets Disponibles:**
- Manual de identidad gráfica con especificaciones de marca
- Archivos de diseño extraídos de Figma incluyendo logos, iconos, y tipografías
- Imágenes de productos y elementos gráficos
- Especificaciones técnicas detalladas en documentación adjunta

**Entregables Esperados:**
- Sitio web completamente funcional y responsive
- Tema de WordPress personalizado
- Configuración de WooCommerce para productos de photobook
- Documentación de instalación y configuración
- Archivos de código fuente organizados y comentados

## Prompts Específicos por Funcionalidad

### 1. Prompt para Estructura Base y Tema

Crea la estructura base del tema de WordPress para Imprenta 109 siguiendo estas especificaciones:

**Header:**
- Logo de Imprenta 109 en esquina superior izquierda (tamaño mínimo 115px)
- Navegación principal responsive con menú hamburguesa para móvil
- Colores: fondo negro #373435, elementos en amarillo #F6D42A

**Footer:**
- Información de contacto de la empresa
- Enlaces a redes sociales (Facebook, Instagram, WhatsApp, TikTok)
- Copyright y año actual
- Logo de la empresa centrado

**Estructura de archivos:**
- style.css con variables CSS para colores corporativos
- functions.php con enqueue de scripts y estilos
- header.php y footer.php modulares
- Archivos de template para páginas específicas

### 2. Prompt para Página de Inicio

Implementa la página de inicio basada en el diseño de Figma con las siguientes secciones:

**Hero Section:**
- Imagen de fondo con photobooks abiertos mostrando fotos familiares
- Título principal: "Haz que cada momento viva para siempre..."
- Subtítulo explicativo sobre la preservación de recuerdos
- Botón CTA "Comienza aquí" en amarillo corporativo

**Sección de Cita:**
- Fondo gris oscuro
- Cita destacada: "La memoria es el diario que todos llevamos con nosotros" - Oscar Wilde
- Tipografía elegante y centrada

**Sección de Proceso:**
- Título: "Empieza ahora y transforma tus fotos en algo eterno"
- 4 pasos con iconos: Elige tu Photobook, Sube tus fotos, Aprueba el diseño, Recíbelo en tu casa
- Botón CTA "Crea tu Photobook ahora"

**Sección de Servicios:**
- Título: "Imprimir sigue siendo un arte. Nosotros lo dominamos"
- Descripción de servicios de impresión tradicional
- Imagen de equipos de impresión profesional
- Botón "Servicios de impresión"

**Sección de Testimoniales:**
- Carrusel con testimoniales de clientes
- Fotos de perfil, nombres y reseñas específicas
- Navegación con flechas y dots

### 3. Prompt para Configurador de Photobooks

Desarrolla el sistema de configuración de photobooks en 5 etapas:

**Etapa 1 - Selección de Estilo:**
- Grid de 4 opciones: Básico, Clásico, Lujo, Premium
- Cada tarjeta con imagen del producto, nombre, precio base
- Precios: Básico $1200, Clásico $1400, Lujo $1600, Premium $2400
- Selección visual con bordes destacados

**Etapa 2 - Personalización:**
- Formulario con opciones de personalización
- Campos: tipo de papel, cubierta, encuadernado, extras
- Calculadora de precio en tiempo real
- Resumen del pedido en sidebar

**Etapa 3 - Datos y Archivos:**
- Área de drag & drop para subir imágenes
- Soporte para JPEG, PNG, PDF, TIFF, PSD, PPT
- Formulario con datos personales y de envío
- Validación de campos requeridos

**Etapa 4 - Confirmación:**
- Resumen completo del pedido
- Verificación de datos personales
- Botón para proceder al pago

**Etapa 5 - Confirmación Final:**
- Mensaje de éxito con ícono de check verde
- Información sobre seguimiento del pedido
- Botón para crear otro photobook

### 4. Prompt para Integración WooCommerce

Configura WooCommerce para manejar los productos de photobook:

**Productos Variables:**
- Producto principal "Photobook Personalizado"
- Variaciones por tipo: Básico, Clásico, Lujo, Premium
- Atributos personalizados para opciones de personalización
- Precios dinámicos basados en selecciones

**Campos Personalizados:**
- Campos para archivos del cliente
- Información de personalización
- Datos de envío específicos
- Notas especiales del pedido

**Proceso de Checkout:**
- Integración con el configurador personalizado
- Validación de archivos cargados
- Confirmación de especificaciones antes del pago
- Emails automáticos con detalles del pedido

### 5. Prompt para Optimización y Rendimiento

Implementa optimizaciones para rendimiento y SEO:

**Optimización de Imágenes:**
- Lazy loading para todas las imágenes
- Múltiples tamaños responsive
- Compresión automática
- Formato WebP con fallbacks

**SEO On-Page:**
- Meta tags optimizados para cada página
- Schema markup para productos y empresa
- URLs amigables para SEO
- Sitemap XML automático

**Performance:**
- Minificación de CSS y JavaScript
- Caché de navegador configurado
- Optimización de base de datos
- CDN ready para assets estáticos

**Accesibilidad:**
- Contraste de colores WCAG AA
- Navegación por teclado
- Alt text para imágenes
- Etiquetas semánticas apropiadas

## Recomendaciones de Implementación

### Orden de Desarrollo Sugerido

1. **Fase 1:** Estructura base del tema y configuración de WordPress
2. **Fase 2:** Implementación de la página de inicio
3. **Fase 3:** Desarrollo del configurador de photobooks
4. **Fase 4:** Integración con WooCommerce
5. **Fase 5:** Testing, optimización y ajustes finales

### Consideraciones Técnicas Importantes

**Manejo de Archivos:** Implementar un sistema robusto de manejo de archivos que incluya validación de tipo y tamaño, almacenamiento seguro, y asociación con pedidos específicos.

**Responsive Design:** Priorizar la experiencia móvil dado que muchos usuarios mexicanos acceden principalmente desde dispositivos móviles.

**Localización:** Configurar el sitio para el mercado mexicano incluyendo formato de moneda (MXN), direcciones, y números de teléfono.

**Seguridad:** Implementar medidas de seguridad robustas para proteger los archivos y datos personales de los clientes.

### Testing y Quality Assurance

**Testing Cross-Browser:** Verificar compatibilidad en Chrome, Firefox, Safari, y Edge.

**Testing de Dispositivos:** Probar en diferentes tamaños de pantalla y dispositivos táctiles.

**Testing de Funcionalidad:** Verificar todo el flujo de compra desde la selección hasta la confirmación del pedido.

**Performance Testing:** Optimizar para tiempos de carga rápidos, especialmente en conexiones móviles.

