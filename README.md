# clase-de-github - cambio en la rama dev       hh
Ejemplo de github y sus codigos 


git clone +url //para descargar un repositorio de github a mi computadora.

.....::::Configuracion de git en computadora::::.....

git config --global user.name " "//configuracino de usuario en la computadora
git config --global user.email " "	//configuracion de correo en la computadora

.....................................................


ssh-keygen //para crear la ssh key, y nos indica la ruta donde se guarda 
cat +url generada por ssh-keygen 	//nos conecta con github

git init 	//crea un nuevo repositorio
touch +nombrte del archivo 	//crea un nuevo archivo 
git add +nombre del archivo 	//agrega el archivo creado
git commit -m "+descripcion del archivo"	//comando para hacer el commit al repositorio de un cambio

git remote add origin +url	//para conectar los repositorios
git pull origin master		//origin es el nombre de la conexion con el remote repo	
git push origin master		//master es la branch o rama

