# 📈 Visualizaciones y Evidencia de Ejecución: Financial Rates Bot

Esta carpeta contiene la documentación visual que certifica el correcto funcionamiento del bot de automatización de divisas.

## 🖼️ Captura de Pantalla: Log de Ejecución (`bot_automation_preview.png`)
Esta imagen muestra el flujo de trabajo del bot en tiempo real:
1. **Conexión:** El bot accediendo exitosamente a las fuentes oficiales de Google Finance.
2. **Extracción:** La captura de los valores actuales para el Dólar (USD) y el Euro (EUR).
3. **Persistencia:** El mensaje de confirmación de que el archivo maestro de Excel ha sido actualizado.

## 📊 El Entregable: Historial de Auditoría
El bot alimenta un archivo centralizado (`reporte_divisas_pro.xlsx`) que sirve como:
* **Log Maestro:** Registro histórico de la TRM día a día.
* **Marca de Tiempo:** Cada registro incluye la hora exacta de la consulta para garantizar la trazabilidad ante auditorías financieras.

## 🛠️ Herramientas de Generación
* **Extracción:** Python (Requests + BeautifulSoup).
* **Output:** Reporte automatizado en formato OpenXML (Excel) procesado con Pandas.

---
*La visualización de procesos automatizados es fundamental para generar confianza en la integridad de los datos financieros.*
