# Proyectos de automatización con n8n e Inteligencia Artificial

Colección de automatizaciones desarrolladas con **n8n**, integrando inteligencia artificial, APIs y servicios externos para optimizar procesos empresariales y tareas personales.

## 1. Procesamiento automatizado de facturas con IA

![Workflow de facturación](n8n-AI-automatizations/images/facturacion.png)

Sistema de automatización para procesar facturas de dos proveedores con formatos diferentes.

**Funcionalidades principales:**
- Recepción automática de facturas PDF mediante Gmail.
- Extracción de datos de facturación y artículos utilizando modelos de IA de OpenAI.
- Procesamiento y estructuración de datos JSON mediante JavaScript.
- Clasificación de artículos y agrupación por cuentas contables.
- Generación automática de documentos de Google Sheets con el detalle de facturación.

**Tecnologías:** n8n, OpenAI API, JavaScript, Gmail, Google Sheets y Google Drive.

**Workflows:**
- [Proveedor A](n8n AI automatizations/workflows/Procesado_facturas_PROVEEDOR_A_PUBLICO.json)
- [Proveedor B](n8n AI automatizations/workflows/Procesado_facturas_PROVEEDOR_B_PUBLICO.json)

## 2. PlebeYo — Asistente personal con IA

![Workflow de PlebeYo](n8n AI automatizations/images/plebeyo.png)

Agente de inteligencia artificial desarrollado con n8n y accesible mediante Telegram, diseñado para gestionar diferentes servicios desde una única interfaz conversacional.

**Funcionalidades principales:**
- Procesamiento de mensajes de texto, audio e imágenes.
- Agente de IA con memoria conversacional.
- Integración con Gmail, Google Calendar y Google Tasks.
- Consulta y modificación de inventarios mediante Google Sheets.
- Gestión de eventos y recordatorios mediante herramientas y subworkflows.
- Control de acceso y confirmación antes de ejecutar acciones destructivas.

**Tecnologías:** n8n, OpenAI API, Telegram Bot API, Google APIs y agentes de IA.

**Workflow:**
- [PlebeYo](n8n AI automatizations/workflows/PlebeYo_PUBLICO.json)

## Seguridad y privacidad

Los workflows publicados son versiones anonimizadas de los proyectos originales.

Para proteger la información personal y profesional, se han realizado las siguientes modificaciones:

- Eliminación de referencias a credenciales y autenticaciones.
- Anonimización de nombres, correos electrónicos e identificadores personales.
- Eliminación de identificadores privados de documentos, calendarios y servicios externos.
- Eliminación de datos de ejecución y metadatos sensibles.

Se ha conservado la arquitectura, las conexiones entre nodos y la lógica principal de las automatizaciones.

**Nota:** Los archivos JSON son versiones demostrativas. Para utilizarlos es necesario configurar las credenciales, los servicios externos y los identificadores correspondientes.
