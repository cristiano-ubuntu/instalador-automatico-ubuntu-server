
#### Scripts Python para editar uma ISO Ubuntu Server 22.04 para adicionar capacidade de instalação automatizada de servidor

Existem duas opções de script. O script [cria_iso_ubuntu_autoinstall.py] faz tudo em uma única etapa e produz uma novo ISO do instalador que é usado sozinho. Os outros dois scripts separam as etapas em um editor para o ISO do instalador que apenas altera o [ grub.cfg ] suficiente para que ele procure o outro ISO se ele estiver anexado e tiver o rótulo do volume CIDATA. O terceiro script cria um ISO com rótulo de volume CIDATA que contém os arquivos [cloud-init] adequados necessários para instalação automática.
