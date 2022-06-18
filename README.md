# TCP-IPconnect2DT

## INTRODUCCIÓN
Proyecto llevado a cabo por el I3MSC para preparar y facilitar el desarrollo del segundo curso de Gemelos Digitales de la UMA.

## CONTENIDO
Este repositorio se divide en 3 carpetas:

- **Documentación**: Contiene una memoria que explica en profundidad el proyecto. Recomendamos su lectura para una mayor comprensión del contenido.
- **Modelos**: Contiene los modelos de Visual Components llevados a cabo: layouts similares a la instalación física situada en el laboratorio de trabajo, los modelos de herramienta conectados a los robots reales y ejemplos de prueba de los programas desarrollados.
- **src**: Contiene los códigos necesarios para poder usar los programas desarrollados.

## PROGRAMAS DESARROLLADOS
El principal interés de este repositorio reside en los dos programas desarrollados, encargados de interconectar el software Visual Components y los robots manipuladores IRB 120 de ABB (programados en RobotStudio) mediante protocolo TCP/IP. Estos son:
- **Reproducción de la posición del robot en el Gemelo Digital (RobotStudio a Visual Components)**. Este programa es capaz de establecer una conexión cliente-servidor entre el robot y Visual Components, y enviar a tiempo real las posiciones articulares del robot al programa, el cuál se encarga de adaptar los modelos virtuales de los robots a estas. También es capaz de replicar el comportamiento de la herramienta. 

Video de demostración: 

[![Alt text](https://img.youtube.com/vi/TyIYKzCEILI/0.jpg)](https://www.youtube.com/watch?v=TyIYKzCEILI)

- **Control del robot mediante rutinas programas en Visual Components (Visual Components a RobotStudio)**. Este programa se encarga de establecer una conexión cliente-servidor entre el robot y Visual Components (igual que el anterior) y de enviar, de manera ordenada y con pausas para confirmación, instrucciones de movimiento o de control de la herramienta al robot real desde Visual Components. 

Video de demostración: 

[![Alt text](https://img.youtube.com/vi/LFA_1vL7EIA/0.jpg)](https://www.youtube.com/watch?v=LFA_1vL7EIA)
