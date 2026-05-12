# SeriesDeTiempo

1. Considera la información histórica diaria de precios para las empresas IBM y Walmart contenida en el sitio de Yahoo finance (http://finance.yahoo.com) durante los últimos 5 años. Nomenclatura  y componentes de las Series de Tiempo.

2. Responde a la pregunta: ¿Existe alguna correlación entre los precios de las acciones de ambas empresas? Explica tanto de forma gráfica como a través del índice de correlación discutido en esta lección

<img width="818" height="403" alt="image" src="https://github.com/user-attachments/assets/eff9b8f4-e33b-4ba2-9ee6-feb1663cfcc2" />

<img width="505" height="364" alt="image" src="https://github.com/user-attachments/assets/2ff548d5-ade9-4c24-a310-4bb4769f7e28" />

Se puede observar en las gráficas que la correlación es muy pequeña y el índice de correlación calculado fue de 0.1732 por lo que podemos concluir que realmente no existe alguna correlación entre los precios de las acciones de ambas empresas. 

3. Obtén los gráficos de descomposición para ambas series de precios así como sus correlogramas. Interpreta tus resultados.

<img width="507" height="386" alt="image" src="https://github.com/user-attachments/assets/67675acf-3b7b-4dae-8448-78cce7b8d6a7" />

<img width="506" height="384" alt="image" src="https://github.com/user-attachments/assets/13ea06cd-de97-455d-bb40-2dabb053a6fc" />

Ambas series presentan autocorrelaciones altas que decrecen gradualmente a medida que aumentan los rezagos, lo que indica la presencia de dependencia temporal significativa. Este comportamiento sugiere que las series no son estacionarias y probablemente contienen tendencia. 

<img width="491" height="401" alt="image" src="https://github.com/user-attachments/assets/b54f1c7a-d6b4-4ad3-95d2-dc9ece69aaa1" />

<img width="982" height="504" alt="image" src="https://github.com/user-attachments/assets/60356c06-2ba7-45ca-9fd3-e4f552b1f20a" />

<img width="488" height="397" alt="image" src="https://github.com/user-attachments/assets/f88e1ff6-7ad1-4d04-91f3-eb73a6e3752e" />

<img width="982" height="509" alt="image" src="https://github.com/user-attachments/assets/d7f7ee5c-3f6e-40d8-aaab-2b145fc46423" />

<img width="558" height="411" alt="image" src="https://github.com/user-attachments/assets/b13de1b3-0b5e-4e54-9d30-d4a3ce67f786" />

<img width="558" height="413" alt="image" src="https://github.com/user-attachments/assets/93dd2e3d-0885-4b8c-ba41-ff97dc74504c" />

La descomposición de ambas series revela una tendencia creciente, lo que indica no estacionariedad. Además, se identifica un componente estacional con oscilaciones periódicas. Los residuos no presentan patrones sistemáticos, lo que sugiere que la descomposición captura adecuadamente la estructura de las series. 

IBM

<img width="986" height="269" alt="image" src="https://github.com/user-attachments/assets/3a72225c-4e85-4b93-940f-69efb24f7cd1" />

WALMART

<img width="985" height="269" alt="image" src="https://github.com/user-attachments/assets/aaeab403-82a7-4699-b6da-695ef53804aa" />

4. Aplica e interpreta la prueba de Dickey-Fuller para ambas series.

Los p-values obtenidos son superiores a 0.05 por lo que no se rechaza la hipótesis nula H0 y se concluye que las series no son estacionarias. 

5. Haz un análisis gráfico de promedios móviles para ambas empresas y pronostica el siguiente día de cotizaciones. ¿Esperarías que dichos pronósticos sean buenos? Explica a detalle.

IBM

De acuerdo con el rmse y el mape, el pronóstico se equivoca aproximadamente en ±86.18 unidades y un 29.3% por lo que los resultados podrían mejorar. 

WALMART

De acuerdo con el rmse y el mape, el pronóstico se equivoca aproximadamente en ±35.13 unidades y un 32.5% por lo que los resultados podrían mejorar. 
