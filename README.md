# FUNDACION TORRIANI
Se quiere diseñar un sistema de bases de datos para una organización sin ánimo de lucro que lleve un seguimiento de elementos del patrimonio histórico en San Cristóbal de La Laguna.  

## ENTIDADES
* Punto de interés 
* Organismos de conservación pública.
* Eventos.
* Organizadores de eventos.
* Usuarios externos.

## ATRIBUTOS
* **Punto de interés** - Cada punto de interés debe estar ubicado en el mapa, debe tener año de construcción, historial de modificación, tipo de construcción, referencias y publicaciones históricas
* **Organismos de conservación pública** - Se debe conocer la inversión pública, la información relacionada con la protección, la riqueza generada, control de empresas contribuyentes, grado de protección, ente responsable del cumplimiento, sanciones que derivan del incumplimiento.
* **Eventos** - Fecha, localización, organizadores de eventos, duración.
* **Usuario externos** - Denuncias y valoraciones a visitas o a eventos.

## ASOCIACIONES

* El punto de interés es **conservado** por organismos de conservación pública.
* Los organismos de conservación pública **conservan** los puntos de interés. 
* Los organizadores de eventos **organizan** los eventos.
* Los eventos son **organizados** por una organización de eventos.
* Los eventos son **realizados** en un punto de interés.
* En el punto de interés se **realizan** eventos.
* Un usuario externo **participa** en eventos.
* En los eventos **participan** usuarios externos.
* Los usuarios pueden **denunciar** a un Punto de interés.
* Un punto de interés puede ser **denunciado** por los usuarios.
