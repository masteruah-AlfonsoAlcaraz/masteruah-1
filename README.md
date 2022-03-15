# masteruah

# Práctica GIT

## Comandos iniciales

### Las explicaciones irán en los comentarios



> git init <!-- Iniciamos GIT -->

> git clone https://github.com/IgnacioJavier/masteruah <!-- Clonamos el directorio -->

>  cd masteruah  <!-- trabajamos en él -->

>  git status -s <!-- Comprobamos el estado de los archivos dentro y vemos que README.md no tiene seguimiento -->

> git add README.md <!-- hacemos seguimiento al archivo README -->

> git commit -m "Primer commit" <!-- Hacemos el primer commit -->

> git push <!-- Con esto guardamos los cambios en el repositorio inicial en mi cuenta de GitHub -->
>
> git add 1.txt

> git commit -m "Añadido 1.txt"

> git tag v0.1 <!-- Añadimos el primer tag -->

> git branch v0.2 <!-- Creamos la primera rama -->

> git checkout v0.2 <!-- Nos movemos a la rama -->
>
> git checkout main

> git add 1.txt

> git commit -m "Hola" <!-- Este es el commit donde hemos puesto "Hola" en 1.txt -->

> git checkout v0.2

>git add 1.txt

> git commit -m "Adios"

> git merge v0.2 <!-- Nos encontramos un mensaje que dice "CONFLICT (content): Merge conflict in 1.txt
> Automatic merge failed; fix conflicts and then commit the result." -->

> git branch -av <!-- Muestra las ramas, con más detalles -->

> git status <!-- Nos mostrará el estado de la fusión, con detalles -->

>git add 1.txt

> git commit -m "modificado main"

> git checkout v0.2

> git add 1.txt

> git commit -m "modificado v0.2"

> git checkout main

> git merge v0.2 <!-- Hemos resuelto el conflicto modoficando el documento para que sea igual en ambas ramas, en mi caso sólo he borrado todo -->

>git add README.md

> git commit -m "Tras fusión"

>git tag v0.2

> git branch -d v0.2 <!-- Este comando borra la rama -->

>git log --oneline <!-- Este es el comando que muestra los commit por ramas -->

>| NOMBRE  | GITHUB                                                       |
>| ------- | ------------------------------------------------------------ |
>| Alfonso | \| AlfonsoAlcaraz \|https://github.com/AlfonsoAlcaraz/masteruah\| |
>| Fran    | \| Franxer \|https://github.com/Franxer/masteruah\|          |
>| David   | \| DBRAVO \|https://github.com/DBRAV0/masteruah\|            |

> 
