+++
categories = []
date = "2016-02-24T16:41:28-03:00"
description = ""
keywords = []
title = "Install Gogs on Ubuntu"
tags  = [ "Development", "Go", "profiling" ]
topics = [ "Development", "Go" ]

+++


Nesse screencast mostro como é simples instalar o Gogs no Ubuntu 14.04 64Bits.

{{< figure src="/media/install_gogs_ubuntu.jpg" >}}

Para quem não conhece o Gogs, ele é uma aplicação escrito totalmente em Golang (GO) que cria um sistema Web parecido com Github ou Gitlab, como é feito em Golang é muito simples de Instalar e Configurar.
Você só vai precisar de um banco de dados, SQLITE3 ou Mysql e o git-core e um Servidor Real ou Virtual com Linux, ele é um Github privado para sua empresa ou projeto.
Em poucos passos a aplicação fica no ar.


{{< youtube DFNifgEHOzk >}}



**Instalando o Gogs pelo Terminal**

{{< codecaption lang="bash" title="Script Install on Debian, Ubuntu, OpenSUSE 64Bits !!!" >}}

## Run as root
sudo su
wget https://gist.github.com/jniltinho/280573e10206e31ab1c7/raw/02aa85f263441076da6c5dacd1b1ef4b2937ee59/install_gogs_ubuntu.sh

chmod +x install_gogs_ubuntu.sh
./install_gogs_ubuntu.sh

{{< /codecaption >}}


**Mais detalhes acesse o script de instalação no gist.**

- https://gist.github.com/jniltinho/280573e10206e31ab1c7


**Mais Links**

- http://gogs.io/
- https://github.com/gogits/gogs/
- http://obahua.com/

