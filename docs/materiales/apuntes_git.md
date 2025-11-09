# Apuntes de comandos git

## Introducción

Este documento tiene la intención de servir como material de referencia para situaciones en las cuales no conozca un comando o me los olvide.

## Comandos gestión local

- Inicializar nuevo repositorio
	`git init`
	
- Agregar archivo a *stagin area*
	`git add <archivo>`

- Crear commit
	`git commit -m "<mensaje>"`

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