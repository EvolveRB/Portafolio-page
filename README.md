[prd_y_brief_de_proyecto_vanguard_it_studio.md](https://github.com/user-attachments/files/33373156/prd_y_brief_de_proyecto_vanguard_it_studio.md)
# Product Requirements Document (PRD) & Project Brief

**Producto:** Vanguard IT Studio & Lab — Plataforma Web Corporativa & Portafolio Tecnológico  
**Versión:** 1.0.0  
**Fecha:** Marzo 2025  
**Estado:** Aprobado / En Producción  
**Autor:** Equipo de Producto & Diseño (Stitch AI)

---

## 1. Resumen Ejecutivo (Executive Summary)

Vanguard IT Studio & Lab es una firma emergente de consultoría informática, arquitectura de software resiliente y modernización de infraestructura cloud orientada a startups, scaleups y PyMEs en Iberoamérica. 

El presente proyecto consiste en el diseño, desarrollo e implementación de una landing page corporativa integral de alto impacto que comunique solvencia técnica, demuestre experiencia real mediante casos prácticos interactivos, presente al equipo directivo de ingeniería y maximice la conversión de prospectos corporativos hacia diagnósticos de viabilidad técnica en 24 horas.

---

## 2. Objetivos del Negocio & Métricas de Éxito (OKRs)

### 2.1 Objetivos de Negocio
* **Posicionamiento de Marca:** Establecer a Vanguard IT como un referente de ingeniería rigurosa (Twelve-Factor, CNCF, OWASP Top 10) frente a competidores tradicionales de desarrollo web generalista.
* **Generación y Cualificación de Leads:** Captar solicitudes de diagnóstico de modernización de arquitectura, migraciones cloud y desarrollo a medida con presupuestos estimados y especificación de stack actual.
* **Transparencia y Solvencia:** Exponer perfiles de liderazgo verificados y casos de éxito reales con métricas cuantitativas de rendimiento y disponibilidad.

### 2.2 Métricas Clave de Éxito (KPIs)
* **Tasa de Conversión (CR):** ≥ 4.5% en envío de formulario de evaluación técnica inicial.
* **Tiempo de Permanencia (Avg. Time on Page):** > 2 minutos y 30 segundos.
* **Engagement en Portafolio:** ≥ 60% de los visitantes interactúan con el carrusel de casos de estudio o visor de arquitectura.
* **Core Web Vitals:** Rendimiento ≥ 95 en Google Lighthouse, LCP < 1.2s, CLS = 0.

---

## 3. Personas y Audiencia Objetivo

1. **CTO / VP of Engineering (Startups & Scaleups):**
   * *Necesidad:* Modernizar sistemas heredados (monolitos a microservicios/Kubernetes), reducir latencias de API y resolver cuellos de botella de infraestructura.
   * *Qué busca en el sitio:* Evidencia de buenas prácticas (DDD, Kafka, Go, Terraform), certificaciones y casos verificables.
2. **Director de Operaciones / CEO (PyMEs en Transformación Digital):**
   * *Necesidad:* Automatización de flujos de trabajo (RPA), integraciones seguras con ERP/CRM y cumplimiento regulatorio (SOC 2, ISO 27001).
   * *Qué busca en el sitio:* Transparencia presupuestaria, acuerdos de confidencialidad (NDA) claros y tiempos de entrega garantizados.

---

## 4. Arquitectura de Información y Secciones

La web está estructurada en una experiencia de página única (*Single Page Application* / Longform Landing Page) con navegación continua y detección de posición en tiempo real (*scroll spy*):

```
┌────────────────────────────────────────────────────────────────────────┐
│  HEADER / NAV: Logo Vanguard IT + Links (Enfoque, Servicios, Nosotros,  │
│  Portafolio, Contacto) + CTA "Iniciar Proyecto"                       │
└────────────────────────────────────────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│  1. HERO / ENFOQUE                                                     │
│     - H1: "Ingeniería de software y consultoría tecnológica..."        │
│     - Badges de tracción & CTAs primario y secundario                  │
│     - 3 Tarjetas de Pilares: Arquitectura Resiliente, Desarrollo Ágil, │
│       Consultoría y Auditoría TI                                       │
└────────────────────────────────────────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│  2. CAPACIDADES / SERVICIOS ESPECIALIZADOS (Grid 3x2)                  │
│     01. Transformación Digital & Migración Cloud                       │
│     02. Software a Medida & APIs de Misión Crítica                     │
│     03. Ciberseguridad, DevSecOps & Auditoría                          │
│     04. Infraestructura & Bases de Datos Distribuidas                  │
│     05. Automatización de Procesos (RPA) & Conectores                  │
│     06. Staff Augmentation & Equipos Ágiles Dedicados                  │
└────────────────────────────────────────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│  3. TALENTO CLAVE & LIDERAZGO (NOSOTROS)                               │
│     - Alejandro Morales (CEO & Lead Tech Strategist)                   │
│     - Sofía Restrepo (Head of Cloud & Principal SRE)                   │
│     - Diego Carrasco (Lead Full-Stack Engineer)                        │
│     * Badges de certificación, enlaces profesionales y especialidades  │
└────────────────────────────────────────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│  4. CASOS PRÁCTICOS & PORTAFOLIO DE SOLUCIONES                         │
│     - Carrusel dinámico de proyectos tecnológicos con vista de tarjeta │
│       (LogisTrack IoT, MedPulse Health, RetailSync ERP, OmniData)      │
│     - Enlace a arquitectura técnica y métricas de impacto              │
└────────────────────────────────────────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│  5. EVALUACIÓN Y CONTACTO                                              │
│     - Propuesta de valor: "Respuesta garantizada < 24h", NDA incluido │
│     - Formulario estructurado: Nombre, Empresa, Correo, Tipo solución, │
│       Presupuesto estimado y Descripción de cuello de botella          │
└────────────────────────────────────────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│  6. FOOTER CORPORATIVO INTEGRADO                                       │
│     - Ubicación física compacta (Sede Central en Madrid, España)       │
│     - Ecosistema Tech, Consultoría y Red Global                        │
│     - Certificaciones (ISO 27001, SOC 2 Type II, AWS Partner)          │
│     - Términos Legales, Privacidad y Compliance SLA                    │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 5. Requerimientos Funcionales (FR)

* **FR-01: Navegación Fija & Scroll Spy Dinámico:**
  * La barra de navegación debe persistir (`fixed top-0 z-50`).
  * Debe actualizar automáticamente el estado visual del enlace activo conforme el usuario hace scroll vertical libre por la pantalla (`IntersectionObserver`).
* **FR-02: Exploración Interactiva del Portafolio:**
  * Componente de carrusel con controles direccionales (anterior/siguiente), paginación por dots y pausa al interactuar.
  * Tarjetas con visualización de mockup de sistema, tags de industria y enlaces a detalles de arquitectura.
* **FR-03: Captura de Leads Técnicos:**
  * Formulario con validación en cliente para correos corporativos.
  * Selector de rangos presupuestarios estándar de consultoría TI ($5,000 - $15,000+ USD).
  * Checkbox implícito o aviso de protección de datos bajo protocolo de confidencialidad (NDA).
* **FR-04: Diseño Responsivo:**
  * Adaptación fluida para Desktop (1440px+ y 1280px), Tablet (768px - 1024px) y Mobile (390px - 430px).

---

## 6. Requerimientos No Funcionales & Sistema de Diseño (NFR)

### 6.1 Identidad Visual y Tokens de Diseño
* **Color Primario Corporativo:** Azul `#00688f` (proyecta solvencia, precisión de ingeniería y estabilidad tecnológica).
* **Color Secundario / Acento:** Morado intenso `#4c3592` / `#6366f1` (representa innovación, modernidad y agilidad).
* **Fondo:** Unificado continuo (opción clara lavanda suave `#fdf8ff` / opción oscura de alto contraste `#0b0f19`).
* **Regla de Formas y Esquinas (Geometría Mixta):**
  * *Contenedores y Tarjetas:* Bordes rectos y definidos con radio sutil (2px–4px) para un orden técnico estructurado.
  * *Elementos Interactivos (Botones `<a>`, Badges, Nav pills):* Bordes completamente redondeados / píldora (`rounded-full` / `9999px`).
  * *Contenedores de Iconografía:* Circulares (`rounded-full`).
* **Tipografía:** Tipografía geométrica legible en entornos de código e interfaz (Epilogue / Inter / Roboto Mono para tags de tecnologías).

### 6.2 Accesibilidad & Seguridad
* Cumplimiento estricto de WCAG 2.1 AA en ratios de contraste para texto e interactivos.
* Protocolo seguro HTTPS, encabezados de seguridad CSP y aviso explícito de almacenamiento seguro de datos según RGPD y normativas internacionales.

---

## 7. Roadmap de Implementación

| Fase | Alcance | Hitos de Entrega |
|---|---|---|
| **Fase 1: Prototipado y Validación Visual** *(Completada)* | Diseño de pantalla de alta fidelidad, definición cromática `#00688f` + morado, navegación con scroll spy y arquitectura de tarjetas. | Mockups interactivos y diseño en DataStore aprobados. |
| **Fase 2: Conexión Frontend & Microinteracciones** | Integración del carrusel de proyectos, validaciones reactivas de formulario y modales de vista técnica de proyectos. | Repositorio frontend desplegado en entorno staging. |
| **Fase 3: Backend & Integraciones de CRM** | Endpoint API para recepción de formularios, automatización de email transaccional y webhook directo a HubSpot/Notion. | Envío de leads en tiempo real con SLA < 24h. |
| **Fase 4: Analítica & Pruebas A/B** | Medición de eventos de scroll, clics en CTAs de diagnóstico y pruebas multivariante de copy de conversión. | Dashboard de métricas en GA4 y Hotjar activo. |

---

## 8. Criterios de Aceptación (DoD)

1. El sitio debe cargar en menos de 1.5 segundos en conexiones de banda ancha estándar.
2. Cada tarjeta de servicio debe listar claramente tecnologías (ej. Docker, Kubernetes, Terraform, Go, React, PostgreSQL) y entregables concretos.
3. El pie de página debe contener de forma compacta la sede física, certificaciones internacionales y políticas de privacidad sin sobrecargar visualmente la pantalla.
4. Todos los botones de llamada a la acción deben tener estados *hover*, *focus* y *active* coherentes con la paleta `#00688f`.
