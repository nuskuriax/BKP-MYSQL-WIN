# BKP-MYSQL-WIN
Backup en python para pasar un dump de mysql por red a un equipo windows o un NAS, manda mail si el bkp es exitoso o si no lo fue, junto a un archivo de log, poner en un cron para realizarlo automaticamente.
Modo de uso:

*Poner en el archivo credswidows el usuario, dominio y contraseña del windows/NAS que se va a usar para mandar la copia

*Poner en el archivo credsmysql el usuario y pass del mysql

*Editar el archivo de scriptbkp, poniendo los datos de la base y del windows/NAS

*Editar los archivos mail y mailmalo con las creds de office365 (o se puede adaptar a gmail u otro server de mails) y los datos, de, para, etc

*Ponerle permisos de ejecucion al scriptbkp

*Ponerlo en un cron (opcional)
