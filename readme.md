Full Astra Picon
Light on Transparent
By TSC

Sources by Ocram - thx


Puedes añadir una tarea a Cron para que se actualice cuando tu quieras.
Primero copia el fichero downloadDoT.sh en /usr/script
dale permisos de ejecución chmod 755 /usr/script/downloadLoT.sh

Si queremos que todos los viernes nos actualice los picon a las 5 de la mañana, tendriamos que editar el fichero de crontab /etc/cron/crontabs/root
Añadir al final la linea:

0 5 * * 5 sh /usr/script/downloadLoT.sh

El Script está hecho para los que tengan los picon en /hdd/
Si alguien tiene los picon en /usb/ tendría que editarlo
