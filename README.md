# desigualdad_seguro_cersantia
### Cálculo de indicadores de desigualdad de ingresos a partir de datos del Seguro de Cesantía

El código disponible trabaja la base de datos del Seguro de Cesantía de Chile para calcular distintos indicadores de desigualdad salarial.

El principal desafío radica en la naturaleza censurada de los datos de ingreso, en cuanto estos solo se reportan hasta la remuneración máxima imponible. Para hacerse cargo de este problema, salarios por sobre este límite son imputados a través del fit de una distribución paramétrica. 

Adicionalmente, se crea un indicador que considera a aquellas personas que han dejado de cotizar en el Seguro y, que por lo tanto, no se sabe si se encuentran inactivas, o trabajando por cuenta propia o de manera informal. Para ello se utiliza un método hot deck de imputación a partir de individuos de las mismas características.

El PPT disponible ofrece un resumen de la metodología y los resultados.
