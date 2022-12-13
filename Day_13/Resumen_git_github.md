
- Vamos a hacer un pequeño resumen:
    - *git init*: Cremos un repositorio de git
    - *git add*: añadimos cambios que hemos hecho
    - *git commit -m "cambio"*: confirmamos los cambios realizados
    - *git branch*: las branches son desviaciones de la main 
    branch. Las hacemos para que el main no se toque y no añadimos 
    código al main hasta que lo hayamos testeado correctamente en 
    las otras branches
    - *git checkout -b "namebranch"*: creamos una nueva branch

- Resumen de github:
    - *git remote add origin "url"*: conectamos nuestro repositorio
    local con un repositorio en github en la nube
    - *git push origin "namebranch"*: añadimos la información actualizada 
    en la branch al repositorio de github desde git. 
        - Aquí es donde nos pedirán lo del token y eso
        que vamos a tener que crearlo y cancelar el pop-up que nos sale 
        en vs-code
    - *git pull origing "namebranch"*: cogemos actualizacioens de un repositorio
    de github conectado a un repositorio local
    - *git clone "url"*: clonamos repositorio de github y lo tenemos disponible
    en local para nosotros. 
    - *Personal acces token*: tienes que crear ese token 
    para acceder a movidas recuerda eso siempre.