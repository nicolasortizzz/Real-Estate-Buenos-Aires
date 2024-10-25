# Real-Estate-Buenos-Aires
Investigation about facts and information related with the real state in Buenos Aires.

REAL ESTATE - BUENOS AIRES

En este trabajo se presentara informacion estadistica clave para entender el mercado de inmuebles en Buenos Aires, Argentina. Se buscara abordar cuestiones que pasan por la mente de un agente el cual busca optimizar el rendimiento de su capital adentrandose en el mundo del real estate.

Para entender este mercado es importante entender que compone el valor de una propiedad. Para esto surge preguntas como, que es lo que realmente altera el valor de las propiedades? Existe algo que por si solo pueda darle una gran variacion al precio de una propiedad? Que es y como encontrarlo? Este trabajo intentara abordar estas preguntas con una vision microeconomica y estadistica, pero me parece necesario resaltar que no estoy teniendo en cuenta una mirada historica y macroeconomica que sin lugar a duda hay tener en cuenta esto para realizar un analisis completo. La volatilidad en el precio del metro cuadrado en Argentina es muy grande a lo largo de periodos de tiempo no mayores a 20 años, es por esto que el fenomeno macroeconomico no debe dejarse de lado.

El trabajo se dividira en 3 partes la primera sera un analisis que brindara informacion sobre aspectos generales, mientras que la segunda parte buscara causalidad y analizar como trabaja un modelo de regresion multiple con nuestros datos. Por ultimo, la tercera parte consistira en desarrollar un modelo predictivo el cual puede tener bastante utilidad comercial si se le hacen ciertos ajustes.

Usare un data set de Keaggle que recolecto los datos en el año 2019 a travez de una pagina de venta de propiedades llamada Properati (https://www.kaggle.com/datasets/alejandromendivil/bsas-realstate-on-sale). Aclaracion sobre varaibles. l1: Pais zona: Zona localidad: Barrio start_date: fecha de alta del aviso de venta de propiedad. end_date: fecha de baja del aviso de venta de propiedad. created_on: fecha de alta de la primera versión del aviso. lat: latitud de la ubicación geográfica de la propiedad. lon: longitud de la ubicación geográfica de la propiedad. rooms: número de habitaciones de la propiedad. bedrooms: número de dormitorios de la propiedad. bathrooms: número de baños de la propiedad. surface_total: superficie total de la propiedad en metros cuadrados. surface_covered: superficie cubierta de la propiedad en metros cuadrados. price: precio de la propiedad en la moneda local. currency: moneda local utilizada para el precio de la propiedad. title: título de la oferta inmobiliaria que resume las características principales de la propiedad. description: descripción detallada de la oferta inmobiliaria que incluye información adicional sobre la propiedad, el entorno, las condiciones de venta o alquiler, etc. property_type: tipo de propiedad ofertada. operation_type: tipo de operación inmobiliaria.

OBJETIVO

El objetivo final del trabajo es crear un modelo que intente predecir el valor de una propiedad conociendo los parametros de la misma.
