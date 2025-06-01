# Challenge-TelecomX_LATAM


# 📊 Informe Final – Análisis de Evasión de Clientes (Churn) en TelecomX LATAM

## 🔹 Introducción

El objetivo principal de este análisis fue identificar los factores que influyen en la **evasión de clientes (Churn)** en la empresa de telecomunicaciones **TelecomX LATAM**. Este fenómeno representa un desafío crítico para el sector, ya que la pérdida de clientes afecta directamente los ingresos y la sostenibilidad a largo plazo. A través de este trabajo, buscamos analizar los datos proporcionados, limpiar y transformarlos, descubrir patrones relevantes y proponer estrategias para **reducir la tasa de Churn**.

## 🔹 Limpieza y Tratamiento de Datos

El proceso comenzó con la **extracción de datos** desde un archivo `.json` alojado en un repositorio público. Las principales acciones realizadas fueron:

- **Normalización** de estructuras anidadas (por ejemplo, información del cliente, teléfono e internet).
- **Concatenación de subtablas** para unificar toda la información en un único DataFrame.
- Eliminación de **valores nulos o inconsistentes** en columnas clave.
- Conversión de columnas categóricas y numéricas al formato adecuado.
- Creación de una columna binaria (`Churn`) para representar si un cliente se fue o no.

Estas transformaciones permitieron preparar los datos para un análisis exploratorio robusto.

## 🔹 Análisis Exploratorio de Datos (EDA)

Se realizaron diversos análisis para entender la relación entre las características del cliente y su probabilidad de abandonar la empresa. Algunos puntos destacados:

- **Visualizaciones de distribución** de variables como tipo de contrato, servicios contratados, métodos de pago y antigüedad.
- Identificación de una mayor tasa de evasión en clientes con:
  - Contratos **mensuales**
  - Múltiples servicios cancelados
  - Métodos de pago como débito automático
- Uso de gráficos como:
  - Barras y histogramas para variables categóricas y numéricas.
  - Mapas de calor de correlación.
  - Comparaciones de Churn según servicio (internet, teléfono, etc.)

Estas visualizaciones facilitaron la identificación de patrones y segmentos de clientes con mayor riesgo de churn.

## 🔹 Conclusiones e Insights

Entre los principales hallazgos del análisis, destacamos:

- Los **clientes con contratos a corto plazo (mensuales)** son significativamente más propensos a abandonar la empresa.
- **Servicios como internet y llamadas** afectan directamente la permanencia del cliente.
- La **antigüedad del cliente** tiene un peso considerable: mientras más nuevo el cliente, más alta es la tasa de Churn.
- Ciertas combinaciones de servicios y métodos de pago elevan el riesgo de abandono.

Estos insights pueden ayudar a TelecomX LATAM a identificar segmentos vulnerables y actuar de forma proactiva.

## 🔹 Recomendaciones

Con base en el análisis realizado, se proponen las siguientes estrategias para reducir la evasión:

1. **Fomentar contratos a largo plazo**, ofreciendo descuentos o beneficios exclusivos por fidelidad.
2. **Mejorar la experiencia de usuario** en los primeros meses, con campañas de bienvenida y atención personalizada.
3. Identificar clientes en riesgo usando modelos de clasificación y aplicar **ofertas personalizadas**.
4. Revisar la estructura de precios y calidad del servicio de internet, dado su impacto en la decisión de quedarse o irse.
5. Implementar un sistema de alertas tempranas basadas en comportamiento del cliente para prevenir abandonos.
