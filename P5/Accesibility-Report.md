# Accessibility Report: Diseño B

## 1. Ficha Técnica del Informe

- **Nombre del proyecto:** Diseño B.
- **Normativa de referencia:** WCAG 2.2 (Nivel AA).
- **Herramientas utilizadas:** Lighthouse, WAVE.
- **Fecha de la auditoría:** 30/05/2026.
- **Nivel de conformidad:** AA, Versión WCAG 2.2 Referencia: norma UNE-EN 301549

## 2. Puntuaciones Globales (Métricas Automáticas)

- **Lighthouse Accessibility Score:** 91/100.
- **WAVE Summary:** 1 error crítico, 13 errores de contraste y 17 alertas.

## 3. Análisis por Principios (POUR)

### Perceptible

- **Error detectado:** Falta de contraste los botones.
- **Criterio WCAG incumplido:** "Criterio 1.4.3 - Contraste mínimo".
- **Impacto:** "Los usuarios con visión baja no pueden identificar la acción principal".
- **Recomendación de mejora:** "Cambiar el color del texto de naranja muy claro a negro (#000000)".
 
---

- **Error detectado:** Texto alternativo redundante en imágenes.
- **Criterio WCAG incumplido:** "Criterio 1.1.1: Contenido no textual".
- **Impacto:** "Los usuarios se ven obligados a leer exactamente la misma información dos veces, lo cual genera una navegación tediosa, confusa y lenta".
- **Recomendación de mejora:** "Añadir texto alternativo más detallado".

### Robusto

- **Error detectado:** Falta de etiqueta en el buscador.
- **Criterio WCAG incumplido:** "Criterio 3.3.2 - Etiquetas".
- **Impacto:** "Los usuarios pueden no estar seguros de qué información se espera que introduzcan ahí ".
- **Recomendación de mejora:** "Añadir una etiqueta al buscador".

## 4. Tabla de Hallazgos y Prioridades

| **ID** | **Prioridad** | **Criterio WCAG** | **Error detectado** | **Recomendación Técnica** |
|---|---|---|---|---|
| **ACC-01** | Crítica | Criterio 1.4.3 - Contraste mínimo | Texto naranja claro sobre botón naranja | Cambiar el color del texto de naranja muy claro a negro (#000000) |
| **ACC-02** | Alta | Criterio 1.1.1: Contenido no textual | Texto alternativo redundante en imágenes | Añadir texto alternativo más detallado |
| **ACC-03** | Alta | Criterio 3.3.2 - Etiquetas | Falta una etiqueta en el buscador de hamburguesas | Añadir una etiqueta al buscador |

## 5. Conclusiones y Declaración de Conformidad

**¿Es el sitio accesible?:** 

El sitio cumple parcialmente con el nivel AA ya que a pesar de obtener un muy buen resultado en Lighthouse Accessibility Score (91/100)
no se cumplen todos los criterios, presentando una serie de barreras críticas a nivel de percepción visual debido a la falta de contraste en los botones
y el texto alternativo redundante en imágenes y a nivel de usabilidad del buscador al no tener información de que se debe introducir.

  **Próximos pasos:**
  - **Acción de contraste:** Modificar el color del texto de los botones principales (cambiando de naranja muy claro a negro #000000) para resolver el problema de
    la percepción visual y garantizar que lo puedan ver los usuarios con baja visión.
  - **Acción de identificación:** Insertar una etiqueta en el buscador de hamburguesas para que todos los que accedan a la página identifiquen claramente la
    información que se espera introducir.
  - **Acción de contenido de las imágenes:** Cambiar el texto alternativo de las imágenes de la página web para eliminar las descripciones redundantes, evitando
    así la navegación tediosa, confusa y lenta.
