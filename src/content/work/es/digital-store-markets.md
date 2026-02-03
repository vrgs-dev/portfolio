---
company: 'Digital Store Markets'
role: 'Desarrollador Full Stack'
dateStart: 2024-05-01
dateEnd: 2024-07-01
lang: 'es'
translationKey: 'digital-store-markets-fullstack'
---

Desarrollo backend de una plataforma de e-commerce con Python y Flask. Responsable de la arquitectura de servicios para catálogo, precios dinámicos y procesamiento de órdenes en un entorno con picos de tráfico estacionales.

Resultados clave

- Arquitectura del motor de órdenes con máquina de estados explícita, validaciones optimistas de stock y operaciones idempotentes que eliminaron el doble procesamiento en pagos.
- Diseño de sistema de precios dinámicos con reglas configurables por categoría y promoción, soportando actualizaciones masivas sin downtime.
- Optimización del rendimiento de catálogo bajo carga (índices compuestos, materialización de vistas, paginación por cursor) con mejoras del ~40% en tiempos de respuesta.
- Implementación de test suite de integración con fixtures reproducibles, cubriendo flujos completos de compra y edge cases de concurrencia.
