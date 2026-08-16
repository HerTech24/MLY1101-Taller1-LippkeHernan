# MLY1101 · Taller N°1 — Consumo de APIs

Nombre: Hernán Lippke
Sección: MLY1101_001V

Pregunta u objetivo:
¿Qué información puede recopilarse sobre los países del mundo desde fuentes
geográfico-demográficas, económicas y culturales?

API 1: CountriesNow — https://countriesnow.space/ (demografía: población por país → dataset_api_1.csv)
API 2: World Bank — https://data.worldbank.org/ (economía: PIB per cápita → dataset_api_2.csv)
API 3: Nager.Date — https://date.nager.at/ (cultura: días festivos → dataset_api_3.csv)

Registros API 1: 263
Registros API 2: 265
Registros API 3: 310

## Cómo ejecutar

Abrir el notebook en Google Colab y usar Entorno de ejecución → Ejecutar todas.
El código regenera automáticamente los 3 datasets (.csv), sin intervención manual.
Ninguna de las 3 APIs requiere API key.

## Nota sobre los conteos

Algunas fuentes (World Bank, CountriesNow) incluyen agregaciones regionales
además de países individuales, y Nager.Date se detiene al superar 300 feriados.
En los tres casos se supera el mínimo de 200 registros por fuente.
