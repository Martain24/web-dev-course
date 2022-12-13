Casi mejor tener los apuntes en un archivo de texto sí

# Whay is deployment

- Hoy vamos a deploy la website. Vamos a aprender a poner nuestra website
  en la web para que todo el mundo la pueda ver.

- Para poder hacer esto tenemos que aprender que es deploying a website

- Deploying a website: mover el código de la web a una máquina remota (servidor)
  que sirva el sitio para los visitantes o clientes.

- Tenemos que mover las instrucciones a un servidor que pueda mostrarselas al mundo
  y en eso se basa el deployment de la website.

# Deployment on Netlify

- Simplemente entramos en la web y **drag and drop** nuestra carpeta con el código
  para que cree una website bien molona y guapa.

- Solo está una hora disponible. Si queremos que nuestra web esté arriba todo el
  rato con un dominio personalizado tenemos que comprar uno si o si. Cuando
  esté más en serio con la web me compraré un dominio sin duda.

- Es realmente barato comprar un dominio así que perfecto.

# Favicon (video 92)

- Podemos poner mariconadas de Favicon. Un logo guapo en el servidor. Puedes ir a una
  página web que genera un favicon dandole una imagen de cualquier cosa.

- Muy fácil añadir un favicon con el elemento _link_ de HTML.

# Relative and absolute paths

- De esto ya sabes manejarte bien. El absolute path va a todo el ordenador. Un relative path
  empieza en la carpeta en la que estás. Pon relative paths en deployment.

# GIT GitHub.

- Vamos a manejar las actualizaciones de nuestro código de una manera eficiente y eficaz
  usando GIT y GITHUB.

- **Version Managent Control**: La clave de esto es que cuando haces un proyecto dicho
  proyecto pasa por diferentes fases. Al principio es un papel en blanco; en una segunda
  fase tienes la estructura hecha; en una tercera fase escribes el contenido; en una cuarta
  fase le das estilo a la primera parte de tu proyecto...Es un conjunto de fases hasta
  que llegas a la última versión de tu código que representa al proyecto acabado. ¿Qué pasa
  si a partir de una fase la cagas? ¿Tienes que volver a empezar desde el principio? ¿O puedes
  empezar desde la fase donde la cagaste?. Aquí es donde entra en juego Version Managent.

Las dos herramientas que nos permiten ver los diferentes estados de nuestro código son:

- **Git**: es una herramienta local que podemos instalar en nuestro ordenador. Nos permite
  controlar las diferentes versiones de nuestro código a través de _repositorios_ organizados

- **GitHub**: es en la nube y nos proporciona las ventajas de GIT. Nos permite así colaborar
  de forma sencilla con otros programadores. Es la mayor plataforma de desarrollo en el mundo.

- Necesitamos juntar las dos herramientas para convertirnos en verdades desarrolladores.

# Command line interface (CLI) vs GUI (graphical user interface)

- La **GUI** es una forma gráfica de controlar y dar ordenes a un ordenador. La **CLI** se
  basa en hablar directamente con el ordenador.

- Con **CLI** accedemos con comandos al ordenador y la forma más facil y sencilla de manejar
  GIT y GITHUB es precisamente usando esta forma de hablar con el ordenador.

# MacOS terminal:
- Bueno, es la polla así resumiendo. 

- Con "ls" miras los archivos que tienes dentro del directorio
en el que te encuentras 

- Con "pwd" te dice en el directorio en el que te encuentras 

- Con "cd .." subes al directorio de arriba con respecto al que te 
encuentras.

- Con "cd nombre_directorio" accedes al directorio que tenga dicho nombre.
Además puedes darle a tab para el autocompletar

- Con "mkdir nombre_direcotorio" creas un directorio nuevo.

- Con "touch nombre_archivo.extension" creas un archivo en el directorio con dicha
extensión.

- Con "rmdir nombre_directorio" eliminar para siempre un directorio. Solo puedes 
hacer si el directorio está vacío.

- Con "rm nombre_archivo" borras el archivo en cuestión.