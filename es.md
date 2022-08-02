# WIP
Comandos de Git:

- `clone <url>`                     # Clona un repositorio
- `add <filename>`			        # Annade el(los) archivos/directorios al stage
- `commit -m <message>`		    # Salva los cambios con un mensaje
- `push` 				            # Sube los commits locales a un remote (sync)
- `push --force` 			        # Sube los cambios a la fuerza (No se recomienda su uso si mas de un dev trabaja en el repo, tener cuidado)
- `git push --force-with-lease` # Personalmente recomiendo esta forma de forzar push (Solo se suben los cambios si no hay nuevos cambios hechos por otro dev)
- `pull`				            # Descargar cambios del remote al local
- `log`				            # Muestra el historial de commits
- `reset --hard <commit hash>`	# Resetear a un punto especifico del historial (si no se proporciona el hash resetea los cambios no commiteados)
- `reflog` 				        # Historial simplificado (Rara vez lo uso)
- `branch <branch-name>`		    # Crea una rama nueva
- `branch --list` 			    # Lista las ramas
- `branch -D <branch-name>`		# Elimina la rama
- `checkout <branch-name>`		# Pararse en la rama
- `checkout -b <branch-name>` # Crea una rama nueva y se para en ella
- `checkout -`                # Cambiar a la rama en la que se estuvo anteriormente
- `merge <branch-name>`		    # Mergear rama en current
- `rebase <branch-name>`		    # Aplica los cambios de la rama en la current
- `status`				        # Muestra el estado del stage y otros datos
- `git rebase master && git reset master` # Solo intentalo
