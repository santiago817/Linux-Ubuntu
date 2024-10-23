lo primero q hice es actualizar los paquetes de ubuntu con :

sudo apt update

despues instale el Ispeak

sudo apt install ispeak

despues comprobar q funcionaba asi q use el comando:

espeak -v es "Hola"

creo el archivo .sh 

touch recordatorio.sh

me fijo si se creo el archivo, asi q uso el comando "ls" como esta el archivo uso el comando:

nano recordatorio.sh 

ahora como estoy en el editor de texto , tnego q poner los comandos q voy a usar para q funcione la herramienta
despues de ingresar los comandos lo gurado y me salgo de nano


con este comando le estoy dando permisos de ejecucion

chmod +x recordatorio.sh

despues ingreso este comando para ejecutar el recordatorio.sh

./recordatorio.sh

al tocar enter me saldra un mensaje diciendo q tengo q actualizar ubuntu y para continuar tendre q tocar enter,
despues me saldra otro mensaje diciendo q tengo q poner un tiempo limite en segundos para q me vuelva a avisar ,
despues de q ingrese los segundos para q me avise saldra la voz advirtiendo de q se termino el tiempo de espera,
saldra otro mensaje diciendo q toque enter para salir 