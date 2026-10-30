# ClientClassifier
# Contexto y problema comercial
Una empresa ficticia de comercio electrónico vende productos de tecnología, hogar, moda, deportes, belleza y alimentos. Su
equipo comercial necesita anticipar el comportamiento de compra de cada cliente para planificar campañas, acciones de
retención y programas de lealtad. El problema consiste en clasificar a cada cliente en uno de cinco perfiles de comportamiento
durante los siguientes 90 días a partir de su historial previo.
La base contiene exactamente 1 000 000 de clientes sintéticos, 29 atributos predictivos, un identificador y una variable de
clase, para un total de 31 columnas. No contiene datos de personas reales ni reproduce estadísticas oficiales de una empresa o
del mercado mexicano. Su propósito es académico: análisis exploratorio, preprocesamiento y clasificación multiclase a gran
escala.
# Unidad de análisis y alcance temporal
Cada fila representa un cliente distinto. El corte histórico se fija al 30 de junio de 2026. Las variables con sufijo 365d resumen
del 1 de julio de 2025 al 30 de junio de 2026. La clase corresponde al 1 de julio al 28 de septiembre de 2026, ambos inclusive.
Todos los clientes tienen al menos 365 días de antigüedad. Los atributos sin sufijo se interpretan al corte o como promedios de
la ventana histórica.
El esquema supone una sesión registrada por cada compra, incluidas las ventas asistidas en tienda. La satisfacción representa la
experiencia general, incluso sin compra. El plazo de entrega es una estimación de servicio asignada al cliente. La categoría y el
método de pago preferidos pueden proceder de preferencias registradas sin compras previas.
# Especificación del archivo
Archivo clientes_comercio_1000000.csv. Codificación UTF-8, separador coma, encabezado en la primera línea, punto decimal y
sin índice de DataFrame. Los importes se expresan en pesos mexicanos.
