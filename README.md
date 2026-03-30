# Análisis de los Presupuestos Generales del Estado (PGE) - Datos de la Fundación Ciudadana CIVIO 

<img width="955" height="710" alt="image" src="https://github.com/user-attachments/assets/87862fd3-01e7-4635-a8e4-095a26c24d18" />

La **[Fundación CIVIO](https://civio.es/)** es una entidad privada sin ánimo de lucro orientada a la prestación de servicios de información e investigación periodística en España. Su objetivo fundamental está orientado a mejorar la transparencia y la veracidad en la comunicación de la actividad por parte de las instituciones públicas y privadas de nuestro país [Información de Actividad 📢](https://civio.es/nosotros/). 

La organización, aunque dedicada a la emisión de artículos de opinión y otras piezas informativas, también posee diversas fuentes de **[Datos](https://datos.civio.es/)** abiertos al público donde se puede encontrar información de muy diversa índole acerca de las **instituciones públicas**. Algunas de las áreas de interés en los que se agrupan los trabajos de investigación de la organización son las siguientes: 


- Funcionamiento de Instituciones
- Recursos Sanitarios
- Medio Ambiente y Meteorología
- Sanidad
- Indicadores de Poder Político
- Procesos de Contratación Pública
- Justicia
- Transparencia
- ...


En concreto, en este proyecto trabajaremos con una que recoge información acerca de las partidas aprobadas en los **[Presupuestos Generales del Estado (PGEs)](https://datos.civio.es/dataset/presupuestos-generales-del-estado/)** desde el año 2007 hasta el año 2022 (serie completa para cuando se realizó el análisis: Julio de 2024). Este conjunto de datos o "dataset" también es provisto por parte de la propia Fundación en su Repositorio GitHub [Fundación Ciudadana CIVIO](https://github.com/civio). La base de datos se puede solicitar previo contacto por correo electrónico en el siguiente enlace:

[Solicitud Base de Datos al Correo de CIVIO](https://datos.civio.es/dataset/presupuestos-generales-del-estado/)

[Descarga Directa GitHub](https://github.com/civio/presupuesto-pge/tree/master/data/es/pais)





## PROYECTO 

El proyecto de análisis se dividirá en 2 fases fundamentales:

1. Evolución de los Ingresos Públicos Totales recaudados por parte de las Administraciones Públicas (2007-2022)

* IMPUESTOS DIRECTOS 
  - Impuesto sobre la Renta de las Personas Físicas (IRPF)
  - Impuesto sobre Sociedades (IS)
  - Cotizaciones Sociales (CC.SS.)

* IMPUESTOS INDIRECTOS 
  - Impuesto sobre el Valor Añadido (IVA)
  - Impuestos sobre Hidrocarburos
  - Impuestos sobre el Tabaco y Bebidas Alcohólicas 


2. Evolución del Gasto Público Total presupuestado por parte de las AA.PP. (2007-2022)

* GASTO EN PENSIONES
* GASTO EN EDUCACIÓN
* GASTO EN SALUD Y SANIDAD
* GASTO MILITAR EN DEFENSA


3. Ranking de Comparación y Composición de los Ingresos y Gastos en el último año disponible (2023)





Este ejercicio de análisis pretende dar una visión acerca de las principales fuentes de recursos financieros que han obtenido las Administraciones Públicas o AA.PP. a lo largo de la última década y de dónde los obtienen en la actualidad. 

Cuando nos referimos a AA.PP. queremos decir todos los organismos asociados al Estado
(Gobierno Central + Comunidades Autónomas o CC.AA. + Corporaciones Locales o CC.LL. + Seguridad Social etc.) 

Los principales productos estadísticos utilizados para este análisis han consistido en una serie de datos tabulares en formato Excel/CSV que os dejo adjuntos en la pestaña "Datos" de igual forma que los originales que encontraréis en el repositorio de GitHub de CIVIO. En estas tablas se contiene información acerca de las siguientes variables:

-----------------------------------------------------------------------------------------------------------------------------
- EJERCICIO: Período al que son imputables las operaciones financieras
- CENTRO GESTOR: Organismo que realiza la operación
  
- FUNCIONAL: Código de identificación de la operación según su Estructura Funcional o COFOG
(https://www.hacienda.gob.es/es-ES/CDI/Paginas/ContabilidadNacional/COFOG/Clasificacion-funcional-del-gasto-de-las-Administraciones-Publicas.aspx)
- ECONÓMICA: Código de identificación de la operación según su Estructura Económica
(https://www.sepg.pap.hacienda.gob.es/sitios/sepg/es-ES/Presupuestos/PGE/ProyectoPGE2022/Documents/LIBROSALMON2022.pdf)

- DESCRIPCIÓN: Nombre del organismo o entidad pública que realiza la operación 
-----------------------------------------------------------------------------------------------------------------------------

P.D.

Si os fijáis, disponéis de una serie de gráficos de análisis con tablas y gráficos dinámicos en los apartados "Ingresos" y "Gastos" donde podéis descargar unas bases de datos unificadas personalmente por mí donde se contienen todas las observaciones de los archivos originales para cada año y contingencia. 
Gracias a esta herramienta podréis extraer vuestras propias conclusiones acerca de los datos brutos.   

Además, tengo que comentaros que he desarrollado una serie de "chunks" de código equivalente tanto en lenguaje R como en Python para realizar el análisis de los gráficos de forma equivalente por vuestra cuenta.


De todas maneras, parte de estos análisis los podéis encontrar ya presentados por parte de la organización en su apartado web ["¿Dónde van mis impuestos?"](https://dondevanmisimpuestos.es/), un trabajo de análisis y visualización de datos realizado igualmente por la Fundación y que ha dado inspiración a este proyecto. 


También conviene recordar que esto es un proyecto individual, con datos abiertos dispuesto a consultas y sugerencias para ahondar en más detalles relevantes que deseéis comentarme :D

Espero que os guste 😄




