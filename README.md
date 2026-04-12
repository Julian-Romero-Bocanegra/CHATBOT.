# CHATBOT. V1
Integrantes: Edwin Stiven Pasto / Julián Romero Bocanegra.\
Docente: Diego Alejandro Barragán Vargas
Institución: Fundación Universitaria Compensar.


## Hallazgos
### 1. Deepseek
Se realizo la creacion de una cuenta, se configuro desde google coolab la llave secreta donde queda registrada la API KEY, sin embargo, en la ejecucion del programa al relizar peticiones aparece error 404, dando como resultado una conexion fallida con la API. Adicionalmente en la invetigacion realizada se determino que la API de Deepseek funciona con un costo sobre las peticiones realizadas, por lo cual se decidio realizar un cambion en la IA que toma de base el Chatbot para evitar dichos costos.

### 2. Gemini 
En vista de la novedades presentadas con la IA anterior, se evaluo la posibilidad de trabajar con Gemini IA como la base para las respuestas del Chatbot. Durante las pruebas realizadas se identificaron las siguiente novedades:
#### 1.1 Errores de conexion y Versionamiento
Apesar de el cambio de IA en las prueba de ejecucion y funcionamiento aparecio error 404 en todas las ocasiones, el progrma no consigue conectarse con las versiones de la IA, inicialmente se identifico que la version gemini-1.5-flash es obsoleta para la ejecucion requerida, se realizaron cambio a las versiones gemini-1.5-pro, gemini-pro y gemini-2.0-flash, sin embargo, con niguna fue posible superar el error de conexion 404.
#### 1.2 Error JSON vs API



