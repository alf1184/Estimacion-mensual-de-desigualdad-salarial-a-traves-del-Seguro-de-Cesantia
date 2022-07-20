# desigualdad_seguro_cersantia
### Cálculos de indicadores de desigualdad de ingresos a partir de datos del Seguro de Cesantía

En los scripts disponibles se trabaja la base de datos del Seguro de Cesantía para calcular distintos indicadores de desigualdad salarial entre trabajadores chilenos. 

El principal desafío radica en la naturaleza censurada de los datos de ingreso, en cuanto estos solo se reportan hasta la remuneración máxima imponible. Para hacerse cargo de este problema, salarios por sobre este límite son imputados a través del fit de una distribución paramétrica. 

Adicionalmente, se crea un indicador que considera a aquellas personas que han dejado de cotizar en el Seguro y, que por lo tanto, no se sabe si se encuentran inactivas, o trabajando por cuenta propia o de manera informal. Para ello se utiliza un método hot deck de imputación a partir de individuos de las mismas características.

El PPT disponible ofrece un resumen de la metodología y los resultados.


