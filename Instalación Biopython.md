# Instalación Biophyton para Linux
## Paso 1
Abrimos una nueva terminal
## Paso 2
Escribimos “python” en la terminal para vericar que no este instalado:

`$ python`
## Paso 3
Las versiones recientes de Python comenzando con Python 2.7.9 y Python 3.4, incluyen la herramienta de administración de paquetes Python pip, que permite una fácil instalación desde la línea de comandos. Colocamos el comando en la consola:
 
 `$ pip install biopython`

Una ves colocado el comando comenzara la instalacion.
## Paso 4
Para actualizar una versión anterior de Biopython, intentamos con el comando:
 
 `$ pip install biopython --upgrade`
 # Instalación de Git
##  Paso 1
En el sistema de control ingresamos el siguiente comando:
 `$ sudo apt install git`
## Paso 2
Cada usuario de git primero debe presentarse a git, ejecutando estos dos comandos:
 `$ git config --global user.email "you@example.com"`
`$ git config --global user.name "Tu nombre"`

# Instalación Gedit
## Paso 1
Abrimos una nueva terminal
## Paso 2
Desde la consola escribimos:
 
 `$ sudo apt-get install gedit`

## Paso 3
Para abrir un archivo específico:
 
 `$ nombre de archivo gedit`

## Paso 4
Para abrir mas de un archivo.
 
 `$ gedit archivo1 archivo2`
 # Instalacion de Seqmagick
## Paso 1
Abir la terminal y colocar el comando:

`pip install seqmagick`

**Tenga en cuenta que a partir de la versión 0.7.0, este paquete requiere Python 3.4+. Si desea utilizar la versión más reciente compatible con Python 2.7:.**

Al finalizar el proceso de instalacion en algunos casos puede marcar error enalgunos paquetes en este caso se recomienda instalarlos por separados con el siguiente comando:

`sudo apt install "nombre del paquete".`

# Instalacion de Bioperl
## Paso 1
Para instalar bioperl en Ubuntu ejecutar los siguientes comandos::

`$ sudo apt-get update`

Te pedira tu contraseña dasela:

## Paso 2

Se ejecuta el siguiente comando:

`sudo apt-get install bioperl`
## Paso 3
Se instala el modulo Bio::Seq con el siguiente comando:

`cpan BIo::Seq`

# Instalación de FASTQC

## Paso 1
Colocar el siguiente comando.
`$ sudo apt-get update`
## Paso 2
Para la instalación se inicia colocando el siguiente comando en la consola:

`$ sudo apt-get install fastqc`


# Instalación de CUTADAPT
 ### Instalación con conda
## Paso 1
 En la consola se coloca el comando:

` $ conda install -c bioconda cutadapt`

#  Instalación de TrimGalore
## Paso 1
Es necesario tener ya instalados los paquetes anteriores:
* Verifique que cutadapt esté instalado
 ` $ cutadapt --version`

* Verifique que FastQC está instalado
 ` $ fastqc -v`

## Paso 2
Instalar Trim Galore
` $ curl -fsSL https://github.com/FelixKrueger/TrimGalore/archive/0.6.0.tar.gz -o trim_galore.tar.gz tar xvzf trim_galore.tar.gz`

Posteriormente para saber que ya lo tenemos instalado corremos el paquete con el siguiente comando:

` $TrimGalore-0.6.0/trim_galore`


# Instalación de SPAdes
## Paso 1
Se instala con el comando:
` $ sudo apt install spades`




# Instalación de velvet
##Paso 2
 Se utilixa nuevamente el comando:

` $ sudo apt-get install velvet`

# Instalación de c-shell
## Paso 1
 Colocar el comando:

` $ sudo apt-get install tcsh`

Para estar seguro que la Instalación se realizó correctamente se usa el comando:

`$ tcsh`


# Instalación de MUMmer
 ## Paso 1

 Es necesario descargar en archivo tar [][27b92a46]

  [27b92a46]: https://sourceforge.net/projects/mummer/files/ "De la siguiente pagina"

  ## Paso 2

  Descomprimir el archivo con el comando

` $ tar -xvzf MUMmer3.0.tar.gz `

