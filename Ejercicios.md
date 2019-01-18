1. Tienes que modificar la escena 5 de Hamlet en el fichero scene-5.txt. En dicha escena Hamlet encuentra al fantasma de su padre. Añade este texto al fichero:
ls
git add scene-5.txt
se añade
> Ghost: 
> My hour is almost come,
> When I to sulphurous and tormenting flames
> Must render up myself.
ctrl O para guardar
ctrl X para salir
2. Añade scene-5.txt al área de preparación.
git add scene-5.txt 
git commit scene-5.txt
3. Haz un commit con los cambios con un buen mensaje de commit.
git commit -m
4. Modifica las palabras del fantasma. Aquí tienes una sugerencia divertida:
ls
git add scene-5.txt
se cambian las frases del fantasma
> Ghost: 
> My hour is almost come,
> When I to sulphurous and tormenting balloons
> Must render up myself.
5. Devuelve el fichero al estado del último commit.
6. Cambia el nombre de LARRY por LAERTES en los ficheros scene-3.txt y scene-7.txt.
git add scene-3.txt
nano scene-3.txt
se cambia la palabra LARRY por LEARTES
ctrl-o
ctrl-x
git add scene-7.txt
nano scene-7.txt
se cambia la palabra LARRY por LEARTES
ctrl-o
ctrl-x
7. Añade los ficheros al área de preparación usando un único comando git.
git commit -a scene-2.txt
git commit -a scene-3.txt
git commit -a scene-5.txt
git commit -a scene-7.txt
8. Vamos a cometer un error a propósito. Borra cualquier línea del fichero scene-2.txt.
git add scene-2.txt
delete 
9. Añade scene-2.txt al área de preparación.
git add scene-2.txt
git commit scene-2.txt
10. Comprueba el estado del repositorio. 
git status
11. Devuelve scene-2.txt al directorio de trabajo.
git mv scene-2.txt repositoriolocal repositoriodetrabajo
12. Haz un commit para guardar los cambios realizados en el nombre de Larry por Laertes.
nano scene-3.txt
ctrl-o
ctrl-x
git commit
13. Busca el primer commit que has hecho y vuelve a dicho commit. Indica como has buscado el commit anterior y como has vuelto a él.
14. Crea una nueva rama llamada **reinventando_hamlet**
git checkout **reinventando_hamlet**
15. Cámbiate a dicha rama
cd **reinventando_hamlet**
16. Mejora la escena 2 como creas conveniente.
nano scene-2.txt

17. Haz un commit con los cambios con un mensaje adecuado.
git commit -a
18. Vuelve a la rama master.
19. Elimina la rama **reinventando_halet**
rm branch **reinventando_hamlet**
20. Crea una nueva rama, modifica algo en la rama master, haz commit y llévate los cambios a la rama que has creado.
git checkout
git commit -a
21. Provoca un conflicto entre la rama master y la rama que has creado (indica lo que has hecho). Une la rama a la rama master resolviendo el conflicto.
