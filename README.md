# forecasting_io

Next step: 
* arreglar todas las formulas (eoq;rop;etc) para que en vez de tomar el parámetro demandaMedia (que era un valor trivial) tome la media de nuestro pronóstico (que varía mes a mes)


To do list:
* Agregar variabilidad del LT
* Chequear si el costo de almacenar funciona para sistema =0/1
* Stock de seguridad (if en caso de sistema =0/1)
* Calcular nivel de servicio (sale con las ventas no realizadas)
* Exportar datos simulados


Previous steps:
  * cargar el excel 
  * No trabajar los dias domingo
  * Crear las collections de pronosticoMedia y pronosticoDesvio
  * Armar la distribución normal que determine la demanda diaria
  * hacer el inject de la demanda diaria a la llegadaClientes (No lo uso)
  * 1 producto= 1 agente --> crear llegadaClientes
  * Calcular costos unitario, de almacen y por ordenar
