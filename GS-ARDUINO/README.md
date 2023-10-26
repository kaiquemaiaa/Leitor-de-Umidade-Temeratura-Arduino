# README GS-ARDUINO

Kaique Maia Reis Silva
Lucas Augusto Dutra Keller
Pedro Henrique Alves Guariente
David de Medeiros Pacheco Junior
Orlando Akio Morii Cardoso

# Leitor de Umidade e Temperatura com Arduino

Este projeto consiste em um leitor de umidade e temperatura desenvolvido com o Arduino. O objetivo é coletar dados em tempo real para medir a temperatura e a umidade do ambiente. O sistema utiliza sensores de temperatura e umidade conectados ao Arduino, exibindo as leituras em um display de LCD. Esse projeto pode ser útil em diversas aplicações, como monitoramento agrícola, controle de ambientes internos e sistemas de climatização.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Funcionamento
O sistema utiliza os seguintes componentes:

-Arduino Uno (ou qualquer outra placa compatível)

-Sensor de temperatura (ex: DHT11 ou DHT22)

-Sensor de umidade (ex: DHT11 ou DHT22)

-Display de LCD (16x2 caracteres)

-Resistores e cabos de conexão

-Os sensores de temperatura e umidade são conectados aos pinos do Arduino, e as leituras são realizadas por meio das portas analógicas. O display de LCD é utilizado para mostrar as informações de temperatura e umidade ao usuário.

O código do Arduino realiza as seguintes ações:

1.Configuração inicial: define os pinos do Arduino para conexão com os sensores e o display de LCD.


2.Inicialização do display: configura o display de LCD e exibe a mensagem inicial.


3.Loop principal

3.1-Realiza a leitura da temperatura e umidade dos sensores.

3.2-Exibe as leituras no display de LCD.

3.3Aguarda um intervalo de tempo entre as leituras

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Instruções de Uso
Para utilizar esse projeto, siga as instruções abaixo:

Monte o circuito de acordo com o esquema de conexões fornecido.
Conecte o Arduino ao computador.
Abra o arquivo do código-fonte no Arduino IDE.
Faça o upload do código para o Arduino.
O display de LCD começará a exibir as leituras de temperatura e umidade.

# Requisitos e Dependências
Para reproduzir esse projeto, você precisará dos seguintes itens:

Placa Arduino Uno (ou similar)
Sensor de temperatura e umidade (ex: DHT11 ou DHT22)
Display de LCD (16x2 caracteres)
Resistores e cabos de conexão
Além disso, é necessário ter o Arduino IDE instalado no computador para programar o Arduino.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Informações Adicionais

Certifique-se de fazer as conexões corretas dos sensores e do display de LCD de acordo com o esquema de ligações fornecido no código ou na documentação do projeto.

Caso esteja utilizando um sensor de temperatura e umidade diferente dos mencionados, verifique as especificações técnicas do sensor e ajuste o código conforme necessário.

Este projeto é apenas uma demonstração básica e pode ser aprimorado e adaptado para atender às suas necessidades específicas. Sinta-se à vontade para modificar o código ou adicionar funcionalidades extras.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Conclusão
O leitor de umidade e temperatura com Arduino é um projeto simples e útil para coletar dados em tempo real e exibi-los de forma fácil de entender. Ele pode ser aplicado em diversas áreas, como monitoramento agrícola, controle de climatização em ambientes internos e muito mais. Sinta-se à vontade para explorar e personalizar o projeto
