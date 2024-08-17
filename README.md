# Estadistica
La estadística es una rama de las matemáticas que se ocupa de la recopilación, análisis, interpretación, presentación y organización de datos. Es una herramienta fundamental en la investigación científica y en la toma de decisiones informadas en diversas áreas como la ciencia, la ingeniería, la economía, la medicina, la sociología, y muchas otras. La estadística se divide en dos ramas principales: estadística descriptiva y estadística inferencial.

1. Estadística Descriptiva
La estadística descriptiva se encarga de organizar, resumir y describir los datos mediante medidas numéricas, gráficos y tablas. Su objetivo es proporcionar una visión clara y concisa de las características principales de un conjunto de datos.

a) Medidas de Tendencia Central
Estas medidas resumen un conjunto de datos utilizando un solo valor que representa el centro de la distribución de los datos.

Media: Es el promedio aritmético de todos los valores en un conjunto de datos.

Media
=
∑
𝑖
=
1
𝑛
𝑥
𝑖
𝑛
Media= 
n
∑ 
i=1
n
​
 x 
i
​
 
​
 
donde 
𝑥
𝑖
x 
i
​
  son los valores de los datos y 
𝑛
n es el número de observaciones.

Mediana: Es el valor que divide el conjunto de datos en dos mitades iguales. Es menos sensible a valores extremos que la media.

Moda: Es el valor que aparece con mayor frecuencia en un conjunto de datos.

b) Medidas de Dispersión
Estas medidas indican qué tan dispersos o concentrados están los datos alrededor de la tendencia central.

Rango: Es la diferencia entre el valor máximo y el valor mínimo en un conjunto de datos.

Rango
=
Valor m
a
ˊ
ximo
−
Valor m
ı
ˊ
nimo
Rango=Valor m 
a
ˊ
 ximo−Valor m 
ı
ˊ
 nimo
Varianza: Es la medida de la variabilidad de los datos en relación con la media. La varianza de una muestra se calcula como:

Varianza
=
∑
𝑖
=
1
𝑛
(
𝑥
𝑖
−
𝑥
ˉ
)
2
𝑛
−
1
Varianza= 
n−1
∑ 
i=1
n
​
 (x 
i
​
 − 
x
ˉ
 ) 
2
 
​
 
donde 
𝑥
ˉ
x
ˉ
  es la media de la muestra.

Desviación Estándar: Es la raíz cuadrada de la varianza, y proporciona una medida de dispersión en las mismas unidades que los datos originales.

Desviaci
o
ˊ
n est
a
ˊ
ndar
=
Varianza
Desviaci 
o
ˊ
 n est 
a
ˊ
 ndar= 
Varianza
​
 
c) Medidas de Forma y Relación
Asimetría (Skewness): Indica la simetría de la distribución de los datos. Si es positiva, la distribución está sesgada a la derecha; si es negativa, está sesgada a la izquierda.

Curtosis: Mide la "altura" de la distribución. Una curtosis alta indica una distribución con colas largas (leptocúrtica), mientras que una curtosis baja indica colas cortas (platicúrtica).

Covarianza: Mide cómo dos variables varían juntas. Una covarianza positiva indica que las variables tienden a aumentar juntas, mientras que una covarianza negativa indica que una tiende a aumentar mientras la otra disminuye.

Coeficiente de Correlación: Es una medida estandarizada de la relación lineal entre dos variables, que varía entre -1 y 1. Un valor de 1 indica una relación positiva perfecta, -1 una relación negativa perfecta, y 0 ninguna relación lineal.

𝑟
=
Cov
(
𝑋
,
𝑌
)
𝜎
𝑋
𝜎
𝑌
r= 
σ 
X
​
 σ 
Y
​
 
Cov(X,Y)
​
 
donde 
𝜎
𝑋
σ 
X
​
  y 
𝜎
𝑌
σ 
Y
​
  son las desviaciones estándar de 
𝑋
X y 
𝑌
Y.

2. Estadística Inferencial
La estadística inferencial se basa en el uso de muestras de datos para hacer estimaciones, predicciones o tomar decisiones sobre una población más grande. Utiliza la teoría de la probabilidad para evaluar la fiabilidad de las conclusiones extraídas.

a) Estimación
Puntual: Es una única estimación de un parámetro poblacional (como la media o la proporción) basada en los datos de una muestra.

Por Intervalo: Proporciona un rango de valores dentro del cual se espera que se encuentre el parámetro poblacional con un cierto nivel de confianza. Un intervalo de confianza es un ejemplo típico.

IC
=
𝑥
ˉ
±
𝑍
×
𝜎
𝑛
IC= 
x
ˉ
 ±Z× 
n
​
 
σ
​
 
donde 
𝑍
Z es el valor crítico de la distribución normal, 
𝜎
σ es la desviación estándar y 
𝑛
n es el tamaño de la muestra.

b) Pruebas de Hipótesis
Las pruebas de hipótesis son procedimientos para decidir si una afirmación sobre una población es consistente con los datos observados en una muestra.

Hipótesis Nula (
𝐻
0
H 
0
​
 ): Es la afirmación que se somete a prueba, generalmente una afirmación de no efecto o no diferencia.

Hipótesis Alternativa (
𝐻
1
H 
1
​
 ): Es lo contrario de la hipótesis nula, y es lo que se intenta demostrar.

Nivel de Significancia (
𝛼
α): Es la probabilidad de rechazar la hipótesis nula cuando es verdadera. Comúnmente se usa 
𝛼
=
0.05
α=0.05.

Valor p: Es la probabilidad de obtener un resultado al menos tan extremo como el observado, asumiendo que la hipótesis nula es verdadera. Si el valor p es menor que 
𝛼
α, se rechaza 
𝐻
0
H 
0
​
 .

c) Modelos Estadísticos
Regresión Lineal: Es un modelo que describe la relación entre una variable dependiente y una o más variables independientes mediante una línea recta.

𝑦
=
𝛽
0
+
𝛽
1
𝑥
+
𝜖
y=β 
0
​
 +β 
1
​
 x+ϵ
donde 
𝑦
y es la variable dependiente, 
𝑥
x es la variable independiente, 
𝛽
0
β 
0
​
  es la intersección, 
𝛽
1
β 
1
​
  es la pendiente, y 
𝜖
ϵ es el término de error.

Análisis de Varianza (ANOVA): Se utiliza para comparar las medias de tres o más grupos y determinar si al menos uno es significativamente diferente de los demás.

Modelos de Regresión Logística: Se utilizan para modelar la probabilidad de un evento binario, es decir, un resultado con dos posibles valores (por ejemplo, éxito/fallo).

3. Aplicaciones de la Estadística
La estadística se utiliza en una amplia variedad de campos, entre ellos:

Ciencias de la Salud: Evaluación de la efectividad de tratamientos médicos, estudios epidemiológicos, análisis de datos genéticos.
Economía y Finanzas: Análisis de tendencias económicas, evaluación de riesgos financieros, estudios de mercado.
Ingeniería: Control de calidad, fiabilidad de sistemas, optimización de procesos.
Ciencias Sociales: Encuestas de opinión, estudios de comportamiento humano, análisis de datos demográficos.
Ciencia de Datos y Machine Learning: Creación de modelos predictivos, análisis de grandes conjuntos de datos, algoritmos de aprendizaje automático.
Conclusión
La estadística es una disciplina fundamental que permite comprender y gestionar la variabilidad en los datos, hacer inferencias sobre poblaciones a partir de muestras, y tomar decisiones informadas en presencia de incertidumbre. Ya sea a través de herramientas descriptivas para resumir datos o métodos inferenciales para hacer predicciones y probar hipótesis, la estadística proporciona un marco riguroso y matemático para analizar el mundo a nuestro alrededor.
