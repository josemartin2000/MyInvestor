# MyInvestor · Sistema de valoración de acciones

**Versión:** v1.01  
**Estado:** Vivo  
**Objetivo:** disponer de un método común, reutilizable y comparable para evaluar el **atractivo de invertir hoy** en una acción.

---

## 1. Qué mide este sistema

La nota final **no pretende decir si una empresa es “buena” o “mala”**.

Mide otra cosa:

> **¿Qué tan atractiva resulta esta acción como inversión en este momento, considerando precio, calidad, caja, crecimiento, riesgo y momento de entrada?**

Esto permite separar dos ideas que a menudo se mezclan:

- **Calidad de la empresa**
- **Atractivo de la inversión al precio actual**

Una compañía excelente puede ofrecer una mala entrada si cotiza demasiado cara.  
Una compañía temporalmente castigada puede ofrecer una oportunidad si el precio compensa suficientemente sus riesgos.

---

## 2. Estructura de valoración

La puntuación final se calcula sobre **10 puntos** mediante seis bloques ponderados.

| Bloque | Peso | Qué evalúa |
|---|---:|---|
| **Valoración** | **25 %** | Precio pagado frente a beneficios, caja y valoración histórica/sectorial |
| **Calidad del negocio** | **20 %** | Rentabilidad del capital, márgenes, ventajas competitivas y fortaleza del negocio |
| **Balance y caja** | **15 %** | Generación de caja, deuda, liquidez y sostenibilidad financiera |
| **Crecimiento / tendencia** | **20 %** | Evolución de ventas, beneficios y segmentos relevantes |
| **Riesgo / visibilidad** | **10 %** | Incertidumbre, competencia, guidance y riesgos estructurales |
| **Momento de entrada** | **10 %** | Comportamiento reciente del precio, suelo, acumulación y reacción a catalizadores |

**Total: 100 %**

### Fórmula

> **Nota final = Σ (Nota de cada bloque × Peso del bloque)**

Cada bloque se puntúa de **0 a 10**.

---


# 2.1 Filtro previo de oportunidades

Antes de realizar una valoración completa, MyInvestor puede usar un **filtro previo de búsqueda** para localizar compañías que merezcan estudio.

Este filtro **no forma parte de la nota final** y no modifica los pesos del sistema.

Su objetivo es detectar posibles discrepancias entre:

> **percepción del mercado** y **realidad fundamental**

Se priorizarán para estudio situaciones como:

- caída fuerte de cotización;
- narrativa claramente negativa;
- miedo o pánico alrededor de la empresa o del sector;
- resultados, caja o balance mejores de lo que sugiere la cotización;
- eventos temporales que puedan estar exagerando el castigo;
- revisiones muy negativas de expectativas;
- reacción desproporcionada a malas noticias.

Puede utilizarse una etiqueta cualitativa de sentimiento:

- **Muy negativo**
- **Negativo**
- **Neutral**
- **Positivo**
- **Euforia**

Esta etiqueta es descriptiva. **No suma ni resta puntos** en la valoración.

Regla de trabajo:

> **El pánico indica dónde mirar; los fundamentales y la valoración determinan si existe oportunidad.**

No se debe comprar una empresa únicamente porque exista miedo, mala prensa o una gran caída. El objetivo es identificar si el mercado puede estar descontando un deterioro mayor que el razonablemente justificable por los fundamentales.


# 2.2 Capa Buffett de convicción y durabilidad

Además de la puntuación cuantitativa/semi-cuantitativa, MyInvestor incorpora una **capa Buffett cualitativa**. Esta capa **no modifica la fórmula ni los pesos** de la nota final.

Busca responder a una pregunta distinta:

> **¿Es este un negocio que entenderíamos y querríamos seguir manteniendo durante muchos años si el mercado cerrase temporalmente?**

Evaluar:

- **Círculo de competencia:** claridad sobre cómo gana dinero y cuáles son sus verdaderos motores económicos.
- **Durabilidad del moat:** fortaleza probable de la ventaja competitiva a 10 años, no solo hoy.
- **Owner earnings:** calidad del FCF económico, ajustando cuando corresponda por SBC, capital circulante extraordinario y capex realmente necesario.
- **Economía por acción:** crecimiento de EPS, FCF y valor intrínseco por acción; considerar dilución o reducción de acciones.
- **Asignación de capital:** disciplina en reinversión, recompras, dividendos, deuda y adquisiciones.
- **Visibilidad a largo plazo:** cuánto depende la tesis de tecnologías, regulación o cambios competitivos difíciles de proyectar.

Campos cualitativos estándar:

| Campo | Valores |
|---|---|
| **Convicción Buffett** | Alta · Media · Baja |
| **Asignación de capital** | Excelente · Buena · Mixta · Débil |

La Convicción Buffett **no suma ni resta puntos**. Sirve para ordenar prioridades cuando dos empresas tienen notas parecidas o cuando una nota elevada depende de una tesis estructural difícil de prever.

Ejemplo conceptual:

- empresa A: 7,8/10 + Convicción Alta → candidata prioritaria;
- empresa B: 7,9/10 + Convicción Media/Baja → puede quedar por detrás pese a su nota superior.

Regla:

> **La nota mide atractivo actual; la Convicción Buffett mide cuánto confiamos en la durabilidad económica del negocio.**

# 2.3 Prioridad de inversión

MyInvestor puede mantener un ranking de **Prioridad de inversión** separado de la nota total.

La prioridad combina:

- nota MyInvestor;
- margen de seguridad actual;
- Convicción Buffett;
- asignación de capital;
- proximidad de catalizadores/resultados;
- riesgo de disrupción;
- convicción personal del usuario.

No es una fórmula automática ni una recomendación irrevocable. Debe actualizarse cuando cambien precio, resultados, guidance o tesis.

---

# 3. Cómo puntuar cada bloque

## 3.1 Valoración · 25 %

Evalúa cuánto estamos pagando por el negocio **hoy**.

Indicadores principales:

- PER histórico
- PER forward
- FCF yield
- Price / Free Cash Flow
- EV/EBIT o EV/EBITDA cuando aporte valor
- Comparación con su propia historia
- Comparación con empresas comparables
- Diferencia entre precio actual y valoración razonable

### Lectura orientativa

| Nota | Interpretación |
|---:|---|
| 9–10 | Valoración excepcionalmente deprimida sin deterioro equivalente |
| 7–8 | Claramente atractiva |
| 5–6 | Razonable / aproximadamente justa |
| 3–4 | Exigente |
| 0–2 | Muy cara o valoración difícil de justificar |

**Regla importante:** una caída fuerte de cotización no implica automáticamente valoración barata si los beneficios también han caído.

---

## 3.2 Calidad del negocio · 20 %

Evalúa la calidad económica estructural de la empresa.

Indicadores:

- ROIC
- ROE cuando sea relevante
- Márgenes brutos y operativos
- Estabilidad de márgenes
- Capacidad de fijación de precios
- Marca / moat / propiedad intelectual
- Recurrencia de ingresos
- Posición competitiva
- Diversificación geográfica y de producto
- Capacidad de reinversión rentable
- Durabilidad del moat a 10 años
- Calidad de la asignación de capital

### Lectura orientativa

| Nota | Interpretación |
|---:|---|
| 9–10 | Negocio excepcional, ventajas muy fuertes |
| 7–8 | Negocio de alta calidad |
| 5–6 | Calidad correcta, con limitaciones |
| 3–4 | Negocio débil o muy cíclico |
| 0–2 | Calidad estructural muy baja |

---

## 3.3 Balance y caja · 15 %

Evalúa la capacidad financiera para atravesar periodos difíciles y financiar crecimiento.

Indicadores:

- Operating Cash Flow
- Free Cash Flow
- Conversión beneficio → caja
- Deuda neta
- Deuda / EBITDA
- Cobertura de intereses
- Current ratio cuando sea útil
- Vencimientos de deuda
- Liquidez disponible
- Sostenibilidad de dividendos y recompras
- Owner earnings cuando el FCF reportado pueda estar distorsionado por SBC, circulante o capex extraordinario

### Lectura orientativa

| Nota | Interpretación |
|---:|---|
| 9–10 | Balance muy fuerte y abundante caja |
| 7–8 | Situación financiera sólida |
| 5–6 | Correcta, pero con alguna presión |
| 3–4 | Deuda o caja preocupantes |
| 0–2 | Riesgo financiero elevado |

---

## 3.4 Crecimiento / tendencia · 20 %

Evalúa si el negocio está mejorando, estabilizándose o deteriorándose.

Indicadores:

- Crecimiento de ingresos
- Crecimiento del EPS
- Crecimiento de FCF
- Evolución orgánica
- Volumen vs precio
- Evolución de segmentos y geografías
- Nuevos productos
- Guidance
- Revisiones de estimaciones

### Lectura orientativa

| Nota | Interpretación |
|---:|---|
| 9–10 | Crecimiento fuerte y sostenible |
| 7–8 | Crecimiento sólido |
| 5–6 | Estable o crecimiento moderado |
| 3–4 | Contracción relevante |
| 0–2 | Deterioro fuerte y persistente |

En empresas en turnaround, este bloque es especialmente importante.

---

## 3.5 Riesgo / visibilidad · 10 %

Evalúa cuánto depende la tesis de elementos todavía no demostrados.

Factores:

- Guidance
- Competencia
- Riesgo regulatorio
- Concentración geográfica
- Concentración de clientes/productos
- Disrupción tecnológica
- Dependencia de un turnaround
- Riesgos de ejecución
- Litigios materiales
- Divisa
- Ciclo económico

### Interpretación de la nota

Aquí **una nota alta significa menor riesgo y mayor visibilidad**.

| Nota | Interpretación |
|---:|---|
| 9–10 | Alta visibilidad y riesgos muy controlados |
| 7–8 | Riesgos manejables |
| 5–6 | Incertidumbre media |
| 3–4 | Incertidumbre elevada |
| 0–2 | Tesis muy incierta |

---

## 3.6 Momento de entrada · 10 %

No intenta predecir el mercado. Evalúa si existe evidencia de que la presión vendedora está disminuyendo.

Aspectos:

- Tendencia principal
- Mínimos y máximos
- Formación de suelo
- Lateralización / acumulación
- Volumen
- Reacción a resultados
- Reacción a malas noticias
- Recuperación de soportes relevantes
- Confirmación de mínimos crecientes

### Lectura orientativa

| Nota | Interpretación |
|---:|---|
| 9–10 | Tendencia favorable y entrada técnicamente muy sólida |
| 7–8 | Señales claras de recuperación |
| 5–6 | Neutral / estabilización incipiente |
| 3–4 | Tendencia bajista todavía activa |
| 0–2 | Caída fuerte sin signos de estabilización |

**Importante:** este bloque solo pesa el 10 %. Una buena empresa barata no deja de ser interesante por no tener un gráfico perfecto.

---

# 4. Interpretación de la nota final

| Puntuación | Lectura |
|---:|---|
| **8,0–10,0** | Oportunidad excepcional / muy atractiva |
| **7,0–7,9** | Atractiva |
| **6,0–6,9** | Interesante, pero con alguna condición relevante |
| **5,0–5,9** | Vigilar / todavía no suficientemente clara |
| **4,0–4,9** | Poco atractiva actualmente |
| **< 4,0** | Riesgo/precio no compensan |

La nota **no es una orden automática de compra o venta**. Sirve para:

- comparar acciones;
- identificar qué bloque impide una entrada;
- observar cómo cambia la tesis con el tiempo;
- diferenciar deterioro del negocio de caída del precio;
- evitar comprar únicamente porque una acción ha caído mucho.

---

# 5. Reglas de uso

## 5.1 Siempre usar datos actuales

Cada valoración debe registrar:

- fecha;
- precio aproximado;
- último ejercicio disponible;
- últimos resultados trimestrales;
- guidance vigente;
- métricas forward cuando existan.

---

## 5.2 No duplicar el mismo problema

Un mismo hecho no debe penalizarse de forma exagerada en varios bloques.

Ejemplo:

Si una caída de ventas reduce el EPS futuro:

- afecta a **Crecimiento**;
- puede afectar a **Valoración** porque cambia el PER forward;
- pero no debe restarse nuevamente en todos los bloques sin motivo adicional.

---

## 5.3 Forward antes que histórico

Para decidir si una acción está barata, debe darse especial importancia a:

- beneficio esperado;
- FCF esperado;
- guidance;
- tendencia de márgenes.

Los múltiplos históricos son contexto, no la única referencia.

---

## 5.4 Turnaround

En una empresa en recuperación, la pregunta central es:

> **¿El precio ya compensa suficientemente el deterioro actual y existe evidencia de estabilización?**

No es necesario que el negocio haya recuperado completamente.

---

## 5.5 Calidad ≠ oportunidad

Una acción puede obtener:

- **9/10 en Calidad**
- pero **4/10 en Valoración**

o:

- **6/10 en Calidad**
- pero **9/10 en Valoración**

La nota final busca combinar ambas dimensiones.

---

# 6. Plantilla para nuevas acciones

## [Empresa] · [Ticker]

**Fecha:**  
**Precio aproximado:**  
**Tesis:**  

| Área | Peso | Nota | Aportación |
|---|---:|---:|---:|
| Valoración | 25 % |  |  |
| Calidad del negocio | 20 % |  |  |
| Balance y caja | 15 % |  |  |
| Crecimiento / tendencia | 20 % |  |  |
| Riesgo / visibilidad | 10 % |  |  |
| Momento de entrada | 10 % |  |  |
| **TOTAL** | **100 %** |  | **/10** |

### Valoración
- 

### Calidad del negocio
- 

### Balance y caja
- 

### Crecimiento / tendencia
- 

### Riesgo / visibilidad
- 

### Momento de entrada
- 

### Conclusión
- **Nota total:**
- **Qué tendría que mejorar para subir la nota:**
- **Qué deterioro obligaría a revisarla a la baja:**
- **Catalizadores a vigilar:**

---

# 7. Principio final

> **El objetivo no es encontrar la empresa con mejores ratios, sino identificar cuándo una empresa de suficiente calidad ofrece una relación atractiva entre precio, crecimiento, riesgo y capacidad de generar caja.**
