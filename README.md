# CHATBOT - SISTEMAS DIGITALES V2
Integrantes: Edwin Stiven Pasto / Julián Romero Bocanegra.\
Docente: Diego Alejandro Barragán Vargas
Institución: Fundación Universitaria Compensar.


## Hallazgos
### 1. Deepseek
Se realizo la creacion de una cuenta, se configuro desde google coolab la llave secreta donde queda registrada la API KEY, sin embargo, en la ejecucion del programa al relizar peticiones aparece error 404, dando como resultado una conexion fallida con la API. Adicionalmente en la invetigacion realizada se determino que la API de Deepseek funciona con un costo sobre las peticiones realizadas, por lo cual se decidio realizar un cambio en la IA que tomara de base el Chatbot para evitar dichos costos.

### 2. Gemini 
En vista de la novedades presentadas con la IA anterior, se evaluo la posibilidad de trabajar con Gemini IA como la base para las respuestas del Chatbot. Durante las pruebas realizadas se identificaron las siguiente novedades:
#### 1.1 Errores de Conexion y Versionamiento
Apesar de el cambio de IA en las prueba de ejecucion y funcionamiento aparecio error 404 en todas las ocasiones, el progrma no consigue conectarse con las versiones de la IA, inicialmente se identifico que la version gemini-1.5-flash es obsoleta para la ejecucion requerida, se realizaron cambio a las versiones gemini-1.5-pro, gemini-pro, gemini-2.0-flash, y gemini-1.5-flash-latest, sin embargo, con niguna fue posible superar el error de conexion 404.
#### 1.2 Error JSON vs API
Se utilizaron nuevos metodos de envio de las peticiones de consulta, esto se implemento mediante la creacion de un archivo JSON que enviara en un solo archivo la consulta completa. Esta funcionalidad tuvo inconvenientes con el error 400 (Bad Request) ya que entre la comunicacion entre el JSON y la API hay parametro que no coinciden entre la estructura del JSON y lo que espera la version del API, por lo cual este metodo no fue funcional.


