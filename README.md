El usuario podrá acceder a las distintas funcionalidades por medio de un menu (navbar) que ofrecerá las siguientes caracteristicas:
	- Crear Materia
	- Inscribir Alumno
	- Listar Alumnos Inscriptos por Materia
	
Atributos Entidades:
	- Materia:
		* nombre
		* cupo
	- Inscripcion:
		* nombre alumno
		* materia
	
Reglas de negocio:
	- El nombre de la materia debe ser requerido y no puede tener más de 50 caracteres.
	- El cupo es requerido y debe ser de tipo numérico.
	- Se debe validar que la materia no haya sido creada previamente.
	- El nombre del alumno es requerido y no debe tener más de 200 caracteres.
	- En la inscripción la materia a seleccionar debe ser un combo y es requerida.
	- Se debe verificar que la materia tenga cupos suficientes para realizar la inscripción.

Nota:
	- Las validaciones deben mostrarse junto al control que están validando, en caso de haber una validación general mostrarla al final del formulario.
	- No se debe utilizar herramientas no vistas durante las clases para resolver el problema.
	- Los componentes deben mostrarse y ocultarse a medida que el usuario va cambiando la funcionalidad desde el menú.
	- Es necesaria la utilización de servicios.

Diagrama de componentes:
