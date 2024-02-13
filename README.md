TITULO: "MODELOS DE MACHINE LEARNING PARA LA PREDICCIÓN DEL PRECIO DE LA ELECTRICIDAD EN EL MERCADO ESPAÑOL"

AUTOR: Iñigo Elorza Barea

TUTOR: Aber Angel Soriano Vazquez

FECHA: Julio 2023

INDICE
1. SÍNTESIS DEL TRABAJO ...................................................... 7
   
3. INTRODUCCION .............................................................. 8
   
  2.1. MODULOS DEL MÁSTER RELACIONADOS CON EL TRABAJO FIN DE MÁSTER .......... 9
  
5. ANTECEDENTES .............................................................. 10
   
  3.1 IMPORTANCIA DE LA ENERGIA ELECTRICA .................................... 10

  3.2 MARCO REGULATORIO ...................................................... 11
  
  3.3 SISTEMA ELÉCTRICO ESPAÑOL .............................................. 12
  
  3.4 ETAPAS DEL SISTEMA ELÉCTRICO ESPAÑOL ................................... 14
  
  3.5 ESTRUCTURA DE GENERACIÓN DE LA EE EN ESPAÑA ............................ 15
  
    3.5.1 Tecnologías de producción de ee .................................... 15
    
    3.5.2 Evolución de la producción de ee ................................... 18
    
  3.6 AGENTES DEL MERCADO .................................................... 23
  
  3.7 MERCADO ELECTRICO ESPAÑOL .............................................. 25
  
  3.8 FORMACION DEL PRECIO DE LA ENERGIA ELECTRICA ........................... 26
  
    3.8.1. Formación del precio en el mercado mayorista a plazo .............. 26
    
    3.8.2. Formación del precio en el mercado mayorista diario ............... 27
    
  3.9 ESTADO DEL CONOCIMIENTO ................................................ 28
  
    3.9.1 Introducción ....................................................... 29
    
    3.9.2 Horizontes de previsión ............................................ 30
    
    3.9.3 Descripción general de las metodologias de modelado ................ 30
    
7. BUSSINES CASE ............................................................. 33
  
9. OBJETIVOS A ALCANZAR ...................................................... 34
    
11. DATOS DE PARTIDA ......................................................... 36
    
  6.1 INTERVALO TEMPORAL ..................................................... 36
  
  6.2 DIA DE LA SEMANA ....................................................... 39
  
  6.3 VARIABLES CONSIDERADAS ................................................. 40
  
  6.4 ANALISIS DE LOS DATOS .................................................. 45
  
  6.5 EXPLORACION DE LAS VARIABLES ........................................... 51
  
    6.5.1 VARIABLE: Precio medio diario energía eléctrica (Pre_elec) ......... 52
    
    6.5.2 VARIABLE: Demanda media diaria (Dem) ............................... 53
    
    6.5.3 VARIABLE: Precio del petróleo (Prec_petr) .......................... 53
    
    6.5.4 VARIABLE: Precio del gas natural (prec_gas) ........................ 54
    
    6.5.5 VARIABLE: Precio medio diario del carbón (Prec_car) ................ 55
    
    6.5.6 VARIABLES: Producción por tecnología ............................... 55
    
    6.5.7 VARIABLE: Temperatura (Temp_)....................................... 58
    
    6.5.8 VARIABLES: Velocidad del viento .................................... 64
    
    6.5.9 VARIABLE: Reservas hidráulicas (Res_hidr) .......................... 68
    
    6.5.10 VARIABLE: Precio derechos de emisión CO2 (Der_CO2) ................ 69
    
    6.5.11 VARIABLE: Situación socio-económica del país (Ibex) ............... 70
    
    6.5.12 VARIABLE: Intercambio de EE con otros países (int_ee) ............. 71
    
  6.6 TRATAMIENTO DE LOS DATOS Y FORMACION DEL DATASET ....................... 71
  
    6.6.1 Union de las variables en un dataframe ............................. 72
    
    6.6.2 Tratamiento de los valores faltantes ............................... 73
    
    6.6.3 Correlacion entre variables ........................................ 75
    
    6.6.4 Dataset final ...................................................... 79
    
    6.6.5 Tratamiento de los valores outliers ................................ 81
    
  6.7 ANALISIS DE LAS VARIABLES .............................................. 83
  
    6.7.1 Variable de respuesta (Pre_elec) ................................... 83
    
    6.7.2 Variables de entrada ............................................... 85
    
13. METODOS Y TECNICAS EMPLEADAS ............................................. 91
    
  7.1 DIVISION DE LOS DATOS PARA LOS MODELOS ................................. 92
  
  7.2 ESTANDARIZACIÓN DE LOS DATOS ........................................... 93
  
  7.3 METRICAS DE VALIDACION DE LOS MODELOS .................................. 94
  
  7.4 MODELO DE REGRESION LINEAL MULTIPLE .................................... 95
  
  7.5 MODELO K VECINOS MÁS CERCANOS (KNN) .................................... 98
  
  7.6 MODELO ARBOL DE DECISION ............................................... 101
  
  7.7 MODELO RANDOM FOREST ................................................... 103
  
  7.8 MODELO XG BOOST ........................................................ 105
  
  7.9 MODELO RED NEURONAL .................................................... 107
  
15. ANALISIS DE LOS RESULTADOS OBTENIDOS...................................... 110
    
  REGRESION LINEAL MULTIPLE .................................................. 110
  
  K VECINOS MÁS CERCANOS ..................................................... 111
  
  ARBOLES DE DECISION ........................................................ 111
  
  RANDOM FOREST .............................................................. 112
  
  XG BOOST ................................................................... 113
  
  RED NEURONAL ............................................................... 114
  
17. CONCLUSIONES ............................................................. 115
    
19. REFERENCIAS BIBLIOGRAFICAS ............................................... 122
    
11.ANEXOS  ................................................................... 124

  ANEXO I : ARCHIVOS CSV  .................................................... 124
  
  ANEXO II: EXPLORACION DE LAS VARIABLES ..................................... 126
  
  ANEXO III: UNION Y TRATAMIENTO DE LOS DATOS ................................ 177
  
  ANEXO IV: CORRELACION ENTRE VARIABLES ...................................... 209
  
  ANEXO V: PROCESADO OUTLIERS (ELIM) ......................................... 218
  
  ANEXO V I : PROCESADO OUTLIERS (L IM T) .................................... 278
  
  ANEXO VII: ESTUDIO VARIABLES ............................................... 359
  
  ANEXO VIII : REGRESION LINEAL (OUT ELIM) ................................... 370
  
  ANEXO IX : REGRESION LINEAL (OUT LIM ....................................... 376
  
  ANEXO X : KNN (OUT_ELIM .................................................... 383
  
  ANEXO XI : KNN (OUT LIM .................................................... 389
  
  ANEXO XII : ARBOL DE DECISION .............................................. 395
  
  ANEXO XIII : RANDOM FOREST ................................................. 401
  
  ANEXO XIV : XG BOOST ....................................................... 410
  
  ANEXO XV RED NEURONAL 8 0 2 0 .............................................. 419
  
  ANEXO XVI : RED NEURONAL 70 30 ............................................. 466   
