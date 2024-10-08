# Migración - Estado 2024



## Contenido

- **Mapa Interactivo**: Aquí puedes ver el mapa interactivo que muestra la migración neta en 2023 y zonas críticas en Latinoamérica:
  
<iframe src="mapa_migracion_2023_con_zonas_y_datos_ajustados.html" width="800" height="600"></iframe>

- **Datos**: Los datos de migración se encuentran en el archivo `migration_total.csv`.
- **GeoJSON**: El archivo `countries.geo.json` contiene la geometría de los países para el mapa.

## Zonas Críticas Analizadas

1. **Tijuana, México**:
   - Endurecimiento de la política de migrantes por Kamala Harris.
   - Suspensión de permisos para venezolanos.

2. **Pacaraima, Brasil**:
   - Aumento de migrantes en agosto (12,000) y junio (8,000).
   - Política de acogida por parte de Lula para recibir migrantes del Líbano.

3. **Cúcuta, Colombia**:
   - Incremento de migrantes en la frontera post-electoral.

## Instrucciones para Ejecutar el Mapa

Para ejecutar el mapa interactivo, simplemente abre el archivo `mapa_migracion_2023_con_zonas_y_datos_ajustados.html` en tu navegador web preferido.

## Requisitos

Asegúrate de tener las siguientes bibliotecas de Python instaladas para ejecutar el código:

- `pandas`
- `folium`
- `shapely`

Puedes instalar estas bibliotecas utilizando pip:

```bash
pip install pandas folium shapely

