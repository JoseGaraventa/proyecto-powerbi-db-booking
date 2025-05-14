# Análisis de Reservas Hoteleras y Contexto Económico

📊 **Proyecto en Power BI** | Autor: José Manuel Garaventa  
🎓 Licenciado en Turismo |  Data Analytics Jr  
🌍 En búsqueda de oportunidades

---

## 🎯 Objetivo del Proyecto

El proyecto analiza reservas hoteleras y sus cancelaciones para identificar patrones de comportamiento y evaluar el impacto de variables económicas (inflación, PBI, desempleo, etc.) sobre la demanda. El enfoque está pensado para asistir la toma de decisiones a nivel **operativo, táctico y estratégico** en la gestión hotelera.

---

## 🧠 Alcance del Análisis

El modelo combina datos **internos** (reservas, cancelaciones, perfiles de cliente) con datos **externos** (variables macroeconómicas) para:

- Identificar segmentos críticos.
- Evaluar riesgos de cancelación o cambios.
- Proyectar tendencias de demanda hotelera por país y contexto económico.

---

## 🗃️ Modelo de Datos

El análisis se basa en 3 tablas principales:

- **Reserva**: tipo de hotel, fechas, anticipación, cambios, régimen, etc.
- **Cliente**: país, segmento, historial de reservas/cancelaciones, tipo de cliente.
- **Variables Económicas**: inflación, desempleo, ingresos disponibles, PBI, precios del combustible, IPC hotelero.

Relaciones clave:
- Un cliente puede tener múltiples reservas.
- Cada cliente se asocia a un único contexto económico según su país y fecha.

---

## 📈 Estructura del Dashboard

El informe consta de 4 páginas interactivas en Power BI:

1. **Visión General de la Demanda**  
   Evolución de reservas y cancelaciones, tipo de hotel, noches de estadía, segmentado por tipo de cliente.

2. **Análisis del Cliente**  
   Comparación entre clientes frecuentes y no frecuentes, origen de reservas, estacionalidad y nivel de complejidad (según historial de cambios).

3. **Impacto de Variables Económicas**  
   Relación entre reservas y factores macroeconómicos (IPC, inflación, ingresos disponibles, PBI), clasificados por cuartiles.

4. **Mapa Económico del Turismo**  
   Visualización geográfica del comportamiento turístico por país, con ranking de reservas y comparación entre cuartiles económicos.

---

## ⚙️ Ejemplos de Métricas Utilizadas

- `Anticipación Promedio`  
- `Índice de Intensidad de Uso`  
- `Clientes con Muchos Cambios` (medida dinámica basada en umbral configurable)

---

## 🔗 Visualización

El informe está disponible en Power BI Desktop. Proximamente publicaré una versión en Power BI Service/Tableau Public.

---

Gracias por visitar mi repositorio. Si estás buscando un perfil con conocimientos en **turismo y análisis de datos**, no dudes en contactarme.

📬 **Contacto**: garaventajosemanuel@gmail.com
