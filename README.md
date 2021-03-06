# Aprendizaje por Refuerzo

El presente repositorio se refiere a un curso sobre Aprendizaje por Refuerzo, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/) 

En este repositorio se modela en Python una microrred energética como un proceso de decisión de Marckov haciendo uso de la biblioteca [Pymgrid](https://github.com/Total-RD/pymgrid) con la finalidad de obtener un control adaptativo que maximice su potencial.

La micro-red energética elegida para su modelación, a partir de las más de 600 disponibles en Pymgrid, se compone por una fuente de generación fotovoltaica, una batería y un generador de energía no renovable.

Las series de tiempo de demanda y generación de energía solar, son aportados por la propia biblioteca Pymgrid usando datos reales de demanda energética y producción de energía fotovoltaíca, los primeros provenientes de [OpenEI](https://openei.org/wiki/Main_Page), y los segundos de el laboratorio de energía renovable [NREL](https://www.nrel.gov/research/data-tools.ht). Ambas series abarcan un año con un total de 8760 mediciones por hora.
