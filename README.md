# TFM
Este repositorio recoge los *scripts* desarrollados para automatizar los análisis correspondientes al Trabajo de Fin de Máster "Modelización metabólica de comunidades microbianas estables crecidas con fuentes de carbono y energía únicas y simples" (Silvia Talavera Marcos, Máster en Bioinformática y Biología Computacional, Universidad Autónoma de Madrid).

**modelado.R** incluye el alineamiento con Nucmer, la creación de modelos con CarveMe y (opcionalmente) el análisis con Smetana para una pareja de nodos dada.
**annotate.R** se encarga de la anotación funcional con eggNOG-mapper y, opcionalmente, la creación de un modelo consenso. También es capaz de llamar a Nucmer para iniciar el proceso desde el principio. 
Las funciones definidas para estos scripts se encuentran en **utils.R**.
Por último, se han desarrollado dos scripts en Python para crear los consensos: **consenso.py** crea un modelo SBML a partir de otros modelos SBML y **consenso_EGG.py** crea una tabla de anotaciones consenso a partir de múltiples archivos de anotaciones.
