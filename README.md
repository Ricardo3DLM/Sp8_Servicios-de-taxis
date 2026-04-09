Info. Proyecto de Sprint 8: "Recopilación y Almacenamiento de Datos"

Análisis de datos con SQL, data wrangling, y prueba de hipótesis sobre servicios de taxis, 
duraciones de viaje, clima, y demanda de destinos.
*Tablas creadas: Barras, y circular (pie chart).


Tablas de Datos (3, derivadas de la sección del proyecto de SQL):

/datasets/project_sql_result_01.csv. contiene los siguientes datos:
	company_name: nombre de la empresa de taxis
	trips_amount: el número de viajes de cada compañía de taxis el 15 y 16 de noviembre de 2017. 

/datasets/project_sql_result_04.csv. contiene los siguientes datos:
	dropoff_location_name: barrios de Chicago donde finalizaron los viajes
	average_trips: el promedio de viajes que terminaron en cada barrio en noviembre de 2017.

/datasets/project_sql_result_07.csv — el resultado de la última consulta. Contiene datos sobre viajes 
desde el Loop hasta el Aeropuerto Internacional O'Hare. Recuerda, estos son los valores de campo de 
la tabla:
	start_ts: fecha y hora de la recogida
	weather_conditions: condiciones climáticas en el momento en el que comenzó el viaje
	duration_seconds: duración del viaje en segundos


Conclusiones:
- El mercado, a pesar de tener mucha competencia, tiene preferencias evidentes tanto en las empresas 
de taxi como en los destinos de viaje.
- En cuanto a empresas, las 3 preferidas son Flash Cab, Taxi Affiliation Services, y Medallion Leasing.
- Las 3 empresas mencionadas tienen 14.24 %, 8.32 %, y 7.55% del mercado respectivamente, sumando un 
poco más del 30%.
- Estas 3 empresas dominan significativamente, ya que lo esperado es que cada una tenga 1.56 %, sumando 
4.69 % entre las 3.
- Las 3 ubicaciones más populares son Loop, River North, y Streeterville.
Estos 3 destinos son visitados por 19.02 %, 16.89 %, y 11.82 % de los clientes respectivamente, sumando 
casi la mitad de todos los viajes con 47.73 % del total.
- Tomando en cuenta lo anterior, y asumiendo que las empresas operan con la misma capacidad de oferta, 
y que ofrecen viajes a todos los destinos, se podría concluir que la ventaja competitiva es evidente. 
La cuestión está en que, si lo que se asume es falso, más información podría revelar el porqué de estas 
diferencias tan pronunciadas.
	- Por ejemplo, es posible que la ventaja existe solamente porque las empresas más grandes son 
las únicas que ofrecen viajes a los destinos más populares, pero esto ya es especulación.

- La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los 
sábados lluviosos de acuerdo a la prueba de hipótesis.
