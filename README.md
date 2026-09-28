Célula 7 — Mercadeo, Campañas y Fidelización

Bienvenido al repositorio del proyecto. Este módulo está diseñado para gestionar las estrategias de mercadeo, ejecución de campañas publicitarias y programas de fidelización de clientes.

---

 Integrantes y Asignación de Roles

A continuación se detallan los roles y responsabilidades de los 5 integrantes del equipo de la Célula 7:

 1.Miguel Gómez  
Responsabilidades:
  * Coordinación de la célula y control del flujo de trabajo en Git (`main`, `develop`, `feature/*`).
  * Revisión y aprobación de Pull Requests (PRs).
  * Arquitectura base del proyecto y definición de estándares de código.

2. [andres 2]
Responsabilidades:
  * Diseñar e implementar la interfaz para la creación y gestión de campañas publicitarias.
  * Desarrollar vistas para la segmentación de audiencia y programación de lanzamientos.
  * Consumo de APIs relativas al módulo de campañas.

3.[jean steven 3]** — 
Responsabilidades:
  * Crear la lógica de negocio para la acumulación y redención de puntos/beneficios.
  * Diseñar la estructura de datos para el historial de compras y clientes fidelizados.
  * Desarrollar endpoints para la gestión de recompensas.

 4.[jose 4]
Responsabilidades:
  * Crear APIs para la generación de reportes y métricas de rendimiento de campañas (ROI, conversiones).
  * Lógica para el envío masivo de correos/notificaciones de promociones.
  * Integración con la base de datos principal.

5. [juan camilo 5]
 Responsabilidades:
  * Pruebas funcionales de los módulos de campañas y fidelización.
  * Redacción de la documentación técnica del repositorio y modelos de base de datos.
  * Asegurar la consistencia visual y la experiencia de usuario (UX) en el módulo.



Flujo de Trabajo en Git

1. **Ramas Principales:**
   * `main`: Código en producción y estable.
   * `develop`: Rama de integración para todas las características trabajadas.
2. **Desarrollo de Funcionalidades:**
   * Crear una rama a partir de `develop`: `feature/nombre-funcionalidad`.
   * Realizar los cambios necesarios y subir la rama a su respectivo *fork*.
3. **Integración:**
   * Generar un **Pull Request (PR)** desde la rama `develop` de su *fork* hacia la rama `develop` del repositorio principal.