# forecasting_io

actualizado wed 

Problemas que tenemos:
* Tenemos la demanda calculada en anylogic con una normal que tiene como desvio el desvio del error (es uno solo para todo el período). Sería ideal sacar valores de desvío de errores mensuales en excel, después los pasamos a AL (es fácil)



To do list:
* Ver rúbrica
* Chequear valores de costos, eoq, rop, ss para todas las combinaciones de políticas y proveedores
* Calcular nivel de servicio (sale con las ventas no realizadas)
* Ver desvíos de error
* Exportar datos simulados
* Montecarlear


Previous steps:
  * cargar el excel 
  * No trabajar los dias domingo
  * Crear collections 
  * Armar la distribución normal que determine la demanda diaria
  * 1 producto= 1 agente --> crear llegadaClientes
  * Calcular costos unitario, de almacen y por ordenar
  * Agregar variabilidad del LT
  * Agregar stock de seguridad
  * hacer el calculo del stock de seguridad para p fijo.
  * arreglar todas las formulas (eoq;rop;etc) para que en vez de tomar el parámetro demandaMedia (que era un valor trivial) tome la media de nuestro pronóstico (que varía mes a mes)
  * Chequear la fórmula del stock de seguridad
  * Agregar variación de proveedores con collections que contengan lt, precios
