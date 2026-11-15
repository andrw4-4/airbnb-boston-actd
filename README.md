# Airbnb Boston: precio y recomendación de anuncios

Proyecto 2 de ACTD (Uniandes), Reto Global Classroom con el Tec de Monterrey.
Datos: Inside Airbnb, `listings.csv` de Boston (scrape 2026-09-20).

Objetivo: tablero en Dash, desplegado en AWS con Docker, que estima el precio por noche de un anuncio y lo clasifica como recomendado o no recomendado. Los modelos están serializados.

## Estructura
| Carpeta | Etapa |
|---|---|
| `data/` | datos originales y dataset limpio |
| `02_limpieza/` | Etapa 2: limpieza y transformación |
| `03_eda/` | Etapa 3: análisis exploratorio |
| `04b_modelos_nn/` | Etapa 4b: redes neuronales y MLflow |
| `05_tablero/` | Etapa 5: tablero en Dash |
| `06_despliegue/` | Etapa 6: Docker y AWS |
| `models/` | modelos serializados |
| `docs/` | enunciado del reto |

## Estado
- [x] Etapa 2: limpieza (3.419 filas, 175 columnas, sin nulos)
- [ ] Etapa 3: EDA
- [ ] Etapa 4b: modelos
- [ ] Etapa 5: tablero
- [ ] Etapa 6: despliegue
