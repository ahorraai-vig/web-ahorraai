# AhorraAI · Vigo 🛒

> Plataforma de digitalización e inteligencia artificial para negocios locales de Vigo.  
> **Web en producción → [ahorraai.com](https://ahorraai.com)**

---

## ¿Qué es esto?

AhorraAI nació como un asistente de comparación de precios por WhatsApp para vecinos de Vigo. Ha evolucionado hacia una plataforma más amplia que conecta negocios locales con sus clientes mediante IA y automatización.

Este repositorio contiene el **frontend público** del proyecto: una landing page estática con información de servicios, planes y acceso al canal de WhatsApp.

---

## Stack Técnico

| Capa | Tecnología |
|---|---|
| Frontend | HTML5 · CSS3 · JavaScript vanilla |
| Hosting | GitHub Pages |
| Dominio | ahorraai.com (CNAME personalizado) |
| Formularios | Tally.so |
| Contacto | WhatsApp Business API |

---

## Estado del Proyecto

- [x] Landing page en producción con dominio propio
- [x] Formulario de captación de negocios (Tally)
- [x] Canal WhatsApp activo
- [ ] Motor de comparación de precios (en desarrollo)
- [ ] Scraper de supermercados en AWS Lambda (en desarrollo)
- [ ] Integración con API de Claude/LLM (próximamente)

---

## Proyecto completo (backend)

La parte técnica del proyecto incluye:

- **Scraper serverless** en AWS Lambda con disparo nocturno via EventBridge
- **Base de datos** en Google Sheets, poblada automáticamente
- **Bot de WhatsApp** que responde consultas de precios usando IA
- **Pipeline completo**: Scraping → Almacenamiento → Consulta por lenguaje natural

> El código del backend está en un repositorio separado (privado durante el desarrollo).

---

## Sobre el proyecto

Construido de forma autodidacta como proyecto real con caso de uso local.  
Parte de un portfolio de automatización con IA centrado en soluciones para pequeños negocios.

**Contacto:** contacto@ahorraai.com
