# robot_trading_bitcoin
Determina si es conveniente la compra/venta de Bitcoin
Usando yahoo finance se obtienen los registros de los últimos 7 días con un intervalo de 5 minutos.
Se crea un dataframe el cuál es tratado para obtener los valores estadísticos del bitcoin, especialmente la media y Q1 y Q3.
Delimitando el rango de valores que se encuentrantran entre Q1 y Q3, se obtiene la media.
Luego se obtienen los datos (precio de cierre y tendencia) en tiempo real con web scraping desde https://coinmarketcap.com/.
Mediante un algoritmo se determina si es conveniente: comprar/vender/esperar.
El resultado se visualiza así:


![image](https://github.com/JulioLaz/robot_trading_bitcoin/assets/108642139/6861f3e1-feee-4ea4-bd0c-c558c2390b91)


![image](https://github.com/JulioLaz/robot_trading_bitcoin/assets/108642139/573e9095-0be5-4fba-b6dc-d59dbe6e40ca)

