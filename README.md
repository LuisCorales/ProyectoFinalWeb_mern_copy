# ProyectoFinalWeb
Aplicacion realizada en el stack mern

El proyecto esta enfocado en la arquitectura MVC para ello se utilizo las siguientes tecnologias: Mongo para la base de base de datos, Express para el tema del servidor, Node para el tema de las dependencias y libreriras y React para la parte del fronted

El proyecto qque se va a realizar es : Calcular Multas de equipos prestados en base a la fecha inicio del prestamo , fecha finalizacion prestamo y fecha de entrega del equipo, Si el equipo no ha sido devuelto va mantener el estado de Prestado y si no presentara fecha de entrega. En el caso que el equipo no ha sido entregado dentro del filtro de multas se calculará la multa hasta la fecha actual ( Today() ). En el contralador se calculará $5 por cada día de no cumplir la entrega pactada

Hare un incapie en la libreria mongoose que es algo importante la ultima version esta "deprecate" y tiene errores de compilacion al igual que la variable "dotenv" por lo cual mi sugerencia seria instalar la libreria npm i mongoose@ "ES COLOCAR UNA VERSION ANTIGUA" NO UTILICES LA VERSION ACTUAL esto tambien aplica para npm i dotenv@ "COLOCAR UNA VERSION ANTIGUA" es un pequeño error de la libreria por asi decirlo, para que no tengas inconvenientes y pueda desplegar tu aplicacion.