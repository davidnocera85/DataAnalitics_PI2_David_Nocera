
# <h1 align=center> **PROYECTO INDIVIDUAL** </h1>
# <h1 align=center>*"Telecomunicaciones"* </h1>

<p align="center">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSrj92-RF8tDd-YI3ZnFEdgp-KVGlfo6HazF13J8jSzCfXAJK6UeWQrWm2EggBOTzFGtco&usqp=CAU"  height=100>
</p>

### Objetivo ###
 Analizar el sector de telecomunicaciones argentino en torno al servicio de internet, con el fin de orientar a una empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y plantear soluciones personalizadas a sus posibles clientes (**`Data Analyst`)**.


### **`Requerimientos`**:

EDA: Desarrollo en código Python (Visual Studio Code y Google Colab).
Bibliotecas: pandas, numpy, Matplotlib, Seaborn.
Dashboard: PowerBI o similar.
Demo: en vivo mediante Google Meet


### **`Estructura de carpetas y archivos`**:

1. **Datasets**: carpeta que contiene los datasets del proyecto junto con el ETL.
2. **EDA**: carpeta que contiene 'notebook' y graficos del proceso 'Exploratory Data Analysis' de datos.
3. **Readme_PI2_DN**: este archivo propiamente dicho, que contiene guia orientadora sobre el proyecto.

# <h1 align=center> **`REPORTE DE ANÁLISIS`**  </h1>

## **`Estado del Arte" del sector Telecomunicaciones en Argentina`**

Hace más de un cuarto de siglo, el 8 de abril de 1994, las universidades argentinas se conectaron a Internet, por primera vez, a través de un enlace digital. Si bien para aquella época otros países de la región como Chile, Brasil y México ya tenían acceso, a Argentina, le costó más de 4 años conectarse. El desconocimiento general acerca de la tecnología, la falta de recursos y la ausencia de marcos regulatorios hacían mucho más lento el camino a la conexión en nuestro país. 
Desde el lanzamiento de las primeras conexiones de banda ancha a finales de la década de los ‘90, Argentina se ha convertido en uno de los países con la mayor tasa de penetración de internet en América Latina, con más de tres cuartas partes de su población con acceso a la red de redes. Si bien Argentina se encuentra entre las naciones con más alto índice de penetración de internet fija y móvil de la región, no alcanza el nivel promedio de los países de la Organización para la Cooperación y el Desarrollo -OCDE- (81%).
El desafío de universalizar el acceso a internet exige un rol central del Estado nacional para la promoción de infraestructura (pública y privada) para la provisión de internet fija y móvil en las zonas donde aún no existe, y mejora del servicio en las zonas existentes, con el objetivo de constituir un escenario de mayor igualdad de oportunidades económicas, educativas y laborales, y colaborar en el fortalecimiento de las economías regionales.
Es fundamental que este proceso se realice junto a grandes compañías ya instaladas, así como así también junto a pymes y cooperativas proveedoras de servicios de telecomunicaciones. Este informe se basa en el análisis de datos provistos por el ENACOM, buscando proponer una serie de acciones para fomentar inversiones rentables, basadas en el diagnóstico sobre  la evolución de los tipos y calidad de servicios ofrecidos, los niveles de penetración de los mismos teniendo en cuenta las desigualdades regionales y el volumen de ingresos generados en los años recientes.

## **`Resumen Análisis de Internet en Argentina`**

## Acceso a Internet 

En primer lugar, se procede a analizar la evolución del acceso a Internet para las distintas provincias a lo largo de los últimos nueve años.

A partir de este gráfico podemos concluir para el servicio de Internet en Argentina que:
* se observa un crecimiento de la penetración de Internet en hogares alcanzando en el tercer trimestre del 2022 un máximo de 76,6 %  (1,54 veces de aumento respecto al 2014). Es decir, un promedio de crecimiento anual de aprox. 6 %.
* se observa un crecimiento sostenido del acceso a Internet por cada 100 habitantes de 24 % (1,6 veces de aumento respecto al 2014). Es decir, un promedio de crecimiento anual de aprox. 6,6 %.
  
Según datos publicados en https://es.statista.com/estadisticas/598732/hogares-con-acceso-a-internet-en-el-mundo-por-region/ y actualizados al año 2021, en cuanto a accesos cada 100 hogares, Argentina se encontraría por debajo del valor promedio para el continente americano (81,4 %), mientras que el promedio más alto lo registra el continente europeo (87,5 %).
Respecto a los accesos por cada 100 habitantes, datos arrojados por el Banco Mundial (https://datos.bancomundial.org/indicator/IT.NET.BBND.P2) para el año 2021, establece un promedio mundial de 16,9 %, por lo que Argentina se encuentra por encima de dicho valor.
Con base en estos datos generales, procedemos a desglosar el análisis para examinar la distribución y evolución de la penetración de Internet. Para tener una visión más clara, a continuación se decide explorar los datos agrupando por promedio anual para cada provincia.

 

Del grafico anterior se puede distinguir una marcada diferencia de penetración de Internet en CABA respecto al resto del país, superando el 100%, lo que se podría atribuir a más de un acceso por vivienda declarada (redundancia debido a la contratación de más de un servicio por ejemplo, por poseer negocio y vivienda en el mismo domicilio, o por la presencia de conglomerados habitacionales como edificios, consorcios, etc.).
En general, se puede observar una tendencia en aumento para todas las provincias, con excepción de CABA que ha tenido una penetración relativamente constante en los 9 años evaluados (la fluctuación no es significativa). Un caso particular corresponde a San Luis, que tuvo un crecimiento abrupto a partir del año 2018, pasando de estar en la última posición al percentil 75 en 5 años; fenómeno que se explica por la implementación de políticas públicas orientadas a fomentar la conectividad (https://agenciasanluis.com/notas/2018/01/29/distinguen-internacionalmente-las-politicas-tecnologicas-de-san-luis/). 

Asimismo, los datos recabados en el análisis global de todas las 24 jurisdicciones, coinciden con los publicados por otras fuentes, como por ejemplo:https://www.infobae.com/new-resizer/iXBaf991XIGU7Oo6hy9I6ktweIo=/filters:format(webp):quality(85)/s3.amazonaws.com/arc-wordpress-client-uploads/infobae-wp/wp-content/uploads/2019/05/16174805/Conectividad-America-Latina-Infografia.gif. Según información recopilada por Cabase, con datos de la ITU, la penetración en los hogares es del 63,8%, la más alta de la región, seguido por 61,8% en Uruguay y Chile con 61,1%. 
Para tener una visión más clara del contexto en Argentina, a continuación se decide explorar los datos agrupando por regiones económicas teniendo en cuenta los promedios anuales de penetración de Internet para cada provincia.
A continuación se desglosa este mismo gráfico, mostrando la evolución por cada región.

 
Como se puede apreciar las regiones NEA y NOA son las que presentan una menor penetración de Internet a comienzos del 2014 (menor al 30% para NEA y menor al 40% para NOA) aumentando paulatinamente hasta el 2022. Cabe destacar que el crecimiento pronunciado en Cuyo se debe a una tracción del abrupto aumento descripto anteriormente en la provincia de San Luis. 
Las regiones Centro y Patagonia presentan una dinámica similar a lo largo de los años consiguiendo valores cercanos al 100 %, mientras que en Capital Federal se mantuvo estable el acceso a Internet por encima de 110% en los 9 años evaluados. 

## Tipo de servicio de Internet
Teniendo en cuenta estos datos, se procede al análisis del tipo de Internet al que acceden en las distintas provincias, arrojando los siguientes resultados:

 
A partir del gráfico anterior se puede concluir que:
- a lo largo de estos 9 años la tecnología ADSL ha ido perdiendo preponderancia pasando de un 57,8 % en 2014 a un 12,6 % en 2022 (disminuye 4,6 veces) siendo reemplazada por otras tecnologías;
- la tecnología Cablemódem aumenta 1,45 veces en 2022 respecto al 2014 (54,4% vs 37,6% respectivamente);
- a partir del 4to trimestre del 2018 se observa un crecimiento sostenido de tecnología Fibra óptica llegando a significar el 25,9% de las tecnologías de accesos a Internet (aumenta 5,6 veces);
- la tecnología Wireless en el 3er trimestre del 2022 llega a representar el 5 % de las tecnologías de accesos a Internet;
- Otras tecnologías representan el 2 % en el 3er trimestre del 2022;

A continuación se propone analizar la distribución de las tecnologías para el tercer trimestre del 2022 como proyección de mercado:
Si bien a lo largo de los años hubo una disminución marcada en su demanda, el servicio de ADSL tiene una presencia importante en diferentes provincias del país, sobre todo en la región centro (como Buenos Aires, Córdoba y Santa Fe, además de CABA) pero también en menor medida, en las otras regiones del país. Esto podría atribuirse en parte al relicto de una marcada presencia de compañías de telefonía fija (Telefónica/Telecom, hoy en baja), ya que el servicio ADSL se brinda a través de dicha red. En contraparte, el servicio de Cablemódem tiene una presencia preponderante en la provincia de Buenos Aires y CABA, además de una importante presencia en las demás provincias de la región Centro como Córdoba y Santa Fe. Cabe destacar que esta modalidad de servicio es provista por las prestadoras de televisión por cable quienes poseen en su estructura de red un troncal de fibra óptica distribuyendo la señal hasta el cliente a través del mismo cable coaxial por medio del cual se presta el servicio de CATV. Estos resultados pueden explicarse en gran parte debido a la arquitectura de distribución de la red troncal de fibra óptica en el país: https://www.argentina.gob.ar/sites/default/files/mapa_refefo_dic_2021.png. Se puede observar que la mayor densidad de redes de fibra óptica para la región Centro, coincide con la mayor cantidad de accesos en dicha región.
Dentro de las tecnologías presentes en Argentina, la fibra óptica es la única capaz de asegurar la provisión del ancho de banda que demandan los hogares para conectar cada vez más dispositivos, realizar home office, estudiar y poder correr aplicaciones de juego, video y entretenimiento en alta definición. La pandemia ha incrementado la demanda capacidad de las conexiones, haciendo de la fibra óptica un recurso crítico de la infraestructura de conectividad del país. Los datos nos dicen que la evolución de las conexiones por fibra de los últimos años se ha visto favorecida y que el ritmo de crecimiento actual fortalece la capacidad de la industria de satisfacer la demanda futura de mediano plazo”.
 
Se observa que, exceptuando CABA, la Fibra óptica es la tecnología con mayor auge en aquellas provincias que poseen los centros urbanos más grandes del país y por ende mayor concentración de usuarios (Buenos Aires, Córdoba, Santa Fe, Mendoza, Tucumán, etc.). Esto puede deberse a que si bien la Fibra óptica, tiene un costo de inversión inicial considerable, se presenta como la tecnología que tiene mejor relación calidad de servicio/precio. La siguiente información respecto al mapa de cobertura actual de la REFEFO (Red federal de Fibra Óptica) permite explicar el fenómeno anteriormente mencionado: https://www.arsat.com.ar/infraestructura-tecnologica/red-federal-de-fibra-optica/.
Además de la cobertura y el grado de alcance de las distintas tecnologías para la provisión de Internet, un dato importante a tener en cuenta es la calidad del servicio, la cual puede ser genéricamente determinada en función de la velocidad de descarga. 

## Velocidad de bajada Internet
A continuación se procederá al análisis de la velocidad promedio de descarga para las distintas provincias y/o regiones de Argentina.
Para obtener una perspectiva más clara de esta variable, se propone calcular un índice de variación de velocidad como el cociente porcentual entre la diferencia de los años 2022-2014 con respecto al año 2014. Lidera la tabla Capital Federal con un incremento en la velocidad de bajada en el 2022 respecto al 2014 por encima de 2500 %, seguida de Catamarca y Buenos Aires (1750 y 1500 % respectivamente). La provincia de Neuquén representa la mediana con un índice de aprox. 1000 %, mientras que Santa Cruz y Tierra del Fuego son las provincias que se encuentran más rezagadas con un índice de alrededor 250 %.
A continuación se muestra la velocidad media de bajada registrada en el último período registrado correspondiente al tercer trimestre del 2022:
 
Si bien el promedio nacional de velocidad de Internet es de 39.54 Mbps, según los datos del Enacom para el tercer trimestre de 2022, esta se encuentra muy dispersa en función de las provincias teniendo a la cabeza Capital Federal con 101 Mbps y por el contrario a Tierra del Fuego con 11 Mbps. Lo cual representa una gran oportunidad de mejora.
A continuación se desea analizar el la velocidad media de bajada reagrupando a las provincias por regiones económicas. Si bien hay una dispersión intergrupo, resulta interesante poder obtener un valor promedio por región:
 

Dejando fuera del análisis a CABA, en el resto del país se pueden subdividir en 2 grupos: regiones con velocidad media de bajada superior a la media nacional (39,54 Mbps), tal es el caso de la región Centro, seguida por el NEA y NOA; regiones con velocidad media de bajada inferior a la media nacional, regiones Cuyo y Patagonia.
Otro análisis interesante resulta en la relación entre penetración y velocidad por provincia para el período más reciente registrado:
 
El gráfico sitúa de izquierda a derecha, las provincias con menor y mayor promedio de velocidad de bajada (en Mbps), y de abajo hacia arriba, aquellas con menor y mayor penetración de Internet por cada 100 hogares. Se observa que Capital Federal posee el mejor promedio de velocidad de bajada y la tasa más alta de penetración por cada 100 hogares; a continuación se encuentran provincias como Buenos Aires, Córdoba, Santa Fe y Neuquén que poseen una relación intermedia entre velocidad de bajada y penetración, mientras que las provincias de Santa Cruz, San Juan y Santiago del Estero poseen la relación más baja de estos dos indicadores. Teniendo en cuenta estos datos, se procede al análisis de la relación por región:

Como hemos visto en anteriores análisis, excluyendo a Capital Federal, la región Centro termina estando a la vanguardia respecto a las demás regiones de Argentina en cuanto a la relación entre velocidad de bajada y penetración de Internet cada 100 hogares. A su vez, la región Patagonia posee mayor penetración que velocidad, mientras que para las regiones NOA y NEA existe un equilibrio entre estos indicadores. Por último la región Cuyo es la que posee peores índices de penetración y de velocidad. En todos los casos mencionados, surge la oportunidad de negocio es posible introducir mejoras sustanciales tanto en la velocidad de bajada como en la penetración.

## Inversión
Un dato importante a tener en cuenta para un plan de negocios es el volumen de los ingresos generados, para ello se procede al análisis de la evolución de ingresos trimestrales en función del tiempo.
el campo ingresos puede representar un inconveniente debido a la variable no contemplada 'inflación', ya que el rango de valores varia en 64 millones (aprox. 22,5 veces) entre el mínimo y el máximo valor, por lo que para poder comparar iguales trimestres en diferentes años, o los ingresos en un periodo de tiempo dado, se ve la necesidad de 'normalizar' los ingresos, ya que de lo contrario generaría una incorrecta interpretación de los datos. Se decide relativizar su valor para prescindir de datos extras de inflación no confiables (estimada vs. real), empleando nuevo dataset obtenido de https://datos.gob.ar/series/api/series/?ids=168.1_T_CAMBIOR_D_0_0_26&limit=5000&end_date=2022-12-31&collapse=quarter&collapse_aggregation=avg&chartType=line para su respectiva conversión de moneda pesos a dólares (más estable).
Como se había comentado previamente, al graficar los Ingresos trimestrales se puede observar claramente que los ingresos registrados en pesos, hay un crecimiento exponencial debido al fenómeno conjunto inflación - devaluación de la moneda, ya que el aumento de ingresos en los nueve años sería 2248 %, lo cual resulta inverosímil. Por otro lado, la conversión de los ingresos a dólares muestra una curva con fluctuaciones para distintos períodos (picos y valles), lo cual resulta razonable para este tipo de negocios, pero conservando el orden de magnitud tanto en sus valores máximos y mínimos (rango aprox. de 286 millones). En este sentido otras fuentes reportan ingresos similares: (https://es.statista.com/estadisticas/1147932/b2b-ingresos-telecomunicaciones-linea-fija-argentina/). Dichas fluctuaciones exacerbadas podrían explicarse en parte por el atraso cambiario que registra el país históricamente.
 
Los datos muestran un descenso en los ingresos promedio a partir del pico máximo en 2017 hasta 2021, teniendo en cuenta varios factores a considerar como el efecto "pandemia" y ya en el 2022 se percibe una recuperación de los ingresos respecto a los 3 años inmediatamente anteriores.


## **`KPIs propuestos`**

Como analista de datos y inteligencia de negocios, aquí se presentan cinco KPIs (Indicadores Clave de Desempeño) que podrían ser relevantes para la empresa prestadora de servicios de telecomunicaciones:

1. Penetración trimestral de Internet fijo por provincia o región: Este KPI medirá la proporción de hogares en cada provincia o región que tienen acceso a Internet fijo. Ayudará a identificar las áreas con mayor y menor penetración de Internet fijo, lo que permitirá a la empresa enfocar sus esfuerzos en expandir su cobertura y mejorar la conectividad en áreas con baja penetración.

2. Velocidad media de bajada de Internet fijo por provincia o región al cabo de tres meses: Este indicador evaluará la velocidad promedio de descarga de Internet fijo en cada provincia o región. Una velocidad de descarga más rápida generalmente indica una mejor calidad de servicio. La empresa puede utilizar este KPI para identificar áreas con baja velocidad de descarga y trabajar en mejoras de infraestructura o tecnología para aumentar la satisfacción del cliente.

3. Distribución de los accesos totales nacionales a Internet fijo por tecnología: Este KPI mostrará la distribución de los accesos a Internet fijo según las diferentes tecnologías utilizadas, como fibra óptica, DSL, cable, etc. Proporcionará información sobre qué tecnologías son más populares entre los usuarios y ayudará a la empresa a tomar decisiones estratégicas sobre la inversión en tecnología y la planificación de la infraestructura.

4. Ingresos trimestrales por la prestación del servicio de Internet fijo por provincia o región: Este indicador medirá los ingresos generados por el servicio de Internet fijo en cada trimestre. Permitirá a la empresa hacer un seguimiento de su rendimiento financiero y evaluar la efectividad de sus estrategias de precios y marketing. También puede ayudar a identificar tendencias estacionales en los ingresos y tomar medidas correctivas si es necesario.

5. Número de accesos al servicio de Internet fijo por tipo de tecnología en cada provincia o región (trimestral): Este KPI proporcionará información sobre el número de accesos al servicio de Internet fijo desglosado por tipo de tecnología en cada provincia o región. Ayudará a la empresa a comprender qué tecnologías son más populares en diferentes regiones y adaptar sus estrategias de despliegue de infraestructura y comercialización en consecuencia.


**`Autor`**

David Nocera

davidandresnocera@gmail.com

GitHub: davidnocera85
