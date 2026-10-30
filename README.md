# Panel Bambú - Automatización de Consultas con IA

Este proyecto consiste en un sistema de automatización inteligente desarrollado para la empresa **Panel Bambú**, ubicada en Mendoza, Argentina. El flujo captura correos electrónicos entrantes de clientes, procesa y clasifica la información mediante Inteligencia Artificial (Anthropic Claude), calcula presupuestos comerciales parametrizados y genera borradores de respuesta automáticos en Airtable para su posterior revisión humana.

## 🛠️ Tecnologías Utilizadas
* **n8n Cloud**: Orquestador del flujo de trabajo y la lógica intermedia de negocio.
* **Anthropic API (Claude 3.5 Haiku)**: Clasificación de consultas comerciales, extracción de dimensiones y redacción de borradores en JSON.
* **Airtable**: Base de datos relacional para la gestión de consultas, tarifas fijas, superficies válidas y log de errores.
* **Gmail**: Canal de comunicación oficial del negocio para la recepción automatizada mediante filtros y etiquetas.

## 📁 Estructura del Repositorio
* `/capturas`: Evidencias fotográficas del correcto funcionamiento del sistema en Airtable.
* `/diagrama`: Arquitectura funcional del flujo de datos.
* `/flujo`: Archivo JSON exportado listo para ser importado en n8n.
* `/documentacion`: Archivos de configuración técnica y registros de claves (excluidos del repositorio público).

## 👥 Autor
* **Leandro Montenegro** - *Desarrollador del Proyecto de Automatización*
