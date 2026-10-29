# UD01: Ejercicio — Sostenibilidad en mkdocs

!!! abstract "Objetivo del ejercicio"
    Este ejercicio **no evalúa cuánto recuerdas de la teoría de sostenibilidad**: es una excusa de contenido para que practiques con mkdocs. Lo que se valora es cómo estructuras y formateas la información en vuestro sitio, no la profundidad de vuestros conocimientos en ASG, RSC o KPIs.

    **Materiales:** vuestro proyecto mkdocs del curso · acceso a Internet para investigar

---

## Punto de partida

Elige **una empresa real** (puede ser del sector informático, o cualquier otra que os interese) que publique información sobre sostenibilidad: memoria de sostenibilidad, informe RSC, informe ASG/ESG, o una sección "sostenibilidad" en su web corporativa.

No hace falta que la analices en profundidad ni que te aprendas los conceptos de memoria — solo necesitas encontrar, en su informe o web, estos cuatro datos:

- [ ] Un criterio o acción **ambiental** concreta que mencionen.
- [ ] Un criterio o acción **social** concreta que mencionen.
- [ ] Un **grupo de interés** que citen explícitamente (empleados, comunidad local, proveedores...).
- [ ] Un **indicador o KPI** numérico que publiquen (una cifra: % de energía renovable, toneladas de CO₂, litros de agua, etc.).

---

## Lo que tienes que entregar

Crea una **página nueva** dentro de vuestro proyecto mkdocs (añádela también al `nav` del `mkdocs.yml`) documentando esa empresa. La página debe incluir, como mínimo:

- [ ] Un título y una breve introducción (2-3 líneas) de la empresa y a qué se dedica.
- [ ] Una **tabla** con los cuatro datos que has recogido (ambiental / social / grupo de interés / KPI).
- [ ] Al menos un **admonition** (`!!! note`, `!!! tip`, etc.) con algo que te haya llamado la atención, positivo o cuestionable, de lo que hayas encontrado.
- [ ] Un **enlace externo** a la fuente original (el informe o la web donde lo has encontrado).
- [ ] Una estructura de encabezados coherente (`##`, `###`) — no todo en un único bloque de texto.

!!! tip "Esto sí es lo importante del ejercicio"
    - ¿Aparece correctamente en el menú de navegación al compilar el sitio?
    - ¿Los encabezados están bien anidados (no saltas de `##` a `####` sin pasar por `###`)?
    - ¿La tabla se renderiza bien?
    - ¿El enlace funciona?

    Si algo de esto falla, es un problema de mkdocs/markdown, no de sostenibilidad — y es precisamente lo que se evalúa aquí.

---

## Opcional, si te sobra tiempo

- Añade una segunda tabla comparando tu empresa con otra del mismo sector en alguno de estos cuatro puntos.
- Prueba a usar una `!!! warning` o un bloque `??? tip` (colapsable) para algo que consideres "greenwashing" (una acción más de imagen que de fondo) — sin que esto sea tampoco el foco de la corrección.

---

## Criterios de corrección

| Aspecto | Peso |
|---|---|
| La página aparece correctamente enlazada en el `nav` | Sí / No (bloqueante) |
| Tabla bien formada y con los 4 datos pedidos | 30% |
| Uso correcto de al menos un admonition | 20% |
| Estructura de encabezados coherente | 20% |
| Enlace externo funcional a la fuente | 15% |
| Redacción propia, breve y clara (no copia-pega del informe) | 15% |

---

## ¿Alguna duda?
