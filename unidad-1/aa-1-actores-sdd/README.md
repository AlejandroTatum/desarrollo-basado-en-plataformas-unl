# AA 1 — Análisis de actores y fundamentos de Spec-Driven Development

| | |
| --- | --- |
| **Unidad** | 1 |
| **Práctica** | Actividad autónoma 1: actores del problema y fundamentos de SDD |
| **Proyecto analizado** | Proyecto 7 del banco académico: Sistema de gestión de prácticas preprofesionales |
| **Modalidad** | Individual |
| **Informe** | [documento/analisis-de-actores-y-fundamentos-de-spec-driven-development-sistema-de-gestion-de-practicas-preprofesionales-v001.pdf](documento/analisis-de-actores-y-fundamentos-de-spec-driven-development-sistema-de-gestion-de-practicas-preprofesionales-v001.pdf) |
| **Bibliografía** | [referencias.bib](referencias.bib) |

## 1. Enunciado y objetivo

Analizar el problema asignado al equipo identificando y caracterizando a sus actores, y explicar los fundamentos de Spec-Driven Development (SDD) y su relación con el flujo de GitHub Spec Kit (constitution, specify, clarify, plan, tasks). El informe parte del alcance MVP acordado en la ACD1: desde la práctica ya asignada hasta su cierre.

## 2. Contenido del informe

| Sección | Contenido |
| --- | --- |
| 1. Identificación del proyecto | Propósito del sistema y alcance MVP acordado en la ACD1. |
| 2. Mapa de actores | Figura con los ocho actores, los cinco momentos del proceso y las relaciones entre actores. |
| 3. Caracterización de actores | Tabla con clasificación, necesidad, interacción, información y restricciones de cada actor. |
| 4. Fundamentos de SDD | Problema, requisito, especificación y solución técnica, con ejemplos del proyecto. |
| 5. Relación con GitHub Spec Kit | Función, artefacto y relación con SDD de cada comando. |
| 6. Preguntas de clarificación | Seis preguntas abiertas antes de diseñar. |
| 7. Declaración de uso de IA | Herramienta usada y alcance de su uso. |

## 3. Herramientas de IA

| Herramienta | Uso |
| --- | --- |
| Agente de programación el Gentleman (Pi) con modelo Claude | Lectura de la guía, búsqueda y verificación de fuentes, borrador del informe y código del mapa de actores. |
| Subagente verificador del mismo agente | Verificación independiente del informe contra la guía y la rúbrica. |

La IA ejecutó; los actores, su clasificación, las preguntas y cada cambio los decidió el estudiante a partir del proyecto y de los acuerdos de la ACD1.

## 4. Proceso con IA

1. Lectura de la guía y conversión de cada actividad en un chequeo verificable.
2. Búsqueda de fuentes: se verificaron por DOI o ISBN los artículos y libros, y la documentación de Spec Kit por su URL; quedaron 7 citadas.
3. Borrador breve con tablas en lugar de párrafos largos.
4. Verificación independiente: requisito por requisito de la guía, con cita textual del informe como evidencia.
5. Aprobación del borrador, PDF en formato de actividad autónoma e inspección visual de cada página.

## 5. Errores de la IA y correcciones

- **Mapa de actores demasiado básico:** la primera versión usaba cajas redondeadas en colores pastel y etiquetas de leyenda que se veían genéricas. Se redibujó con un estilo técnico sobrio: tipo de actor como rótulo, flechas con sentido y línea punteada para lo que queda fuera del MVP.
- **Fuente marcada como no verificada:** el artículo de Piskala sobre SDD tiene DOI de arXiv, que no figura en Crossref. Se verificó en DataCite.
- **Portada rechazada por error:** el validador confundía la palabra "Desarrollo" del nombre de la asignatura con el inicio del cuerpo. Se corrigió la regla del validador.
- **Espacio en blanco alrededor del mapa:** se probó fijar la figura junto a su texto, pero el hueco solo se movía a la página siguiente. Se dejó la figura sola y centrada en su propia página.
