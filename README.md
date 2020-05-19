# TFM_Analisis-predictivo-de-la-contaminacion-en-Granada

Se han desarrollado varios notbook por medio de Anaconda para la construccion de modelos predictivos del nivel total de Particulas en el aire en la ciudad de Granada.

El programa esta compuesto de los siguientes notebooks:
 
  - WebScraping Extraccion Contaminacion v02.ipynb: Extraccion inicial de los datos de contaminacion de las distintas estaciones de medicion de la ciudad de Granada. Teniendo que configurar unicamente el año que se quiere extraer.
  
  - Analisis Descriptivo Climatologia.ipynb: Exploracion de los datos metereologicos de la ciudad.
  
  - Analisis Descriptivo Contaminacion.ipynb: Exploracion de los datos de contaminacion de la ciudad.
  
  - PreProcesing_V02.ipynb: Preparacion de los datos para su posterior utilizacion en los modelos predictivos.
  
Los modelos estan subdividos en 4 carpetas por distincion de modelo utilizado en cada uno.

Son 6 ejecuciones distinta por cada modelo para la comparacion entre las distintas estaciones de medicion. Los titulos de cada notbook hace referencia al modelo utilizado, estacion de contaminacion y a la estacion de metereologia:

      Estacion de contaminacion:
        - TablaGN: Granada Norte
        - TablaPC: Palacio de los Congresos
        - TablaCD: Armilla
        
      Estacion Metereologica:
        - MetGA: estacion metereologica del Aeropuerto de Granada
        - MetGBA: estacion metereologica de la Base Aerea de Granada
