# 📋 Audit One-Page — Plantilla HTML para Auditoría Corporativa

Plantilla profesional de una sola página para presentar informes de auditoría corporativa. Diseñada para ser simple, elegante y lista para usar sin dependencias ni frameworks.

---

## Vista previa

> Navbar fijo · Hero con llamadas a la acción · Sección de objetivos · Datos de la empresa · Footer de contacto

---

## Características

- **Un solo archivo** `auditoria.html` — sin dependencias locales, sin build tools
- **100% responsive** — adaptada para desktop, tablet y móvil
- **Navbar fijo** que acompaña al usuario en todo momento
- **Scroll suave** a cada sección desde el navbar y los botones del hero
- **Animaciones de entrada** al hacer scroll (Intersection Observer)
- **Fuentes externas** vía Google Fonts (`Playfair Display` + `DM Sans`)
- Sin frameworks CSS, sin JavaScript externo — HTML, CSS y JS vanilla

---

## Estructura de la página

| Sección | Descripción |
|---|---|
| **Hero** | Título principal y dos botones de navegación rápida |
| **Objetivos** | Cuadrícula de 6 tarjetas con los objetivos de la auditoría |
| **Empresa** | Tabla de datos institucionales y estadísticas clave |
| **Contacto / Footer** | Información de contacto, navegación y notas legales |

---

## Cómo usar

1. Descarga o clona el repositorio
2. Abre `auditoria.html` en cualquier navegador — funciona sin servidor
3. Edita los campos marcados directamente en el HTML

### Campos a personalizar

```html
<!-- Nombre de la firma auditora -->
<span class="nav-logo">AuditPro</span>

<!-- Datos de la empresa auditada -->
<span class="data-val">Nombre de la Empresa S.A.</span>
<span class="data-val">76.XXX.XXX-X</span>        <!-- RUT / NIF -->
<span class="data-val">Servicios Financieros</span> <!-- Sector -->
<span class="data-val">Nombre Apellido</span>       <!-- Representante legal -->

<!-- Estadísticas -->
<span class="stat-val">$0M</span>   <!-- Ingresos -->
<span class="stat-val">000</span>   <!-- Colaboradores -->
<span class="stat-val">0</span>     <!-- Sucursales -->
<span class="stat-val">00 años</span> <!-- Antigüedad -->

<!-- Contacto en el footer -->
<a href="mailto:contacto@auditpro.cl">contacto@auditpro.cl</a>
<a href="tel:+56912345678">+56 9 1234 5678</a>
```

---

## Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 semántico | Estructura del documento |
| CSS3 (variables, grid, clamp) | Estilos y responsive design |
| JavaScript vanilla | Animaciones de scroll (Intersection Observer) |
| Google Fonts | Tipografía (`Playfair Display`, `DM Sans`) |

---

## Compatibilidad

Probada en Chrome, Firefox, Safari y Edge en sus versiones modernas.  
No requiere Internet Explorer ni polyfills.

---

## Licencia

Uso libre como plantilla. Puedes modificarla, distribuirla y adaptarla a tus proyectos sin restricciones.  
Si la usas como base para un proyecto propio, se agradece una mención o estrella ⭐ al repositorio.

---

*Generado como plantilla de código abierto para auditorías corporativas.*
