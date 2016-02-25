+++
categories = []
date = "2016-02-25T15:16:32-03:00"
description = ""
keywords = []
title = "Quokka a CMS developed in Python"

+++



Hello everyone, today I will talk about an opensource cool Bruno Rocha project.
This is a design of a CMS developed with Python using non-relational database MongoDB.
At times I helped Bruno in the project, it was very little, but it's a help.
The project is developed with Micro Framework called Flask, the code is available on GitHub and has a demo for you to test.

In recent weeks the project received several improvements in the administrative part and several companies are using the Quokka CMS internally on its Intranet.

{{< figure src="/media/quokka1.png" >}}

Not to be alone in a post made a Quokka installation Screenshot Ubuntu 14.04 64Bit, following the script itself that helped create.

{{< youtube PVpTRbLKwLw >}}


First download the installation script with wget follow the command below:

```
wget https://raw.githubusercontent.com/quokkaproject/quokka/development/etc/scripts/setup-quokka-nginx-uwsgi-ubuntu.sh
```

Perform steps before that you need to become root by running the command **sudo su**. 

```
sudo su
bash setup-quokka-nginx-uwsgi-ubuntu.sh
```


**The script will ask two questions:**

First question – What is the site name that you will put in Quokka this server, you can put something like blog.seudominio.com.br, but know that this will be the Quokka name for you to access via browser, recommended to Environment Production on the Web or on an internal server in your Company.

Second Question – The Server IP, put the server Fixed IP
Wait a few minutes and the Quokka is in the air and you can now write your posts.

Recalling that the script does not do magic only install Nginx Web Server, MongoDB, uwsgi, Quokka CMS and everything you need for the project to run properly on the Server.

Recalling that the Nginx runs on port 80 if you have another web server running on port 80, make the changes to the Nginx **/etc/nginx/sites-available/quokka.conf** file if you already have the Nginx server is only me ask to inform how to add the Quokka this environment.

After installation you must access via browser, in my case I put the blog.linuxpro.com.br address, you will see a screen similar to this one. 

{{< figure src="/media/quokka_site.png" >}}

To edit or manage the Blog go to the URL http://quokka_url/ admin and use the login and the default password (login: admin@example.com password: admin), be sure to change.

**Links to Project:**

- https://github.com/quokkaproject/quokka
- http://demo.quokkaproject.org/
- http://quokkaproject.org/ 

I hope you enjoyed the post, leave your comments below
