# Métricas e Hipótesis – iUpi MVP

Este documento define qué se mide, por qué se mide y cómo se utilizarán los datos para validar la propuesta de valor del MVP.

El objetivo del MVP no es escalar, sino aprender.

---

## 1. Objetivo de Medición

Validar si:

- La propuesta de valor es clara.
- La comunicación genera confianza.
- Los usuarios entienden qué hace iUpi.
- Los canales atraen tráfico calificado.
- Existe intención real de uso.

---

## 2. Hipótesis Principales

### H1 – Humanización

Si humanizamos la comunicación (tono cercano, menos institucional), aumenta la confianza y mejora la tasa de registro.

**Indicador asociado:**  
Aumento en conversion rate desde redes sociales.

---

### H2 – Producto Visible

Si mostramos el simulador en uso (capturas reales, explicación paso a paso), disminuye la fricción y el abandono.

**Indicador asociado:**  
Reducción en abandono de landing o formulario.

---

### H3 – Claridad del CTA

Si el CTA explica claramente el beneficio (“Practicar sin riesgo”) en lugar de ser genérico (“Registrate”), mejora la conversión.

**Indicador asociado:**  
Incremento en CTR y en tasa de registro.

---

### H4 – Medición por Canal

Si identificamos correctamente el canal de origen (Instagram, LinkedIn, X, Facebook), podremos optimizar adquisición hacia el canal con mayor conversión.

**Indicador asociado:**  
Registros segmentados por canal + comparación de conversion rate.

---

## 3. Métricas Clave

### 3.1 Métricas de Conversión

- **Conversion Rate (CR):** visitas → registros.
- **Tasa de abandono del formulario.**
- **Registros por canal.**

---

### 3.2 Métricas de Adquisición

- CTR desde redes sociales.
- Clics en link de bio.
- Tráfico por canal (UTM).

---

### 3.3 Métricas de Calidad

- Tiempo en página.
- Scroll depth.
- Respuestas a encuestas breves (si se implementan).
- Mensajes directos recibidos.

---

## 4. Implementación Técnica (MVP)

Para poder medir correctamente:

- Uso de UTMs diferenciadas por canal.
- Landing única con parámetros dinámicos.
- Registro de fuente en base de datos.
- Comparación semanal antes / después de cambios.

Ejemplo de estructura:

- /registro?canal=instagram
- /registro?canal=linkedin

---

## 5. Método de Análisis

1. Implementar cambio.
2. Medir durante 7–14 días.
3. Comparar contra baseline.
4. Decidir si:
   - Se mantiene.
   - Se itera.
   - Se descarta.

Sin datos, no hay decisión.

---

## 6. Qué NO medir (en esta etapa)

- Likes.
- Seguidores.
- Alcance sin conversión.
- Métricas de vanidad.

En etapa MVP importa:

Confianza → Registro → Intención.

---

## 7. Principio Fundamental

Las métricas no se usan para “reportar números”,  
se usan para aprender y tomar decisiones.

El MVP existe para validar hipótesis, no para escalar volumen.
