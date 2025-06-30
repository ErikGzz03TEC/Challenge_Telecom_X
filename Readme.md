# Análisis de Abandono de Clientes en una Empresa de Telecomunicaciones

Este proyecto tiene como objetivo analizar los factores que influyen en el abandono de clientes (`Churn`) en una empresa de telecomunicaciones. A través de técnicas de análisis exploratorio de datos y visualización, se buscó identificar patrones que expliquen el comportamiento de los clientes que deciden dejar el servicio.

## Objetivos

- Identificar las características demográficas y contractuales asociadas al abandono de clientes.
- Determinar qué servicios tienen mayor o menor relación con el churn.
- Proponer recomendaciones basadas en los hallazgos obtenidos del análisis.

## Dataset

El conjunto de datos contiene información detallada sobre los clientes de la empresa, incluyendo aspectos demográficos, tipo de contrato, servicios contratados y comportamiento de pago.

### Diccionario de Variables

| Variable | Descripción |
|----------|-------------|
| `customerID` | Número de identificación único de cada cliente |
| `Churn` | Indica si el cliente dejó (`Sí`) o no (`No`) la empresa |
| `gender` | Género del cliente: masculino o femenino |
| `SeniorCitizen` | Indica si el cliente tiene 65 años o más (1 = sí, 0 = no) |
| `Partner` | Indica si el cliente tiene pareja |
| `Dependents` | Indica si el cliente tiene dependientes |
| `tenure` | Meses que el cliente ha estado con la empresa |
| `PhoneService` | Si el cliente tiene servicio telefónico |
| `MultipleLines` | Si el cliente tiene múltiples líneas telefónicas |
| `InternetService` | Tipo de servicio de internet contratado (Fibra óptica, DSL, Ninguno) |
| `OnlineSecurity` | Si el cliente tiene servicio de seguridad en línea |
| `OnlineBackup` | Si el cliente tiene servicio de respaldo en línea |
| `DeviceProtection` | Si el cliente tiene protección para dispositivos |
| `TechSupport` | Si el cliente cuenta con soporte técnico |
| `StreamingTV` | Si el cliente tiene servicio de TV por cable |
| `StreamingMovies` | Si el cliente tiene servicio de películas en streaming |
| `Contract` | Tipo de contrato (mensual, un año, dos años) |
| `PaperlessBilling` | Si el cliente recibe la factura en formato digital |
| `PaymentMethod` | Método de pago (ej. transferencia bancaria, tarjeta de crédito, cheque) |
| `Charges.Monthly` | Monto mensual cobrado al cliente |
| `Charges.Total` | Total acumulado que ha gastado el cliente |

## Herramientas Utilizadas

- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook / Visual Studio Code
- Análisis estadístico y visualización de datos

## Principales Hallazgos

- Los clientes con contrato mensual tienen una mayor tasa de abandono comparado con contratos a un año o dos años.
- El uso de servicios adicionales como soporte técnico y respaldo en línea se asocia con una menor tasa de churn.
- No hay una característica demográfica clara que explique el abandono.
- Los clientes con una fibra óptica como servicio de internet tienen una mayor tasa de abandono.

## Conclusiones

El análisis muestra que factores como la duración del contrato, el servicio de internet y duración en el sevicio (tenure). Se recomienda implementar estrategias de retención enfocadas en mejorar la experiencia de usuarios con contrato mensual y promover el uso de servicios adicionales que aporten valor.


## Próximos Pasos

- Implementar modelos predictivos para anticipar el abandono de clientes (clasificación con modelos como K-means).
- Desarrollar dashboards interactivos para seguimiento en tiempo real (Power BI o Tableau).
- Proponer campañas de retención específicas para los segmentos con mayor probabilidad de churn.

---