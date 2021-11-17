# Concepção do Projeto
Acesso rápido:
* [Introdução](https://github.com/otavio-sf/PI2_2021.2/blob/main/README.md)
* [Design/Projeto](https://github.com/otavio-sf/PI2_2021.2/blob/main/design.md)
* [Implementação](https://github.com/otavio-sf/PI2_2021.2/blob/main/implementacao.md)
* [Operação](https://github.com/otavio-sf/PI2_2021.2/blob/main/operacao.md)

  O projeto tem como objetivo a implementação do uso da Domótica em residências, para demonstrar as facilidades, comodidades e segurança que o uso dessa tecnologia pode nos fornecer durante o dia a dia. Para apresentar essa implementação, será utilizada uma maquete de uma residência com diversos equipamentos eletrônicos, funcionando em conjunto para obtermos as seguintes funções:
  
  * Acionamento de luzes do ambiente através de um monitoramento de presença;
  * Detecção de vazamento de gás e/ou fumaça, acionando a abertura das janelas, soando um alarme específico e acendendo luzes indicando a saída;
  * Monitoramento da temperatura e umidade do ambiente, fazendo o acionamento do condicionador de ar;
  * Monitoramento do nível de chuva, informando o usuário sobre periculosidade ou caso tenha deixado as roupas na rua, fechamento de janelas e em caso de períodos de seca, acionamento da irrigação do jardim;
  * Monitoramento de presença quando o usuário está ausente, com acionamento de alarme e envio de informações para o usuário;
  * Controle de iluminação externa automatizada de acordo com a luminosidade do dia;
  * Abertura automatizada de cortinas de acordo com a luminozidade externa do dia e acionamento de despertador.
  * Acionamento de funções por aproximação, como descarga e torneiras.


## Lista de componentes a serem utilizados:

   - Placa MEGA 2560 R3 + Fonte + Cabo USB para Arduino;
   - Sensor de Umidade e Temperatura DHT11;
   - Sensor de presença e movimento PIR;
   - Sensor de gás MQ-2 inflamável e fumaça;
   - Micro Servo SG92R 9g TowerPro;
   - Módulo Sensor de Umidade/Nível Água Chuva;
   - Módulo Relé 5 V e um Canal;
   - Sensor ultrasônico HC-SR04;
   - Módulo Matriz de LED 8×8 com MAX7219;
   - _Buzzer_ passivo;
   - _Display_ LCD 16×2 I2C _Backlight_ Azul.


Imagem ilustrativa dos equipamentos eletrônicosa a serem utilizados:

![Arduino e sensores](https://www.usinainfo.com.br/img/cms/fotos-categorias/sensores-para-arduino-diversos-modelos.jpg)
