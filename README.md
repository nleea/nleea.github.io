# pase-web

Landing de presentación de **El Pase**, el sistema operativo para restaurantes: una plataforma
web multi-sucursal que cubre la operación completa de un restaurante, desde que se abre una mesa
hasta que entra a caja, descuenta inventario y se repone por compras.

Este repositorio contiene **únicamente la página de marketing** que muestra el producto. No es el
sistema en sí (el panel de operación vive en otros repositorios), sino el sitio que lo presenta a
restaurantes interesados.

## ¿Para qué sirve?

- Explicar qué es El Pase y qué problema resuelve.
- Mostrar los módulos del sistema (comandas, cocina/KDS, caja, domicilios, inventario, recetas,
  compras, clientes, finanzas, personal, RBAC y auditoría).
- Explicar el flujo operativo: tomar pedido → preparar → cobrar → cerrar y descontar stock.
- Comunicar diferenciadores (multi-sucursal, permisos a medida, auditoría, métodos de pago locales).
- Presentar planes y capturar solicitudes de demo.

## Contenido

| Sección | Descripción |
|---|---|
| Hero | Propuesta de valor + mockup del tablero de cocina (KDS) |
| Métricas | Cifras destacadas del sistema |
| Módulos | Las 13 áreas de la operación |
| Cómo funciona | Flujo interactivo en 4 pasos (tabs) |
| Plataforma | Características técnicas y diferenciales |
| Precios | Planes Básico, Pro y Empresa |
| Preguntas | FAQ en acordeón |
| CTA / Footer | Solicitud de demo y contacto (`sistema@pase.uk`) |

## Tecnología

- Un único `index.html` autocontenido: **HTML + CSS + JavaScript vanilla**, sin dependencias ni
  build step.
- Tipografías Bricolage Grotesque, IBM Plex Sans y IBM Plex Mono (Google Fonts).
- Design system "El Pase" (graphite + steel + ember), responsive, con soporte de
  `prefers-reduced-motion`.
- Interacciones: menú móvil, scroll-reveal, contadores animados, tabs del flujo y acordeón.

## Cómo visualizarlo

No requiere instalación. Abre el archivo directamente:

```bash
open index.html
```

O sírvelo en local:

```bash
python3 -m http.server 8080
```

Luego visita `http://localhost:8080`.

## Estructura

```
pase-web/
├── index.html   # Página completa (estructura, estilos y scripts)
├── .gitignore
└── README.md
```
