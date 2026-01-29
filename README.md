# Interconnect, Ciencia de datos

📖 Resúmen:  
 Entrenamiento y elección del mejor modelo con métricas f1-score y AUC-ROC para predecir los clientes potenciales que podrían cancelar su servicios de la empresa de telecomunicaciones, se tiene la finalidad de identificarlos para tratar de evitarlo mediante descuentos o promociones.  
.  
.  
.   
🎯 Objetivo:  
 Identificar clientes potenicales que podrían abandonar la empresa de telecomunicaciones (cancelar sus servicios).

❌ Problema:  
 Los clientes están cancelando sus servicios y no han identificado las razones.

✅ Solución:  
 Creamos y probamos un modelo que identifica con buena exactitud que clientes podrían estarse planteando cancelar sus servicios en la empresa.

🔢 Metodologia:  
  1. Formateo y limpieza de datos.
  2. Enriquecimiento de datos mediante unificación del conjunto de datos y creación de nuevas columnas.
  3. Estandarización y formateo de datos para poder entrenar modelos.
  4. Realización del análisis exploratorio de datos.
  5. Creación de hipótesis.
  6. Entrenamiento y elección de modelos (modelo dummy, regresión logística, arbol de decisión, bosque aleatorio y LightGBM) con balanceo de clases mediante 'remuestreo de clases (upsampling)'.
  7. Finalmente aplicamos el modelo elegido a nuestro dataset de prueba y mostramos la conclusiones.  

📊 Conclusiones:  
 Creamos satisfactoriamente un modelo que predice correctamente el 83% de los clientes que cancelarán el servicio (AUC score). Nuestro modelo también tiene una eficiencia entre recall y precisión del 61.50% (f1 score) y un exactitud de 74% (accuracy). 
