# Modelo OSI

**OSI** - Open Systesm Interconnection

es modelo generalizado que se puede usar para estandarizar la comunicacion de diferentes provedores

es un modelo de referencia de como deben tener lugar las comunicaciones. divide la agrupacion en **capas**.

un sistema bajo este esquema de llama **arquitectura en capas**

se usa para comprender los procesos de comunicaion y ver que funciones se realiza por cada capa. si se desarrolla un protocolo para cada capa solo nos preoucapamos por el protocolo de cada capa.

## ventajas del modelo OSI
divide en proceso de la red en componentes mas pequenos y simples.

permite compatibilidad

# funciones de Capa

Applicacion - capa superior habla con el usuario

Presentacion - como se muestra la informacion al usuario

Sesion - Inicio configuracion y desconexion, determina si los datos permanecen locales o enviarse a un componente remoto

Transporte - define funciones a nivel de red.
- Control de flujo que garantiza la integridad de datos y permite transporte de datos confiables. Velocidad e integraidad, si llego el mensaje?
- Conexion Orientada a la Comunicacion: protocolo de enlace de tres vias, para poder enviar informacion debe inciarse sesion. Mando la peticion y checo si si llego la comunicacion. Windowing: segmento de datos que se puede enviar sirve para controlar la cantidad de segmentos de datos pendientes y no reconocidos

- red: gestiona el direccionamiento logico, determina la mejorm manera de mover el trafico, conecta diferentes redes. paquetes de red ynpaquetes de actualizacion de rutas.





