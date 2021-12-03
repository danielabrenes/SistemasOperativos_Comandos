# SistemasOperativos_Comandos
Se encuentran adjuntos varios comandos de Linux 
Comando | Uso
------------ | -------------
ip addr | Para ver la direccion IP
ping 8.8.8.8(direccion) | Acceso a internet
sudo apt install neofetch | Instalacion del neofetch
neofetch | Ejecuta el Neofetch
sudo apt | Para instalar paquetes
clear | Limpia la terminal
sudo apt update && sudo apt upgrade | Para las nuevas instalaciones realizarles una actualizacion
pwd | Muestra donde esta localizado en la terminal
sudo apt install cmatrix | Instalar matrix
cmatrix | Ejecuta la matrix
whoami | Para ver el nombre del dispositivo
man | Muestra el manual
exit | Sale del programa
nano | Para un editor de texto
cat (nombre del archivo) | Para ver el archivo de texto
ls | Trae los archivos adjuntos de la carpeta
su - | Para ponerse en modo administrador (root)
Mkdir | Crear carpeta
Cp texto1 texto2 | Para hacer copia entre textos
Mv nombre archivo, ruta donde se va a mover | Para mover un archivo de carpeta
Ls carpeta / grep archivo | Muestra lo de la carpeta y muestra una cadena string
Rm archivo ruta | Para borrar
Touch archivo | Crea archivo dentro de directorio
Rm directorio -R | Borra un directorio completo
Rm directorio -Rf | Borra un directorio completo de manera forzada
Rm -Rf  | NO USAR – daña el SO
Scp archivo usuario@direccionip:/ruta | Para transferir archivos entre hosts a través del protocolo SSH
sudo apt install openssh-server | Instalacion de servidor ssh
git clone URL | Para clonar 
curl -X GET -L ubicación | Envia solicitudes a páginas web
wc /var/log/syslog | Cuenta la cantidad de líneas
wc /var/log/syslog -w | Cuenta la cantidad de palabras
wc /var/log/syslog -m | Cuenta la cantidad de caracteres
head *ruta* | Primeras líneas de un archivo
head *ruta* -n 3  () | Va mostrando las primeras lineas pero poco a poco
tail | mostrar las últimas líneas de cualquier fichero
less o more | Muestra primeras 10 lineas
ls -1 / -R | Imprime todas las carpetas
ls -1 / -R - more | Imprime las carpetas lentamente)
History | Historial de todos los comandos ejecutados
History \ grep curl “palabra” | En el historial busca la palabra
Reboot | Reinia el equipo
Shutdown | Apaga el equipo
Pdfunite “nombres de los pdf a unir” / “nombre.pdf” ”nuevo nombre” | Une archivos PDF
Pdfseparate -f # pagina-1 #página nombre.pdf resultado_%d.pdf | Separa pdf
convert -verbose -density 300 -trim -quality 100 -flatten -sharpen 0x1.0 archivo.pdf salida.jpg | Convertir de pdf a jpg
Grep -r “palabra” “ruta” | Busca cadenas de texto
Find ruta –“name” “nombredelarchivo”  | Busca de archivos
Comando Docker | Uso
------------ | -------------
curso docker images | Para ver las imagenes con las que cuenta
curso docker pull ngnx |
curso docker ps -a | Para ver los estados de los contenedores
curso docker history nginx | Historial de capas
curso docker info | Muestra los drivers
curse uname -a | Para ver el kernel
~ docker network ls | Para ver las redes de Docker
~ sudo ifconfig docker0 | Para ver la interface Docker Cero
~ docker network create --driver (nombre de la red) | Crear un driver
~ sudo ifconfig -s | Para ver las interfaces
~sudo ifconfig (red) | Para ver los contenedores de una red
docker pull | Se trae del repositorio o registro que nosotros le digamos la imagen adecuada.
docker ps -a | Para ver los contenedores que estan en ejecucion y los que no
~ docker run -ti (imagen) |  "docker run" con las opciones "-t", que es para que nos asigne un terminal, y la "i", que es para que sea interactivo
~ docker run -ti --rm (imagen) | "docker run -ti", para que sea interactivo, y agregamos la opción "--rm", esto hará que cuando se termine de ejecutar el comando del contenedor automáticamente se borre del disco. 
~ docker run -ti --rm ubuntu bash = entry point | Para activar comandos Unix
~ docker rmi (imagen) | Para borrar imagenes
docker find ./ | Muestra ficheros
producer nginx docker built -t (imagen y version) (carpeta) | Crear un imagenes
producer curso vim Dockerfile | Hacer variables
