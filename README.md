# [Sistema] - Proyecto de Sistemas II

## Descripción general
Este repositorio contiene la documentación y los recursos de apoyo del sistema desarrollado para la asignatura **Proyecto de Sistemas II** (Carrera de Ingeniería de Sistemas)[cite: 1]. El sistema busca resolver [indicar el problema principal del proyecto, por ejemplo: la gestión de pedidos, inventario o registros del área asignada] de forma ordenada, trazable y mantenible.

## Requisitos principales del sistema

### Requisitos funcionales (RF)
- **RF-01 (Gestión de usuarios y accesos):** Permitir el inicio de sesión y el control de acciones según el rol asignado.
- **RF-02 (Gestión de registros principales):** Crear, consultar, actualizar y dar de baja los registros centrales del dominio del sistema.
- **RF-03 (Búsqueda y filtrado):** Localizar registros rápidamente mediante criterios clave o filtros.
- **RF-04 (Reportes o exportación):** Generar vistas o reportes resumidos para seguimiento y control.

### Requisitos no funcionales (RNF)
- **RNF-01 (Seguridad):** Proteger credenciales, evitar exponer secretos o claves en el código y exigir autenticación válida.
- **RNF-02 (Mantenibilidad y trazabilidad):** Mantener código modular, documentación actualizada e historial claro de cambios en Git.
- **RNF-03 (Usabilidad y rendimiento):** Ofrecer una interfaz clara y tiempos de respuesta ágiles en las operaciones habituales.

## Flujo de trabajo con Git y Pull Requests
1. Nunca realizar cambios directos sobre la rama `main`[cite: 1].
2. Crear una rama descriptiva a partir de la rama de trabajo correspondiente (por ejemplo, `docs-mejora-proyecto` o `feat/...`).
3. Registrar commits con mensajes claros y descriptivos[cite: 2].
4. Abrir un Pull Request detallando el cambio realizado y solicitar revisión antes de integrar[cite: 2].