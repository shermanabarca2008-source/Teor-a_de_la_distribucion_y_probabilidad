# APE07._

## 📌 Conclusión General

Durante el desarrollo de este análisis se aplicó el **modelo de distribución Normal** sobre los datos reales correspondientes a la **Remuneración Mensual Unificada** de los servidores públicos del Municipio de Loja, con el propósito de comprender su comportamiento estadístico y evaluar su ajuste a una distribución teórica.

En una primera etapa, se modeló y representó gráficamente la **Función de Densidad de Probabilidad (PDF)** de una distribución Normal y se calcularon **puntajes Z**, los cuales permitieron interpretar la posición relativa de los datos respecto a la media en unidades de desviación estándar.

Posteriormente, bajo el supuesto de normalidad, se estimó que aproximadamente el **83,08 %** de los servidores públicos perciben una remuneración mensual dentro del intervalo analizado, utilizando las propiedades de la distribución Normal para calcular probabilidades.

Sin embargo, al aplicar el **test de normalidad de Shapiro-Wilk**, se obtuvo un resultado de **W = 0.5988** y un **valor-p = 3.22 × 10⁻⁶³**, evidencia suficiente para **rechazar la hipótesis de normalidad** de los datos.

Adicionalmente, el análisis descriptivo mostró una **asimetría positiva de 3.75** y una **curtosis de 21.41**, indicando que la distribución presenta una cola larga hacia la derecha y una alta concentración de valores, alejándose considerablemente del comportamiento esperado de una distribución Normal.

En consecuencia, aunque el modelo Normal resulta útil como una herramienta de aprendizaje y aproximación teórica, **no representa adecuadamente el comportamiento real del conjunto de datos**. Para obtener inferencias más precisas sería recomendable emplear modelos que se ajusten mejor a la distribución observada, como una **distribución Log-Normal** o aplicar transformaciones logarítmicas antes de realizar análisis probabilísticos.

---

### ✅ Aspectos más relevantes

- 📊 Se modeló la distribución Normal y se calcularon puntajes Z para analizar la posición relativa de los datos.
- 📈 Bajo el supuesto de normalidad, se estimó que el **83,08 %** de las remuneraciones se encuentran dentro del intervalo estudiado.
- ❌ El **test de Shapiro-Wilk** confirmó que los datos **no siguen una distribución Normal** (**W = 0.5988; p = 3.22 × 10⁻⁶³**).
- 📉 La distribución presenta **asimetría positiva (3.75)** y **curtosis elevada (21.41)**, evidenciando una marcada desviación del modelo Normal.
- 🎯 Para futuros análisis estadísticos, se recomienda utilizar modelos más adecuados para datos asimétricos, como la **distribución Log-Normal**, con el fin de obtener resultados más confiables y representativos.

---
# APE08._

## 📌 Conclusión General

Durante el desarrollo de este análisis se comprobó el **Teorema del Límite Central (TLC)** mediante simulaciones y datos reales, demostrando que la distribución de las **medias muestrales** tiende a aproximarse a una distribución Normal, aun cuando la población original presenta una distribución asimétrica.

En una primera etapa, se trabajó con una **población sintética de distribución exponencial**, donde se generaron **1000 muestras de tamaño \(n = 30\)**. Los resultados evidenciaron que las medias muestrales convergieron a una distribución aproximadamente Normal y que la diferencia entre la media poblacional y la media de las muestras fue prácticamente nula, confirmando que la **media muestral es un estimador insesgado**.

Posteriormente, se aplicó el mismo principio a un **conjunto de datos reales del Municipio de Loja**, utilizando la variable **Remuneración Mensual Unificada**. A pesar de presentar una **asimetría positiva de 3.75**, el procedimiento de **bootstrapping** con **500 muestras de tamaño \(n = 40\)** mostró una aproximación a la distribución Normal de las medias muestrales, validando la aplicación de técnicas de inferencia estadística sobre esta variable.

Finalmente, se analizó el comportamiento del **Error Estándar de la Media**, comprobando que disminuye conforme aumenta el tamaño de la muestra, siguiendo la relación inversa con la raíz cuadrada de \(n\). Este resultado demuestra que incrementar el tamaño muestral mejora la precisión de las estimaciones, aunque requiere un esfuerzo considerable en la recolección de datos, ya que **para reducir el Error Estándar a la mitad es necesario cuadruplicar el tamaño de la muestra**.

En conjunto, los resultados obtenidos evidencian la importancia del **Teorema del Límite Central** como fundamento de la inferencia estadística, al permitir realizar estimaciones confiables sobre una población incluso cuando los datos originales no siguen una distribución Normal.

---

### ✅ Aspectos más relevantes

- 📊 Se verificó experimentalmente el **Teorema del Límite Central** mediante simulaciones y datos reales.
- 📈 Las **medias muestrales** convergieron a una distribución aproximadamente Normal, aun cuando la población original era asimétrica.
- 🎯 La **media muestral** demostró ser un **estimador insesgado** de la media poblacional.
- 💼 El análisis sobre la **Remuneración Mensual Unificada** del Municipio de Loja confirmó la aplicabilidad de la inferencia estadística mediante técnicas de **bootstrapping**.
- 📉 Se comprobó que el **Error Estándar de la Media** disminuye al aumentar el tamaño de la muestra.
- 📏 Para **reducir el Error Estándar a la mitad**, es necesario **cuadruplicar el tamaño de la muestra**, aspecto fundamental para la planificación de estudios estadísticos y proyectos de investigación.

---
# APE09._

## 📌 Conclusión General

En el desarrollo de esta práctica se aplicaron diferentes técnicas de **estimación estadística** mediante intervalos de confianza, utilizando tanto la **distribución Normal (Z)** como la **distribución *t* de Student**, según las características de la muestra analizada.

En una primera etapa, se realizaron estimaciones para **muestras grandes**, calculando correctamente el **estimador puntual**, el **margen de error** y los **límites inferior y superior** del intervalo de confianza mediante la distribución Z.

Posteriormente, se trabajó con **muestras pequeñas**, aplicando la **distribución *t* de Student** e incorporando correctamente los **grados de libertad (\(df=n-1\))**, lo que permitió obtener intervalos de confianza adecuados cuando la desviación estándar poblacional era desconocida.

Como parte del proyecto integrador, se construyó un **intervalo de confianza** para una variable del conjunto de datos del Municipio de Loja, representándolo gráficamente mediante **barras de error**, facilitando la interpretación visual de la incertidumbre asociada a la estimación.

Finalmente, se realizó un **análisis de sensibilidad**, demostrando que el **margen de error aumenta conforme se incrementa el nivel de confianza**. Asimismo, se comprobó que el margen de error disminuye al aumentar el tamaño de la muestra, evidenciando la importancia de contar con un número suficiente de observaciones para obtener estimaciones más precisas.

En conjunto, este análisis permitió comprender la importancia de los **intervalos de confianza** como herramientas fundamentales de la inferencia estadística, ya que no solo proporcionan una estimación del parámetro poblacional, sino también una medida de la incertidumbre asociada a dicha estimación.

---

### ✅ Aspectos más relevantes

- 📊 Se calcularon correctamente **intervalos de confianza para muestras grandes** utilizando la distribución **Normal (Z)**.
- 📈 Se aplicó la **distribución *t* de Student** para muestras pequeñas, utilizando los **grados de libertad (\(df=n-1\))**.
- 💼 Se construyó un **intervalo de confianza** sobre datos reales del Municipio de Loja y se representó mediante **barras de error**.
- 📉 Se comprobó que **al aumentar el nivel de confianza, el margen de error también aumenta**, produciendo intervalos más amplios.
- 📏 Se verificó que **para reducir el margen de error es necesario incrementar el tamaño de la muestra**, siendo necesario **cuadruplicar el número de observaciones para reducir el error a la mitad**.
- 🎯 Los intervalos de confianza constituyen una herramienta esencial para la **toma de decisiones**, ya que permiten cuantificar la incertidumbre y obtener estimaciones más confiables que una estimación puntual.

---
# APE10._

## 📌 Conclusión General

Durante este análisis se evaluó el comportamiento de las **pruebas de hipótesis** y la influencia que tiene el **tamaño de la muestra** sobre el **valor-p**, evidenciando cómo este indicador puede variar significativamente aun cuando la diferencia entre los datos observados y la hipótesis nula sea mínima.

Los resultados mostraron que, **a medida que el tamaño de la muestra aumenta**, el **valor-p disminuye considerablemente**, incrementando la probabilidad de rechazar la hipótesis nula. Sin embargo, esto no implica necesariamente que la diferencia encontrada tenga importancia desde un punto de vista práctico.

En el caso analizado, la diferencia entre la media observada (**5.01 V**) y la media planteada en la hipótesis nula (**5.00 V**) fue de apenas **0.01 V**. Aunque con muestras muy grandes esta diferencia puede resultar estadísticamente significativa, su impacto sobre el funcionamiento real del sistema o del sensor es prácticamente despreciable.

Este comportamiento pone de manifiesto la importancia de distinguir entre la **significancia estadística** y la **significancia práctica**. Mientras la primera depende del valor-p obtenido en la prueba estadística, la segunda evalúa si la magnitud de la diferencia observada tiene consecuencias reales dentro del contexto del problema.

Asimismo, se evidenció que el **valor-p no debe interpretarse de manera aislada**, sino complementarse con otras herramientas de inferencia estadística, como los **intervalos de confianza**, el **tamaño del efecto** y la **potencia estadística**, para obtener conclusiones más sólidas y fundamentadas.

Finalmente, el análisis permitió comprender que, en escenarios de **Big Data**, las pruebas de hipótesis tradicionales tienden a detectar diferencias extremadamente pequeñas debido al enorme tamaño muestral, lo que incrementa la probabilidad de rechazar la hipótesis nula incluso cuando dichas diferencias carecen de relevancia práctica.

---

### ✅ Aspectos más relevantes

- 📊 Se comprobó que **el valor-p disminuye conforme aumenta el tamaño de la muestra**, incluso cuando las diferencias reales son muy pequeñas.
- 📈 Un **valor-p pequeño** no implica necesariamente que exista una diferencia importante desde el punto de vista práctico.
- ⚖️ Se destacó la diferencia entre **significancia estadística** y **significancia práctica**, conceptos fundamentales para una correcta interpretación de los resultados.
- 📉 Se concluyó que el **valor-p debe analizarse junto con otras métricas**, como los **intervalos de confianza**, el **tamaño del efecto** y la **potencia estadística**.
- 💻 En entornos de **Big Data**, las pruebas de hipótesis presentan una sensibilidad muy elevada, pudiendo detectar diferencias mínimas que no generan un impacto real en la toma de decisiones.
- 🎯 Una interpretación adecuada de los resultados estadísticos requiere considerar tanto la evidencia matemática como el contexto práctico del problema analizado.

---
# APE11._
## 📌 Conclusión General

Durante el desarrollo de esta práctica se aplicaron diferentes **pruebas de hipótesis para dos muestras**, tanto **independientes** como **pareadas**, con el propósito de determinar si existían diferencias estadísticamente significativas entre dos grupos de datos.

En la primera parte, se realizó una **prueba *t* para muestras independientes (A/B Testing)** con el fin de comparar el consumo de memoria RAM entre dos algoritmos. El análisis permitió establecer si las diferencias observadas entre las medias eran estadísticamente significativas, proporcionando una base objetiva para comparar el rendimiento de ambos algoritmos.

Posteriormente, se aplicó una **prueba *t* para muestras pareadas**, evaluando el efecto de un nuevo firewall sobre la latencia de un mismo conjunto de servidores antes y después de su implementación. Al tratarse de observaciones dependientes, el análisis permitió medir el impacto real de la optimización considerando las diferencias individuales de cada servidor.

Finalmente, se aplicó un **Análisis de Varianza (ANOVA de un factor)** sobre el conjunto de datos del proyecto integrador para comparar las medias de los distintos grupos definidos por el **régimen laboral**. Tras identificar diferencias significativas entre los grupos, se utilizó la **prueba Post-Hoc de Tukey**, la cual permitió determinar específicamente qué pares de grupos presentaban diferencias estadísticamente significativas en sus remuneraciones.

En conjunto, los resultados evidencian la utilidad de las pruebas de hipótesis y del ANOVA como herramientas fundamentales para comparar grupos y respaldar la toma de decisiones mediante evidencia estadística, permitiendo distinguir entre diferencias atribuibles al azar y diferencias con sustento estadístico.

---

### ✅ Aspectos más relevantes

- 📊 Se aplicó una **prueba *t* para muestras independientes (A/B Testing)** para comparar el rendimiento de dos algoritmos.
- 💻 Se evaluó el consumo de memoria RAM mediante una prueba estadística que permitió determinar si existían diferencias significativas entre ambos algoritmos.
- 🔄 Se realizó una **prueba *t* para muestras pareadas**, comparando la latencia de los mismos servidores antes y después de implementar un nuevo firewall.
- 📈 Se aplicó un **ANOVA de un factor** para comparar las remuneraciones promedio entre los diferentes **regímenes laborales** del Municipio de Loja.
- 📋 La **prueba Post-Hoc de Tukey** permitió identificar con precisión qué grupos presentaban diferencias estadísticamente significativas.
- 🎯 Las pruebas de hipótesis y el ANOVA demostraron ser herramientas fundamentales para analizar diferencias entre grupos y apoyar la toma de decisiones basada en evidencia estadística.

