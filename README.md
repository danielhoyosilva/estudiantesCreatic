# estudiantesCreatic
Curso de Servidores con NodeJS PM2 MYSQL


CREATE DATABASE creatic;
CREATE TABLE IF NOT EXISTS `estudiantes` (
  `id` int(5) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=1;

insert into "estudiantes" values (null, "Estudiante", "Creatic");
