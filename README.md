# Integração do protocolo de segurança TLS para a comunicação de veículos aéreos não tripulados

Este projeto tem como objetivo implementar a integração do protocolo TLS (Transport Layer Security) na comunicação entre o ArduCopter e o MAVProxy. O protocolo TLS é amplamente utilizado para fornecer segurança em comunicações de rede, garantindo autenticidade, confidencialidade e integridade dos dados transmitidos.

## Resumo

Este projeto visa a integração bem-sucedida do TLS em um contexto específico. Ele inclui a implementação do protocolo tanto no lado do servidor quanto no lado do cliente, garantindo uma comunicação segura e criptografada entre os dois.

## Repositórios

O projeto está dividido em três repositórios no GitHub:

1. [Repositório do ArduPilot - ArduCopter](https://github.com/BeaComp/ardupilot-implementation-TLS): Este repositório contém a implementação do lado do servidor, incluindo todas as configurações e código relacionados ao servidor no arquivo [UARTDriver](https://github.com/BeaComp/ardupilot-implementation-TLS/blob/master/libraries/AP_HAL_SITL/UARTDriver.cpp)


2. [Repositório do Cliente](https://github.com/BeaComp/pymavlink-implementation-TLS): Aqui, você encontrará a implementação do lado do cliente, que se conecta ao servidor com segurança por meio do protocolo TLS no arquivo [mavutil.py](https://github.com/BeaComp/pymavlink-implementation-TLS/blob/master/mavutil.py)
