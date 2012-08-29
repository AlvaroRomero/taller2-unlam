COMANDOS UTILIZADOS:

ssh-keygen -t rsa -C "your_email@youremail.com"
#Necesitamos una clave ssh para autenticar con github

git remote add origin git@github.com:claudio-unlam-taller2/taller2-unlam.git
#agregamos el repositorio remoto de github 

git config --global user.name "Firstname Lastname"
#configuracion de nombre de usuario

git config --global user.email "your_email@youremail.com" 
#configuracion de mail de usuario

git init
#se inicializa el repositorio

git add .
#agregamos todos los archivos

git commit -m "commit inicial"
#realizamos el primer commit inicial

git push -u origin master
#subimos el branch al repositorio externo

git status
#comando para verificar el estado del branch

git log
#historial de modificaciones

git checkout -b datosParticulares origin/master
#creamos un nuevo branch

git checkout master
#cambiamos de branch

git clone git@github.com:claudio-unlam-taller2/taller2-unlam.git
#clonamos el proyecto
