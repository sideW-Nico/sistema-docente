# Apuntes de comandos git

## Introducción

Este documento tiene la intención de servir como material de referencia para situaciones en las cuales no conozca un comando o me los olvide.


## Reglas al publicar y crear commits

### Regla #1: Manejo de prefijos
Al inicio del mensaje de cada commit se deberá colocar uno de los siguientes prefijos:

- **feat**: Nueva funcionalidad  
- **fix**: Corrección de error  
- **docs**: Cambios en documentación  
- **style**: Cambios visuales o de formato  
- **refactor**: Reescritura sin cambiar comportamiento  
- **test**: Cambios en pruebas  
- **chore**: Tareas menores  
- **perf**: Optimización de rendimiento  
- **build**: Cambios en build o dependencias  
- **ci**: Cambios en integración continua  

### Regla #2: closing keywords
Al final de cada mensaje se deberá colocar una de las siguientes closing keywords seguido de su número de issue.

- **close**: Cierra la issue indicada cuando el commit llega a la rama principal  
- **closes**: Versión plural de *close*, con el mismo efecto  
- **closed**: Variante en pasado, también válida para cerrar la issue  
- **fix**: Cierra la issue asociada al corregir un error  
- **fixes**: Versión plural de *fix*, con el mismo efecto  
- **fixed**: Variante en pasado, también válida para cerrar la issue  
- **resolve**: Cierra la issue al indicar que fue resuelta  
- **resolves**: Versión plural de *resolve*, con el mismo efecto  
- **resolved**: Variante en pasado, también válida para cerrar la issue  


## Comandos gestión local

- Inicializar nuevo repositorio
	`git init`
	
- Agregar archivo a *stagin area*
	`git add <archivo>`
	
- Quitar archivo de *stagin area*
	`git restore --staged <archivo>...`

- Crear commit
	`git commit -m "mensaje"`

- Mostrar estado del repositorio
	`git status`
	
- Mostrar historial de commits
	`git log`
	`git log --oneline`
	
- Deshacer cambios hasta una commit anterior
	`git reset --hard <commit>`

## Comandos de gestión remota

- Agregar repositorio
	`git remote add <nombre> <URL>`
	
- Mostrar lista de ramas
	`git branch`

- Subir commits
	`git push`
	
- Obtener y fusionar cambios recientes
	`git pull`
	
	
## Manejo de versiones

- Listar etiquetas
	`git tag`
	
- Listar etiquetas por número de versión
	`git tag --sort=version:refname`

- Crear etiqueta
	`git tag -a <nombre> -m "mensaje"`
	
- Crear etiqueta sobre un commit específico
	`git tag -a <nombre> -m "mensaje" <commit>`

- Subir etiqueta en base a su nombre
	`git push origin <nombre>`

- Subir todas las etiquetas locales
	`git push origin --tags`
	
- Eliminar etiqueta remota
	`git push origin :refs/tags/<nombre>`