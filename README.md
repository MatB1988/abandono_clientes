# Proyecto de Abandono de Clientes en Banco

## Descripción del Negocio

Este proyecto aborda una problemática en la cual un gerente de una sucursal bancaria se encuentra preocupado por el creciente número de clientes que abandonan los servicios de tarjetas de crédito ofrecidos por el banco.

El objetivo principal es predecir de manera proactiva qué clientes están en riesgo de abandonar el servicio para poder intervenir y ofrecerles mejores servicios, con la esperanza de cambiar sus decisiones en la dirección opuesta.

El conjunto de datos utilizado consta de información de 10,000 clientes, incluyendo datos demográficos como edad, salario, estado civil, límite de tarjeta de crédito, categoría de tarjeta de crédito, entre otras variables. Se observa que solo un 16.07% de los clientes han abandonado el servicio, lo que sugiere un conjunto de datos desbalanceado y la necesidad de realizar transformaciones para abordar este desequilibrio.

## Requerimientos y Ejecución del Proyecto

Este proyecto requiere el uso de datos de clientes, preferiblemente en formato CSV, para su análisis y aplicación de modelos predictivos. Se puede ejecutar utilizando entornos de Python con bibliotecas como pandas, scikit-learn , Logistic Regression, KNN, Decision Tree, Random Forest y XGB Classifier utilizando Grid Search.

## Análisis y Soluciones Propuestas

El desarrollo de este análisis se centra en identificar posibles causas y ofrecer soluciones al problema recurrente de abandono de clientes en el banco. Se han utilizado modelos para llevar a cabo este análisis, específicamente el modelo XGB Classifier.

### Variables Significativas

Las variables más significativas identificadas para el óptimo desarrollo del modelo XGB Classifier son:

- **Total_Trans_Ct**
- Total_Revolving_Bal
- Total_Relationship_Count
- **Total_Trans_Amt**
- Months_Inactive_12
- **Age**

### Soluciones Propuestas

Se proponen las siguientes soluciones, enfocadas en las variables destacadas en negrita:

1. **Total_Trans_Amt**: Se sugiere enfocarse en los clientes con tarjeta azul e ingresos menores a 40K, ya que representan una proporción significativa de clientes que abandonan el servicio. Ofrecerles tarjetas de mayor categorización (Silver, Gold o Platinum) podría incentivar su permanencia.

2. **Total_Trans_Amt**: Implementar un motor de recomendación para productos dirigidos principalmente a clientes con tarjeta Blue, que son los que más abandonan el servicio.

3. **Age**: Segmentar los clientes en grupos etarios y realizar estrategias de marketing agresivas hacia los jóvenes menores de 30 años y el grupo de personas mayores de 40 años, con el objetivo de atraer poblaciones de otras edades y así aumentar la clientela y reducir los abandonos.

4. **Total_Trans_Ct** y **Total_Trans_Amt**: Realizar campañas de marketing dirigidas a los clientes que realizan pocas transacciones o transacciones de bajos montos, ofreciéndoles promociones y alianzas con locales de gastronomía, vestimenta, entre otros, para fomentar el uso de la tarjeta.


