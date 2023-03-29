# DTS08-ProyInd-2
Repositorio de Proyecto Individual 2 para Data Science HENRY

# INTRODUCCIÓN
El índice S&P 500 es uno de los índices bursátiles más importantes y representativos del mercado de valores de los Estados Unidos. Durante su historia, este indicador ha experimentado altibajos y ha sido testigo de varios eventos económicos y políticos que han afectado su desempeño.

Éste trabajo de análisis del índice S&P 500 para los últimos 23 años, pretende llevar a cabo un análisis detallado del rendimiento del índice durante dicho período, incluyendo la identificación de tendencias, patrones y factores que han influido en su desempeño. Se utilizarán herramientas y técnicas de análisis para evaluar el rendimiento del índice en diferentes períodos y para comparar su desempeño con otros índices bursátiles.

Por otro lado, se explorarán superficialmente algunos factores macroeconómicos y políticos que han podido tener un impacto en el desempeño del índice, como las recesiones económicas, las fluctuaciones del mercado de materias primas, las políticas gubernamentales y las crisis geopolíticas. Se analizará cómo estos factores han afectado la rentabilidad de las empresas que cotizan en el índice y cómo esto a su vez ha influido en su desempeño general.

Se espera que este análisis proporcione una idea general de la evolución del mercado de valores de los Estados Unidos y cómo los factores macroeconómicos y políticos han influido en el desempeño del índice S&P 500.

![](https://github.com/hoyped/DTS08-ProyInd-2/blob/main/_src/S&P500.png)

El índice S&P 500 representa el desempeño de las 500 empresas más grandes de Estados Unidos, según su capitalización de mercado. Fue creado y es mantenido por Standard & Poor's, una agencia de calificación crediticia y proveedora de índices financieros.

El S&P 500 se considera un indicador representativo del mercado de valores de EE. UU. y se utiliza comúnmente como un barómetro para medir el rendimiento del mercado de valores en general. Las empresas incluidas en el índice representan una amplia gama de sectores, incluyendo tecnología, salud, energía, finanzas y más.

La capitalización de mercado se calcula multiplicando el precio actual de las acciones de una empresa por el número total de acciones en circulación. Por lo tanto, las empresas con mayor capitalización de mercado tienen un mayor peso en el índice. El S&P 500 se considera un índice ponderado por capitalización, lo que significa que las empresas más grandes tienen un mayor impacto en el desempeño general del índice.

Para efectos del presente se reducirá el grupo de compañías al top 10 histórico según su permanencia en durante los últimos 23 años.

# CONTENIDO

**1. ANÁLISIS EXPLORATORIO DE LOS DATOS (*EDA*)**
Se propone como punto de partida un análisis exploratorio que permita obtener un resumen de estadísticas descriptivas de los datos, análisis univariable (distribución), análisis bivariable (correlación), detección de outliers y su tratamiento, así como cualquier técnica de estudio que permita un completo entendimiento de los datos.

Lo anterior fue desarrollado mediante el IDE **Visual Studio Code** para el lenguaje de desarrollo y programación **Python**.

![](https://github.com/hoyped/DTS08-ProyInd-2/blob/main/_src/yahooFinanceAPI.jpg)

**2. DASHBOARD**
Un dashboard es una herramienta de visualización de datos que ayuda a las organizaciones a monitorear y analizar su desempeño en tiempo real y proporciona una vista rápida y clara de los datos clave para la toma de decisiones informadas.

Los resultados obtenidos en éste análisis se dispondrán para visualziación en el archivo (.pbix) para otorgar un panorama visual y dinámico del comportamiento del Índoce S&P 500, así como otros importantes indicadores durante los últimos 23 años (2000-2022).

Lo anterior fue desarrollado utilizando la potente herramienta de visualización y análisis Power BI.

![](https://github.com/hoyped/DTS08-ProyInd-2/blob/main/_src/Power-BI.png)

**3. KPI's**
En el desarrollo del presente proyecto y tomando en cuenta que el Índice S&P 500 es un reflejo de la salud de la economía de los Estados Unidos, se proponen los indicadores de Producto Interno Bruto (PIB), Tasa de Inflación (CIP) y Confianza Empresarial (TC) de dicho país; no debemos desconocer igualmente que el mismo Índice es sinónimo de indicador.

*Producto Interno Bruto*
El Producto Interno Bruto (PIB) es una medida económica que se utiliza para estimar el valor total de los bienes y servicios finales producidos dentro de un país durante un período de tiempo determinado, generalmente un año. El PIB es una de las medidas más utilizadas para evaluar la salud económica de un país.

*Tasa de Inflación*
La tasa de inflación es la tasa a la cual el nivel general de precios de los bienes y servicios en una economía está aumentando durante un período de tiempo determinado. Es decir, la tasa de inflación mide el aumento porcentual en el precio promedio de una canasta de bienes y servicios en una economía. Una tasa de inflación positiva indica que los precios están aumentando, mientras que una tasa de inflación negativa indica que los precios están disminuyendo con el tiempo.

*Confianza Empresarial*
El índice de confianza empresarial es una medida que se utiliza para evaluar el grado de optimismo o pesimismo que tienen las empresas en relación a las perspectivas económicas futuras. Este índice se basa en encuestas realizadas a empresarios y ejecutivos de empresas, en las que se les pregunta su opinión sobre factores económicos importantes, como la situación actual de la economía, la situación financiera de su empresa, sus planes de inversión, entre otros. Si el índice de confianza empresarial es alto, se espera que las empresas estén dispuestas a invertir más en sus negocios y contratar más trabajadores, lo que a su vez puede impulsar el crecimiento económico.

*Índide S&P 500*
Ya definido lineas arriba

![](https://github.com/hoyped/DTS08-ProyInd-2/blob/main/_src/KPI.jpg)










El análisis exploratorio de los datos *-(EDA, por sus siglas en inglés)-* es un punto fundamental en todo proyecto de análisis de datos. Al utilizar técnicas de visualización y análisis estadísticos, es posible identificar patrones y relaciones importantes en los datos, así como posibles problemas o fuentes de error. Estos hallazgos sirven para guiar el diseño e implementación de modelos de análisis más avanzados, ayudando a los analistas a tener una comprensión más profunda de los datos.

Lo anterior fue desarrollado utilizando la libreria **pandas profiling** del lenguaje de desarrollo y programación **Python**

![](https://github.com/hoyped/DTS08-ProyInd-1/blob/main/_src/04.png)

**4. SISTEMA DE RECOMENDACIÓN**
Se solicita realizar un modelo de machine learning para crear un sistema de recomendación de películas para usuarios, donde teniendo su identificación y dato de una película o serie, el sistema indique ***SI recomienda o NO*** dicho contenido para el usuario en cuestión.
En el desarrollo del presente punto se proponen tres (3) métodos de clasificación para obtener un modelo que nos brinde confianza en la predicción, dicho de este modo se trabajaran los siguientes: ***KNN - K Nearest Neighbors***, ***Random Forest Classifier*** y ***Cosine Similarity***.
En este punto es importante aclarar que las métricas de los módelos dieron resultados muy disímiles, indicando que la configuración de las herramientas algorítmicas tiene importante incidencia en los resultados y confiabilidd de las predicciones.

Lo anterior fue desarrollado utilizando la libreria **scikit learn** del lenguaje de desarrollo y programación **Python**

![](https://github.com/hoyped/DTS08-ProyInd-1/blob/main/_src/07.JPG)
![](https://github.com/hoyped/DTS08-ProyInd-1/blob/main/_src/08.JPG)

**5. VIDEO**
En este se evidencia la ejecución del desarrollo **API** del punto dos (2), así como una explicación de los modelos de machine learning entrenados.
Enlace al video:
https://drive.google.com/file/d/1CKfkQyh2gEcJIVFCWTfd_arpod9Eae5K/view?usp=share_link


**CONCLUSIONES**
-   Los modelos de ML pueden ser muy efectivos para predecir resultados en gran variedad de problemas, desde decisión de compra hasta diagnóstico médico.
-   La calidad de los resultados depende en gran medida de la calidad de los datos utilziados para entrenar el modelo.
-   La selección del algoritmo de aprendizaje automático adecuado es crucial para obtener resultados confiables.
-   Los modelos de ML son altamente escalables y pueden manejar enormes cantidades de datos.
-   Interpretar los resultados obtenidos a través de modelos de ML es todo un desafio que requiere habilidades especializadas.


***MUCHAS GRACIAS***
