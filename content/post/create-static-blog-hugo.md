+++
categories = [ "Golang", "Blog" ]
date = "2016-02-28T11:42:58-03:00"
description = ""
keywords = [ "Development", "Go", "Blog", "Linux" ]
tags  = [ "Development", "Go", "Blog", "Linux" ]
topics = [ "Development", "Go", "Blog", "Linux" ]
title = "Create static Blog Hugo"

+++


{{< figure src="/media/create-static-blog-hugo_00.png" >}}

**Sobre o Hugo.**

Hugo é um gerador de site estático escrito em Go. Ele é otimizado para velocidade, facilidade de uso e configurabilidade. Hugo tem um diretório com conteúdo e modelos e torna-los em um site HTML completo.

Hugo faz uso de arquivos de remarcação com a matéria frente para os dados de meta.
Escrito em golang para a velocidade, Hugo é significativamente mais rápido do que a maioria dos outros geradores de site estático.

Um site típico de tamanho moderado pode ser processado em uma fração de segundo. Uma boa regra de ouro é que Hugo leva cerca de 1 milissegundo para cada parte do conteúdo. É tão rápido que vai tornar o local em menos tempo do que leva para mudar para o seu navegador e recarregar.

Hugo é feito para ser muito flexível. Definir seus próprios tipos de conteúdo. Defina seus próprios índices. Construir seus próprios modelos, códigos de acesso e muito mais. Ele é escrito para funcionar bem com qualquer tipo de site, incluindo blogs, tombos e docs.

**Instalando Hugo.**

Hugo é escrito em golang com suporte para Windows, Linux, FreeBSD e OSX.

A versão mais recente pode ser encontrada em [versões hugo](https://github.com/spf13/hugo/releases). Atualmente, construir para Windows, Linux, FreeBSD e OS X para x64 e i386 arquiteturas.

A instalação é muito fácil. Basta baixar a versão adequada para sua plataforma de [versões hugo](https://github.com/spf13/hugo/releases). Uma vez baixado pode ser executado a partir de qualquer lugar. Você não precisa instalá-lo em um local global. Isso funciona bem para hosts compartilhados e outros sistemas em que você não tem uma conta privilegiada.
Idealmente, você deve instalá-lo em algum lugar em seu caminho para o uso fácil. **/usr/local/bin** é o local mais provável.


Para criar um novo post com Hugo e muito simples, execute os comandos abaixo.

```bash
## Create new post on Hugo
hugo new post/first.md
```

Depois você precisa editar o arquivo que está na pasta **content/post/create-static-blog-hugo.md**

Se você tem um blog e deseja migrar para o Hugo veja esse [Link Migration Tools](https://gohugo.io/tools/#migration-tools)