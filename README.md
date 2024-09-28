Buenas a todos! En este proyecto individual, tomé el rol de un Data Scientist, ayudando a un emprendimiento llamado Noir, el cual presentó una gran baja en sus ventas este último trimestre.
Comencé, creando la base de datos utilizando SQL, luego exporté cada tabla a un CSV distinto para poder comenzar con el análisis exploratorio en Python.
Los objetivos principales del proyecto fueron:
- Identificar la razón de la baja de ventas
- Proponer una solución a este problema
- Implementar modelos de machine learning, como sistemas de recomendación, para ayudar a los clientes de Noir a comprar, ya que este emprendimiento no contaba con uno.
- Proponer un KPI.
Mis soluciones fueron:
- Luego de un largo análisis de los datasets, identificamos la razón de la baja de ventas, la cual era la insatisfacción de los clientes. Otro factor que influyó fue el amplio rango de precios que Noir tiene en sus productos.
[EDA](EDA.ipynb)
- La solución a esto, fue implementar estrategias de fidelización, tales como cuponeras de descuentos para clientes, y una campaña de re-targeting para atraer de nuevo a los clientes perdidos, brindándoles un pequeño descuento en sus siguientes compras. Para abordar el tema de los precios, propusimos estudiar la competencia en el mercado y analizar los precios de la competencia. También se consideró, descontinuar los productos extremadamente costosos, ya que estos solo brindan gastos y poca o incluso nula ganancia. 
- Implementé 2 nuevos sistemas de recomendación, uno para productos similares a los clientes que ya han comprado, y el otro basado en productos más populares.
[Sistemas de recomendación](sistemas_recomendacion.ipynb)
- Propuse un KPI para ayudar con la retención de los clientes, cuya fórmula es: Clientes al final del período - Nuevos clientes adquiridos durante el período / Clientes al inicio del período * 100. Ejemplo: 
Clientes al inicio: 150
Clientes al final: 130
Nuevos clientes: 10
130 - 10 / 150 * 100 = 120 / 150 * 100 = 80%
Esto significa, que la tasa de retención de clientes del período sería de un 80%.

Disclaimer: Los datos utilizados en este proyecto son ficticios, al igual que el emprendimiento mencionado. Muchas gracias por su atención!