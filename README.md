# hgr-dre

Aplicación dockerizada HGR Sigala.

Es una aplicación utilizada para el control del aula. Contiene dos aplicaciones, un cliente utilizado en los pc's del alumnado y un servidor al que se conectan los clientes. 

Compatible con Ubuntu 20.04 Focal, Linux Mint (20, 20.1, 20.2) y EducaAndOS, sistema basado en Ubuntu Focal 20.04.

Gracias al equipo del CGA de la Consejería de la Junta de Andalucía.

![](https://github.com/aosucas499/hgr-dre/raw/main/testing/hgr-info.jpg)

## USO

+ Encontrará los archivos compartidos entre el servidor y el cliente en la carpeta **HGR** ubicada en su carpeta de usuario del sistema.

+ Solo podrá compartir los archivos alojados en la carpeta **HGR** entre el servidor y el cliente. Si necesita compartir algún archivo alojado en otra carpeta, haga una copia o muévalo a dicha carpeta.

+ Manual del programa original, [aquí](http://www.juntadeandalucia.es/educacion/cga/portal/wp-content/uploads/2017/03/Manual_de-_Usuario_HGR.pdf).

## FUNCIONA

### SERVIDOR
+ Listado de clientes conectados
+ Compartición de archivos con los clientes (los archivos tienen que estar en la carpeta HGR)
+ Recibir demostración de la pantalla del servidor en el cliente.
+ Ejecutar aplicación en cliente
+ Enviar archivos multimedia al cliente
+ Enviar mensajes al cliente
+ Bloquear clientes
+ Bloquear Internet en los clientes
+ Apagar pc del cliente
+ Reiniciar pc del cliente
+ Visualizar la pantalla del cliente desde el servidor.
+ Tomar control de la pantalla del cliente desde el servidor.
+ Realizar capturas de pantalla del cliente desde el servidor
### CLIENTE
+ Enviar archivos al servidor (los archivos tienen que estar en la carpeta HGR)
+ Solicitar ayuda al servidor

## NO FUNCIONA

### SERVIDOR
+ Documento colaborativo

### CLIENTE (estas funciones se podrían implementar pero solo engordaría el tamaño de la imagen y no las veo necesarias)
+ Abrir libreoffice writer desde el servidor
+ Abrir navegador de Internet desde el servidor



## INSTALL

    cd ~
    
    sudo apt-get update-y
    
    sudo apt-get install git -y

    git clone https://github.com/aosucas499/hgr-dre.git

    cd hgr-dre
    
    chmod +x install-hgr-dre
    
    ./install-hgr-dre
    
    sudo reboot (Reboot the system - Reiniciar el sistema)




Si este proyecto te ayuda, puedes invitarme a un café.


If this project helps you, you can give me a cup of coffee.


[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?business=FUMT27MVTRTHJ&no_recurring=0&item_name=Proyectos+TIC+Andaluc%C3%ADa&currency_code=EUR)

