# forecasting_io

actualizado fri 19:56

Problemas que tenemos:
* Podemos usar los datos del excel perfectamente excepto para calcular las variables que van definidas en la main (eoq, rop,ss). Ya probe sacarlas del main, pero no funciona porque el resto de las variables dejan de poder usarlas.
Probé con pronostico.get(0) y tira un error en la simulación y probe pronostico.getFirst() pero no funciona porque es una ArrayList (y tiene que quedarse asi).
* a arreglar si nos sobra tiempo: hacer que anylogic calcule el pronostico con table 

Next step: 
* arreglar todas las formulas (eoq;rop;etc) para que en vez de tomar el parámetro demandaMedia (que era un valor trivial) tome la media de nuestro pronóstico (que varía mes a mes)
* El sisttema hace mal la cuenta para calcular SS. A mi me da 112 y al sist 18.
* hacer el calculo del stock de seguridad para p fijo.


To do list:
* Chequear si el costo de almacenar funciona para sistema =0/1
* Calcular nivel de servicio (sale con las ventas no realizadas)
* Exportar datos simulados
* Montecarlear


Previous steps:
  * cargar el excel 
  * No trabajar los dias domingo
  * Crear las collections de pronosticoMedia y pronosticoDesvio
  * Armar la distribución normal que determine la demanda diaria
  * hacer el inject de la demanda diaria a la llegadaClientes (No lo uso)
  * 1 producto= 1 agente --> crear llegadaClientes
  * Calcular costos unitario, de almacen y por ordenar
  * Agregar variabilidad del LT
  * Agregué source para el stock de seguridad

