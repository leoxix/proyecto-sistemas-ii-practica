# Guía de Reutilización (InnerSource): Plantilla de Requisitos y Casos de Prueba

## 1. Descripción del recurso compartible
Este documento define una **plantilla genérica de especificación de requisitos y casos de prueba** extraída de las prácticas de **Proyecto de Sistemas II** (Carrera de Ingeniería de Sistemas)[cite: 1, 3]. Su propósito es permitir que otros equipos del curso o de la organización adopten una estructura uniforme para documentar funcionalidades y validar su comportamiento sin partir desde cero[cite: 3].

Este recurso está elaborado de forma **genérica y libre de datos confidenciales**: no incluye contraseñas, tokens, claves API, URLs internas privadas, datos personales ni información específica de un cliente o base de datos real.

## 2. Instrucciones de uso
1. Copie el bloque de plantilla base (al final de esta guía) hacia su propio repositorio o carpeta de documentación (por ejemplo, `docs/plantilla-requisitos-pruebas.md`).
2. Reemplace los marcadores `[EJEMPLO_...]` con los datos reales de su módulo o sistema.
3. Redacte los requisitos funcionales y no funcionales de manera verificable (qué debe hacer el sistema y bajo qué condiciones).
4. Complete los casos de prueba incluyendo entradas, precondiciones y resultado esperado antes de dar por cerrada la tarea.

### Plantilla base sugerida
- **Identificador y nombre del módulo:** `[MOD-01 - Nombre del módulo]`
- **Objetivo:** `[Describir brevemente qué resuelve este módulo]`
- **Requisito funcional asociado:** `[RF-XX: El sistema debe permitir...]`
- **Requisito no funcional asociado:** `[RNF-XX: Validación, rendimiento o seguridad aplicable]`
- **Caso de prueba:**
  - **ID:** `[CP-01]`
  - **Precondiciones:** `[Estado inicial requerido]`
  - **Datos / Acción:** `[Entrada o pasos ejecutados]`
  - **Resultado esperado:** `[Salida o comportamiento correcto]`

## 3. Reglas para proponer modificaciones
- **Trabaje siempre en una rama separada:** No realice cambios directos sobre la rama principal (`main`)[cite: 1]; cree una rama descriptiva, por ejemplo `innersource/mejora-plantilla-pruebas`.
- **Mantenga el carácter genérico:** Toda propuesta debe seguir siendo aplicable a distintos equipos y no incorporar datos sensibles, credenciales ni reglas rígidas de un único proyecto[cite: 3, 4].
- **Abra un Pull Request descriptivo:** Explique qué problema resuelve la mejora, qué secciones se modificaron y qué beneficio aporta a otros equipos[cite: 2, 3].
- **Respete la estructura mínima:** Conserve las secciones de identificación, requisitos y casos de prueba para no romper la compatibilidad de quienes ya usan la plantilla.

## 4. Responsables de revisión y mantenimiento
- **Mantenedor / Revisor principal:** `[Nombre o rol del encargado de documentación/calidad del equipo]`[cite: 3]
- **Revisor secundario:** `[Nombre o rol de un compañero del equipo o integrante designado]`[cite: 2, 3]
- **Política de revisión y mantenimiento:** Los Pull Requests propuestos sobre este archivo serán revisados en un plazo máximo de 48 horas verificando claridad, ausencia de datos sensibles y utilidad general[cite: 3, 4]. Al cierre de cada iteración o hito del proyecto se revisará si la guía requiere ajustes adicionales.