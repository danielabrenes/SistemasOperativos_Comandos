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
root | Para ponerse en modo administrador
nano | Para crear un archivo nano
cat (nombre del archivo) | Para ver el archivo de texto
Mkdir | Crear carpeta
Cp texto1 texto2 | Para hacer copia entre textos
Mv nombre archivo, ruta donde se va a mover | Para mover un archivo de carpeta
Ls carpeta (|) grep archivo | Muestra lo de la carpeta y muestra una cadena string
Rm archivo ruta | Para borrar
Touch archivo | Crea archivo dentro de directorio
Rm directorio -R | Borra un directorio completo
Rm directorio -Rf | Borra un directorio completo de manera forzada
Rm -Rf  | NO USAR – daña el SO
Scp archivo usuario@direccionip:/ruta | 
sudo apt install openssh-server | Instalacion de servidor ssh
git clone URL | Para clonar 
curl -X GET -L ubicación | Envia solicitudes a páginas web
GmailApp.sendEmail(‘correo’, ‘asunto’, ‘data.toString()) | Envia correos
wc /var/log/syslog | Cuenta la cantidad de líneas
wc /var/log/syslog -w | Cuenta la cantidad de palabras
wc /var/log/syslog -m | Cuenta la cantidad de caracteres
head *ruta* | Primeras líneas de un archivo)
head *ruta* -n 3  () | 
tail
less o more | Muestra primeras 10 lineas
cat | Todo el contenido de un archivo)
ls -1 / -R | Imprime todas las carpetas
ls -1 / -R (|) more | Imprime las carpetas lentamente)
History | Historial de todos los comandos ejecutados
History \ grep curl “palabra” | En el historial busca la palabra
Reboot | Reinia el equipo
Shutdown | Apaga el equipo
Pdfunite “nombres de los pdf a unir” / “nombre.pdf” ”nuevo nombre” | Une archivos PDF
Pdfseparate -f # pagina-1 #página nombre.pdf resultado_%d.pdf | Separa pdf
convert -verbose -density 300 -trim -quality 100 -flatten -sharpen 0x1.0 archivo.pdf salida.jpg | Convertir de pdf a jpg
Grep -r “palabra” “ruta” | Busca cadenas de texto
Find ruta –“name” “nombredelarchivo”  | Busca de archivos
