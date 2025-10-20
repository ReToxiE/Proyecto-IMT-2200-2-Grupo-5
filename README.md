# Proyecto IMT-2200

## Estructura

- `data/`: Archivos de datos (raw o procesados).
- `notebooks/`: Notebooks con análisis exploratorio y modelamiento.
- `src/`: Código fuente auxiliar.
- `figures/`: Imágenes y visualizaciones generadas automáticamente por los notebooks.
- `web/`: Archivos para GitHub Pages.
- `requirements.txt`: Dependencias del proyecto.

## Reproducción rápida - guía para correr el proyecto

Para Windows:
```powershell
python -m venv .venv
.venv\Scripts\Activate
pip install -r requirements.txt
jupyter notebook notebooks/analisis_final.ipynb
```