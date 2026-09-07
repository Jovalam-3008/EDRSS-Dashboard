# EDRSS Dashboard

Demo pública del **Early Delinquency Risk Scoring System (EDRSS)**, un sistema de priorización para cobranza temprana de operaciones de microcrédito móvil.

## Aplicación publicada

[Abrir EDRSS Dashboard](https://edrss-dashboard-hjcbxwakvf6js8yn6evnhe.streamlit.app/)

## Historia del tablero

1. Resumen ejecutivo de la cartera.
2. Evolución temporal del riesgo y la mora.
3. Señales de comportamiento asociadas al incumplimiento.
4. Desempeño y explicación del modelo predictivo.
5. Captura de riesgo según la capacidad de contacto.
6. Calidad y trazabilidad de los consumibles.

## Resultados principales

- 209,593 operaciones procesadas.
- ROC-AUC fuera de tiempo: 0.8435.
- Captura del 33.67% de la mora al contactar el 10% de las operaciones.
- Lift al 10%: 3.37x.

## Privacidad

La demo utiliza únicamente archivos agregados. No publica la base original, credenciales, identificadores ni la cola detallada de cobranza.

## Ejecución local

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\streamlit.exe run dashboard\public_app.py
```

Para Streamlit Community Cloud, seleccione `dashboard/public_app.py` como archivo principal.
