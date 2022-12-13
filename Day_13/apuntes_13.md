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

- También puedes añadir un colaborador a tu proyecto, si en algún momento quieres
saber como vete al vídeo 111 del curso. De momento con lo que sabes creo que puedes ir 
tirando bastante bien 

- Recuerda que también puedes **clonar** un repositorio que esté en github 
para tenerlo de manera local. Simplemente copiar la url asociada a dicho 
repositorio y en el terminal escribes *git clone "url"* y se clonará todo 
el repositorio. Es una forma sencilla de acceder a proyectos de otros 
desarrolladores


# Contribuyendo a proyectos

- También podemos contribuir a proyectos open source. Es decir, podemos 
sugerir cambios a un desarrollador en su proyecto. Así podemos ayudar 
a solucionar bugs y mejorar ciertas movidas.

- Simplemente le damos a **fork** y guardamos el repositorio de otra persona 
en nuestra cuenta de github. Como está en nuestra cuenta ahora podemos 
acceder a él de manera remota desde nuestro ordenador con el personal 
acces que hayamos creado. 

- Una vez lo hayamos cambiado le damos a pull request y la magia ocurre. 
Si alguna vez te interesa copiar un código de otra persona mira el vídeo 
112 del curso