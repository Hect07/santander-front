#   Iniciar proyecto de git
git init

#   Preparar archivos que se convertirán en un commit
git add .
##  El punto es para agregar todos los archivos modificados

#   Crear commit con su mensaje
git commit -m "Aqui va el mensaje"

#   Agregar remoto "Solo la primera vez"
git remote add origin "url"

#   Enviar commits -u origin master
git push -u origin master