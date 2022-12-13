# Vamos a github

- Nos vamos de lo local para manejar los repositotios de manera
remota en la nube mediante github.

- Podemos guardar nuestros proyectos en la nube y así poder 
acceder a ellos desde cualquier ordenador y en cualquier momento

- También nos permitirá hacer nuestra portfolio page para 
enseñar a otros developers y contratadores lo bueno que eres 
carajo.

- También es bueno para colaborar con otros desarrolladores. 
Es una forma sencilla para que todos tengan acceso al código 
y dicho código sea facil de manejar. 

- También se puede usar para contribuir y ayudar a otros desarrolladores 
con sus proyectos. 

# Muchas movidas:

- Vale, lo que tenemos que hacer es crear un repositorio vacío en github.
Después vamos al repositorio que tengamos en local y tenemos que escribir
lo siguiente: *git remote add origin "página web que nos ponga en github"*

- Es importante que la rama master sea cambiada de nombre y le llames main
con el siguiente código: *git branch -M main*

- Ahora lo único que tienes que hacer es poner *git push origin main* para 
que todo lo que tenga tu repositorio sea cargado en la nube de github. 
    - OJO: te va a aparecer un pop-up de VScode no le haces caso y le das 
    a cancelar
    - Después te pedirá que pongas tu NOMBRE de usuario de github y le 
    des a enter
    - Finalmente tendrás que escribir un token que habrás creado previamente
    en github en la parte de settings. (busca sino te acuerdas en internte 
    como crear token en github)

- Perfecto, ahora cuando hagas cambios localmente en el repositorio lo único que
tendrás que hacer será escribir *git push origin main* para que se actualice 
en la nube. 

- Además, si haces cambios desde la nube y después quieres traerlos a lo local
lo que tendrás que escribir será: *git pull origin main*.