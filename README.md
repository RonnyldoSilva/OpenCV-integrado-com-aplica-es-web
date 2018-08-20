# OpenCV integrado com Aplicações Web

## Objetivo

Desenvolver soluções de visão computacional integrada à dispositivos móveis e aplicações web. Durante este minicurso, iremos desenvolver uma aplicação de filtros, que será transformada em uma aplicação mobile.

## Ferramentas que iremos utilizar

* OpenCV (biblioteca open-source de visão computacional em C++)
* Boost (conjunto de bibliotecas em C++ que provê diversas funcionalidades, dentre elas a possibilidade de criar um servidor TCP/IP)
* NodeJS (plataforma que permite criar servidores HTTP em JavaScript)
* AngularJS (framework que facilita o desenvolvimento de aplicações web do lado do cliente)
* Ionic (framework que permite exportar aplicações web do lado do cliente em aplicações mobile nativas) 

### Instalando o OpenCV

```shell
sudo apt-get install build-essential cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev
git clone https://github.com/Itseez/opencv.git
mkdir opencv/release
cd opencv/releasecmake ..
make –j8 && sudo make install
```
