# hgr-dre

A script to download a docker image and run HGR applications from Guadalinex Edu Next (Ubuntu 16 Xenial 32bits).

Docker image based on:

tag hgr: HGR applications using Repositories from Guadalinex edu next (Ubuntu 16 Xenial 32bits)

tag sigala: Unstable Sigala applications using Repositories from Guadalinex edu 2013 (Ubuntu 12 Precise 64bits)


Gracias al equipo del CGA de la Consejería de la Junta de Andalucía.

http://www.juntadeandalucia.es/educacion/cga/portal/?p=7791

## USAGE

    cd ~
    
    sudo apt-get update-y
    
    sudo apt-get install git -y

    git clone https://github.com/aosucas499/hgr-dre.git

    cd hgr-dre
    
    chmod +x install-hgr-dre
    
    ./install-hgr-dre
    
    ./hgr-server (servidor HGR)
    
    ./hgr (cliente HGR)


## FILES description

### install-hgr-dre: Run first. It installs: 
1. Docker. 
2. Docker image (aosucas499/guadalinex:hgr)
3. File to boot at init session the app hgr client (it copies the file hgr.desktop to ~/.config/autostart)

### hgr.desktop
File necessary to boot the container when the session starts. It will be copied to folder "~/.config/autostart"

### hgr-server
It runs the the hgr-server application taking into account if the container was created or not.

### hgr
It runs the the docker container and the hgr-client application taking into account if the container was created or not.
>## IMPORTANT
 Don't move this script from the folder "~/hgr-dre/" or it won't work
 because the autoboot file finds the script in that folder

>## IMPORTANTE
 No muevas este script de la carpeta "~/hgr-dre" o no funcionará
 porque el archivo de autoarranque busca este script en esa carpeta
