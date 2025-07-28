# 📲 User Behavior Analysis in Food App – Sprint 11

This project explores how users interact with the mobile application of a foodtech startup, identifying friction points within the conversion funnel and evaluating the impact of a typographic redesign through an A/A/B experiment.

---

### Análisis de Comportamiento de Usuario en App de Alimentos – Sprint 11

Este proyecto explora cómo los usuarios interactúan con la aplicación de una empresa emergente de productos alimenticios, identificando puntos de fricción en el embudo de conversión y evaluando el impacto de un rediseño tipográfico mediante un experimento A/A/B.

---

## ¿De qué trata?

- Se analiza el recorrido de los usuarios dentro de la app, desde su primer evento hasta la etapa de compra.
- Se detectan las etapas donde más usuarios abandonan el proceso.
- Se evalúa si un cambio en la tipografía afecta el comportamiento de los usuarios, comparando tres grupos experimentales.

---

## Desglose del análisis

1. **Exploración inicial**  
   - Limpieza de datos, revisión de fechas y eventos registrados.
   - Validación de la cobertura temporal y exclusión de datos incompletos.

2. **Embudo de conversión**  
   - Identificación de eventos clave y su frecuencia.
   - Cálculo de proporciones entre etapas para detectar pérdidas de usuarios.
   - Estimación del porcentaje que completa el recorrido hasta el pago.

3. **Evaluación del experimento A/A/B**  
   - Comparación entre dos grupos de control para validar la aleatorización.
   - Pruebas estadísticas para detectar diferencias significativas.
   - Análisis del grupo de prueba con tipografía nueva frente a los controles.

---

## Herramientas utilizadas

- Python (pandas, matplotlib, scipy)
- Visualización de datos y análisis exploratorio
- Pruebas estadísticas para validación experimental
- Storytelling analítico orientado a decisiones de diseño

---

## Conclusiones

- Se identificó la etapa crítica del embudo donde se pierde la mayor cantidad de usuarios.
- Los grupos de control fueron estadísticamente equivalentes, validando el diseño experimental.
- El cambio tipográfico no generó diferencias significativas en el comportamiento de los usuarios.
- Se recomienda mantener el diseño actual o realizar pruebas adicionales antes de implementar cambios visuales.

