# hgr-dre

Aplicación dockerizada HGR Sigala.

Es una aplicación utilizada para el control del aula. Contiene dos aplicaciones, un cliente utilizado en los pc's del alumnado y un servidor al que se conectan los clientes. 

Gracias al equipo del CGA de la Consejería de la Junta de Andalucía.

![](https://github.com/aosucas499/hgr-dre/raw/main/testing/hgr-info.jpg)

## USO

+ Encontrará los archivos compartidos entre el servidor y el cliente en la carpeta **HGR** ubicada en su carpera de usuario del sistema.

+ Solo podrá compartir los archivos alojados en la carpeta **HGR** entre el servidor y el cliente. Si necesita compartir algún archivo alojado en otra carpeta, haga una copia o muévalo a dicha carpeta.

## FUNCIONA

### SERVIDOR
+ Listado de clientes conectados
+ Compartición de archivos con los clientes (los archivos tienen que estar en la carpeta HGR)
+ Recibir demostración de la pantalla del servidor en el cliente.
+ Ejecutar aplicación en cliente
+ Enviar archivos multimedia al cliente
+ Enviar mensajes al cliente
+ Apagar pc del cliente
+ Reiniciar pc del cliente
### CLIENTE
+ Enviar archivos al servidor (los archivos tienen que estar en la carpeta HGR)
+ Solicitar ayuda al servidor

## NO FUNCIONA

### SERVIDOR
+ Documento colaborativo
+ Bloquear clientes
+ Bloquear Internet en los clientes
### CLIENTE
+ Visualizar la pantalla del cliente desde el servidor.
+ Tomar control de la pantalla del cliente desde el servidor.
+ Abrir libreoffice writer desde el servidor
+ Abrir navegador de Internet desde el servidor 
+ Realizar capturas de pantalla desde el servidor

**Algunas de las funciones que no estan disponibles** parece que son funciones del servidor pero son debido a dockerizar el cliente, el servidor no encuentra en el sistema del cliente esas aplicaciones o funciones. Estas funciones funcionarán si el servidor se instala en educaAndOS plus, Ubuntu o Linux Mint desde este proyecto y el cliente es el original instalado en Guadalinex Edu, Next o [Minino TDE](https://github.com/aosucas499/minino-TDE)


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


If this project helps you,  you can give me a cup of coffee .


[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?business=FUMT27MVTRTHJ&no_recurring=0&item_name=Proyectos+TIC+Andaluc%C3%ADa&currency_code=EUR)

