ESTE PROJETO FOI BASEADO NO FORK DO GRUPO 64 CCR


Software e serviços online
OpenCV
Dlib
Python3



Problemática

O presente projeto trata sobre a utilização de visão computacional, processamento de imagem e sistemas embarcados.
O principal objetivo foi desenvolver um algoritmo baseado em processamento de imagem e python para a detecção de
sonolência em motoristas. O projeto foi dividido em etapas para a compreensão de assuntos mais complexos, pois
torna-se fundamental o conhecimento em matemática, lógica de programação C/C++, Python, Dlib e OpenCV para o
seu desenvolvimento. Os resultados iniciais demonstraram uma acurácia de 85%, pois o sistema depende de boa
iluminação. Em horários noturnos, torna-se difícil a identificação dos olhos e consequentemente a análise do estado de
sonolência – para tal solução poderia ser usada uma câmera infravermelha e desta maneira validar o sistema em
turnos diferentes

This project deals with the use of computer vision, image processing and embedded systems.
The main objective was to develop an algorithm based on image processing and python for the detection of
drowsiness in drivers. The project was divided into stages to understand more complex issues, as
knowledge in mathematics, C/C++ programming logic, Python, Dlib and OpenCV for the
its development. The initial results showed an accuracy of 85%, as the system depends on good
lighting. At night, it becomes difficult to identify the eyes and, consequently, analyze the state of
drowsiness – for such a solution, an infrared camera could be used and in this way validate the system in
different shifts



Aplicação

Os motoristas de caminhão que transportam cargas e materiais pesados por longas distâncias durante o dia e a noite, muitas vezes sofrem de falta de sono. fadiga e sonolência são algumas das principais causas de acidentes graves em rodovias. As indústrias automobilísticas estão trabalhando em algumas tecnologias que possam detectar a sonolência e alertar o motorista sobre ela.



Neste projeto, vamos construir um sistema de detecção e alerta de sono para motoristas usando o módulo de câmera Raspberry Pi, OpenCV e Pi. O objetivo básico deste sistema é rastrear a condição facial do motorista e os movimentos dos olhos e se o motorista estiver se sentindo sonolento, o sistema irá disparar uma mensagem de aviso. Esta é a extensão do nosso aplicativo anterior de detecção de pontos de referência facial e reconhecimento de rosto.



Instalando OpenCV no Raspberry Pi




Antes de instalar o OpenCV e outras dependências, o Raspberry Pi precisa ser totalmente atualizado. Use os comandos abaixo para atualizar o Raspberry Pi para sua versão mais recente:




sudo apt-get update



Em seguida, use os seguintes comandos para instalar as dependências necessárias para instalar o OpenCV em seu Raspberry Pi.

sudo apt-get install libhdf5-dev -y 

sudo apt-get install libhdf5-serial-dev –y 

sudo apt-get install libatlas-base-dev –y 

sudo apt-get install libjasper-dev -y 

sudo apt-get install libqtgui4 –y

sudo apt-get install libqt4-test –y