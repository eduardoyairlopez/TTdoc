# TTdoc

Pasos para usar el git


# necesitan clonarlo a su pc, ya sea por ssh o https

1. git clone git@github.com:darcusfenix/TTdoc.git
1. git clone https://github.com/darcusfenix/TTdoc.git



# ya lo tienen en su pc, ahora pueden hacer cambios
# para agregar cosas a sus repositorio local con dos opciones, si agregan archivos es con -> git add --all o si modifican archivos con -> git add .:

2. git add .
2. git add --all



# ahora para guardar los cambios en una versión, por decir así. es con:

3. git commit -m "texto que describe el cambio"


# y ya por último para enviar los cambios al repositorio remoto, en este caso github con :

4. git push origin master



# Si es por https les pedirá sus claves de github y si es por ssh tendrán que generar su clave publica de ssh y darsela a github. Pero esto primerero los debo tener con permisos pra que ustedes puedan hacer push