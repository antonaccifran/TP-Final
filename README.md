# TP-Final
INFORME DE OPTIMIZACIÓN

SKYFLY AIRLINES
📋 A) Descripcion del Proyecto:
La aerolinea SkyFly Airlines de origen Ruso ha contratado a la consultora Smart Data Solutions para llevar a cabo un analisis de sus datos sobre sus vuelos y sus pasajeros. Como bien sabemos, la industria aeronáutica es dinámica y altamente competitiva, por eso la idea es presentar un proyecto del que se pueda extraer insights valiosos y toma de decisiones estratégicas con el objetivo de expandir y optimizar su presencia en el mercado.

❌ B) Problemática:
Las aerolíneas se enfrentan actualmente a numerosos desafíos, entre ellos, una creciente competencia por las rutas, incrementos en el precio del petróleo, conflictos laborales y elevados impuestos. Este problema afecta la rentabilidad de la aerolínea.

🎯 C) Objetivo Principal:
El objetivo principal del proyecto es identificar, a través del análisis de datos, patrones y áreas de mejora en los indicadores claves relacionados con la eficiciencia de la aerolinea y la experiencia del cliente. Se buscará obtener insights que permitan a SkyFly diseñar una estrategia enfocada en optimizar su operatoria y aumentar la lealtad de los pasajeros. El valor agregado de este proyecto, radica en que nuestras recomendaciones se basan en datos precisos y accionables, lo que posibilita una toma de decisiones basada en evidencias.

📊 D) Resultados esperados e impacto:
El proyecto contribuirá a transformar la manera en que la aerolínea administra sus vuelos e interactúa con sus clientes, permitiendo posicionar a SkyFly de manera más competitiva en el mercado, lo que se traducirá en una mejora en la rentabilidad en el mediano plazo.

E) Entregable:
Smart Data Solutions le presentará el 13 de Diciembre del 2024 un Informe interactivo a la empresa que consta de un Dashborad con los KPI´s claves, analisis especificos y recomendaciones a los Directivos para que los directivos puedan avanzar con acciones concretas en la empresa en un corto/mediano plazo y así lograr mejoras en la rentabilidad de la empresa.

F) Responsables del Informe:
  1) Empresa: Smart Data Solutions.
  Consultora global especializada en análisis de datos con mas de 10 años en el mercado.
  
  2) Colaboradores: Noelia Adagio, Marcela Camerota, Francisco Antonacci, Josefina Perez Alisedo
G) Tecnologias Utilizadas:
MySQL - Server: Base de Datos

🐍 Python: Utilizado para realizar el EDA. Librerías: Pandas, Numpy, Matplotlib, Seaborn.

📊 Power BI: Se utiliza Power Query para la limpieza de datos. Power BI para la creación del Informe (Dashboard y análisis con visualizaciones interactivas)

Herramientas de soporte: Draw.io (para el modelo relacional), Github (plataforma que permite compartir y colaborar el proyecto), Trello (herramienta que nos permite gestionar el proyecto y las tareas de forma colaborativa:)

Se contrato el servicio del Hosting de Railway para desplegar la base de datos en la nube.

H) Base de Datos:
La base de datos proporcionada por el cliente consta de 8 tablas relacionadas en un formato SQLite. Abarca información de sus vuelos, aeropuertos en los que opera, aeronaves de su tropa, reservas, etc en un período de Junio a Septiembre del 2017. Las tablas son:

aircrafts_data: Contiene la información sobre los aviones (9 filas, 3 columnas) airports_data: Contiene la data de los aeropuertos (104 filas, 5 columnas) boarding_passes: Detalles sobre los boletos de embarque (579686 filas, 4 columnas) bookings: Datos de las reservas (262788 filas, 3 columnas) flights: Información de cada vuelo (33121 filas, 10 columnas) seats: Información sobre los asientos de los aviones (1339 filas, 3 columnas) tickets_flights: Detalles de los tickets, los vuelos correspondientes y el precio (1045726 filas, 4 columnas) tickets: Información de los tickets y de los pasajeros correspondientes (366733 filas, 3 columnas)

I) Tareas
El proyecto se divide en las siguientes fases:

Base de Datos: Obtención de la base de datos del cliente en formate SQLite.
Elaboración del Modelo relacional (relaciones entre la data): Se realizó el modelo relacional en Draw.io
Normalización y limpieza de los datos para lograr análisis fiables: Se realizó la limpieza de la base de datos en Power Query.
Análisis Exploratorio de Datos (EDA): Identificación de tendencias y patrones. Se realizó el EDA en Python relacionando distintas variables y en Power BI a traves de la creación de medidas y graficos variados.
Realización y presentación del reporte (Power BI): Se realizó el reporte en Power BI respetando la estética del logo de la empresa SkyFly Airlines. El reporte está compuesto por 4 solapas: PORTADA, DASHBORAD, ANALISIS ESPECIFICO y RECOMENDACIONES.
