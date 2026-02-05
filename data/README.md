# 📂 Gestión de Activos de Datos: Financial Rates Auditor

Esta carpeta contiene el archivo maestro generado por el proceso de automatización (RPA) de tasas de cambio.

## 📑 Descripción del Archivo Maestro (`reporte_divisas_pro.xlsx`)
El archivo centraliza el historial de capturas realizadas por el bot. Está estructurado bajo un formato de **Serie de Tiempo**, lo que permite su fácil integración con otros reportes financieros o dashboards de BI.

### Diccionario de Datos:
* **Fecha:** Marca de tiempo exacta (YYYY-MM-DD HH:MM:SS) en que se realizó la extracción desde la fuente oficial.
* **Moneda:** Identificador de la divisa monitoreada (USD, EUR).
* **Tasa:** Valor de cambio (TRM) capturado en tiempo real con precisión decimal.

## 🛡️ Integridad y Confiabilidad
* **Sin Duplicados:** El script de automatización realiza una validación de persistencia para asegurar que no existan registros repetidos para una misma captura.
* **Trazabilidad:** La inclusión de la hora exacta de consulta permite que este archivo funcione como un **Log de Auditoría** para cierres contables.

---
*Este dataset es el resultado directo de la interacción entre Python y APIs web, garantizando la eliminación del error humano en la gestión de divisas.*
