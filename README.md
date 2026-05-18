# Mapa Eleições 2018 - 2º Turno

Interactive map of the 2018 Brazilian presidential election (second round) results by municipality.

Built with **Streamlit**, **GeoPandas**, **Folium**, and **Pandas**.

## How to run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Data

- Electoral results: TSE's official `votacao_candidato_munzona_2018_BR.csv` (2nd turn, president)
- Municipal boundaries: IBGE shapefile (`BRMUE250GC_SIR.shp`)
- TSE-IBGE municipality code correspondence: Estadão's GitHub repository

## Features

- Interactive choropleth map showing the winning candidate per municipality
- Filters by state (UF) and winning candidate
- Municipal-level metrics (total, wins per candidate)
- Detailed data table sorted by vote count

## Legend

- Red: Fernando Haddad (PT)
- Green: Jair Bolsonaro (PSL)
