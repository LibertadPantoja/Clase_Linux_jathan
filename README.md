# Clase_Linux_jathan
Apuntes de la clase de Debian: **Debian 9 stretch**


# Ambientes gráficos

## GNOME shell

Intefaz gráfica muy completa

### Tweak para costumizar: gnome-look.org

- En Tweak Se pueden obtener formas de ver los escritorios, se pueden modificar las áreas de trabajo, hacerse estáticas y determinar el número de ellas. 

En el menú **Máquina virtual** se pueden redirigir los dispositivos montados a la máquina virtual.

## Jeraquía de directorios en New Linux

	Todo para new Linux son archivos
  
  
  Super ususario debian es su
  
  ### En el directorio bin hay binarios escenciale spara correr comandos
  
  ### En boot todo lo relacionado al sector de arranque
  
  ```
  cd /
  ls -la boot/
  ```
  ### En dev
  
  Archivos del dispositivo
  
  ### En etc
  
 archivos host, configuración del sistema
 
 ### En home
 
 Se guardan los archivos de los usuarios (aquí s ecrean los directorios personales)
 
 ### En lib
 
 Están las bibliotecas. Prestas un recurso que es regresado.
 
 ### En media
 
 Puntos de montaje de cosas extraíbles que ya reconoce el sistema previamente (montado con sesión gráfica).
 
 ### En mnt
 
 Punto de montaje para sistemas de archivos temporalemnte montados
 
 ### En opt
 
 Paquetes adicionales que nostros instalamos
 
 ### En sbin
 
 Archivos especiales del sistema sóloe ejecutados por el superusuario. No existen para el suusario sin privilegios.
 
 ### En srv
 
  Ctrl - shift t nuevo tab en terminal
  
  ### En tmp
  
  Se guardan los qrchivos temporales mientras la sesión esté activa.
  
  ### En usr
  
  Aplicaciones y librerías para diferentes usuarios (who,whoami)
  
  #### En local
  
  Cosas particulares de cada usuario, no se usa mucho en Debian
  
  ### En var
  
  Archivos variables (paquetes instalados en debian). 
  
  ´´´
  ls -la /var/cache/apt/archives
  ´´´
  
  ### En root 
  
  Está el home del superusuario
  
  Ctrl -p y Ctrl -n ayuda a desplazarse en el historial
  
  Ctrl -a inicio de la orden en terminal
  
  Ctrl -e ir al finald e la lí
  nea
  less ver contenido de archivos
