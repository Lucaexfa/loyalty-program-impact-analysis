# loyalty-program-impact-analysis


📌 **Notebook interactiva (sin instalar nada):**  
👉 Ver el análisis completo y ejecutado en Kaggle:  
[https://www.kaggle.com/code/lucaexequielfarias/loyalty-program-impact-analysis]

---

## Objetivo del proyecto
Evaluar el impacto del programa de fidelización en el comportamiento de compra
de los clientes, analizando si dicho programa genera cambios en:
- el gasto promedio por compra
- la recurrencia de compra por cliente

El objetivo es determinar si el programa aporta un beneficio medible para el
comercio o si su efecto se limita al otorgamiento de descuentos.

---

## Dataset
Se utiliza un dataset público obtenido de Kaggle con información transaccional
de clientes, incluyendo montos de compra, descuentos aplicados y pertenencia
al programa de fidelización.

Debido al tamaño del dataset, el análisis se presenta principalmente a través
de la notebook interactiva, que puede visualizarse directamente en Kaggle.

---

## Metodología de análisis

El análisis se desarrolló siguiendo un enfoque estructurado:

1. **Preparación de datos**
   - Carga del dataset original
   - Limpieza y validación de datos
   - Generación de una tabla limpia para análisis

2. **Análisis del ticket promedio**
   - Comparación del gasto promedio antes y después de descuentos
   - Comparación entre clientes fidelizados y no fidelizados

3. **Análisis de la efectividad del programa**
   - Medición de recurrencia por cliente utilizando identificadores únicos
   - Comparación de la frecuencia promedio de compra entre ambos grupos

4. **Visualización e interpretación**
   - Uso de gráficos únicamente cuando aportan valor analítico
   - Interpretación basada en evidencia, evitando conclusiones forzadas

---

## Principales hallazgos

- El programa de fidelización **no muestra un impacto significativo** en el
  gasto promedio por compra.
- No se observan diferencias en la **recurrencia promedio** entre clientes
  fidelizados y no fidelizados.
- La principal diferencia detectada es un **mayor nivel de descuentos**
  otorgados a los clientes que participan del programa.

---

## Conclusión

En función de las métricas analizadas, el programa de fidelización no genera
cambios observables en el comportamiento de compra de los clientes en términos
de gasto ni frecuencia. Su efecto se limita principalmente a otorgar beneficios
económicos al cliente, sin evidencia de un retorno directo para el comercio.

---

## Recomendaciones

- Revisar la estructura de descuentos del programa y alinearla con objetivos
  de negocio concretos, como mayor frecuencia o gasto acumulado.
- Implementar incentivos condicionados a comportamientos específicos.
- Segmentar el programa de fidelización según el perfil del cliente.
- Incorporar métricas temporales para evaluar retención y valor a largo plazo.

---

## Notas finales
Este proyecto se presenta con un enfoque analítico y de negocio, priorizando la
interpretación de resultados y la toma de decisiones basada en datos.
La notebook en Kaggle permite revisar el análisis completo de forma directa,
sin necesidad de configuraciones técnicas.
