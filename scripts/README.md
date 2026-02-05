# 🐍 Motor de Automatización: Financial Rates Bot

Esta carpeta contiene el código fuente desarrollado en Python para la extracción y procesamiento automatizado de datos financieros.

## 🛠️ Especificaciones Técnicas
El script `Financial_Rates_Bot.ipynb` realiza las siguientes funciones críticas:

1. **Web Scraping Dinámico:** Implementación de `BeautifulSoup` para navegar en Google Finance y extraer el valor real del Dólar (USD) y Euro (EUR).
2. **Lógica Escalable:** Uso de diccionarios de configuración que permiten añadir nuevas divisas o cambiar fuentes de datos sin reescribir la lógica principal.
3. **Persistencia de Datos:** Gestión inteligente de archivos que verifica la existencia de registros previos para consolidar un historial maestro en Excel sin duplicados.

## 📦 Librerías Requeridas
* `requests`: Gestión de peticiones HTTP a servidores financieros.
* `beautifulsoup4`: Análisis y extracción de datos de estructuras HTML.
* `pandas`: Procesamiento de datos y exportación a formatos contables.

---
*Este código ha sido diseñado bajo principios de eficiencia y escalabilidad, ideal para ser programado como una tarea recurrente (Cron Job) en servidores corporativos.*
