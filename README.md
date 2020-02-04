# demografia-padron-municipal
Este vocabulario ha sido desarrollado en el contexto de la actuación sobre datos abiertos del proyecto [Plataforma de Gobierno Abierto, Colaborativa e Interoperable](http://www.red.es/redes/es/que-hacemos/ciudades-inteligentes/proyectos-en-ciudades), de la [II Convocatoria de Ciudades Inteligentes](https://perfilcontratante.red.es/perfilcontratante/busqueda/DetalleLicitacionesDefault.action?idLicitacion=6707&visualizar=0) del [Ministerio de Economía](http://www.mineco.gob.es/) y Empresa lanzada a través de la [Entidad Pública Empresarial Red.es](http://www.red.es/) adscrita a la [Secretaría de Estado de Avance Digital de dicho Ministerio](http://www.mineco.gob.es/portal/site/mineco/avancedigital).

## Propósito y alcance del vocabulario
El propósito y alcance de este vocabulario está motivado por la definición proporcionada en la guía publicada por el Grupo de Trabajo de Datos Abiertos creado por la FEMP: ["Datos Abiertos: Guía estratégica para su puesta en marcha. Conjuntos de datos mínimos a publicar"](http://femp.femp.es/files/3580-1617-fichero/Gu%C3%ADa%20Datos%20Abiertos.pdf). Según este documento, el propósito de este vocabulario es representar la información de la población empadronada en la ciudad. Por lo tanto, el alcance del vocabulario se centra en cubrir la representación de aquellos datos que son intercambiados entre el INE y los ayuntamientos, concretamente, el fichero de relación de habitantes descrito como parte de los ficheros de intercambio de la categoría variaciones patronales . El fichero de relación de habitantes incluirá a todas las personas existentes en el padrón municipal de habitantes y su contenido es responsabilidad exclusiva del Ayuntamiento. Los datos de este fichero se denominan microdatos y son de uso interno del Ayuntamiento.

Por otra parte, en este dominio también se provee la representación de los macrodatos del padrón municipal, que constituyen los datos que se exponen al público. Estos datos se presentan como cubos de datos conformados por diferentes dimensiones y medidas de tal forma que permiten la explotación estadística de los datos del padrón.

## Desarrollo del vocabulario
El material generado en las diferentes actividades ejecutadas durante el desarrollo del vocabulario, casos de uso, historias de usuario, glosario de términos, etc., se encuentra disponible en la [Wiki del Vocabulario](https://github.com/CiudadesAbiertas/vocab-demografia-padron-municipal/wiki)

## Mantenimiento
Para gestionar aquellas incidencias o mejoras sugeridas con respecto al vocabulario te recomendamos seguir las guías proporcionadas en [Gestión de Issues](https://github.com/CiudadesAbiertas/vocab-demografia-padron-municipal/wiki/Gesti%C3%B3n-de-issues)

## Ejemplos
Algunas a realizar en un SPARQL endpoint de pruebas se han habilitado para ejemplificar su funcionamiento. Por un lado, varios datos ficticios han sido generados y posteriormente cargados en el endpoint con la finalidad de representarlos según el vocabulario de microdatos del padrón municipal. Se proveen varias [consultas](hhttps://github.com/CiudadesAbiertas/vocab-demografia-padron-municipal/blob/master/examples/queries.md) que permiten extraer información relevante de los habitantes. Por otro lado, a partir de los datos del padrón se han generado los cubos con los datos agregados de la población. En los [cubos de ejemplo](hhttps://github.com/CiudadesAbiertas/vocab-demografia-padron-municipal/blob/master/examples/queries-cubos-datos.md) se han incluido tanto las consultas para generar cada cubo así como las consultas para extraer la información agregada que contiene cada uno de ellos.
