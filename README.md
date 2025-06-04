# Controle de bomba d'água com MQTT
Repositório criado para versionamento da atividade sobre comunicação MQTT

## Descrição geral do Funcionamento do programa 
O LED azul representa o acionamento de uma bomba d’água, que pode ser acionada à distância através de um  aplicativo que utiliza o protocolo de comunicação MQTT, a temperatura interna do equipamento é medida com o sensor de temperatura da raspberry pi pico 2, sendo mostrado no aplicativo a tendência. 

## Descrição detalhada do Funcionamento do programa  na BitDogLab

**LED RGB→** LED azul simula acionamento da bomba d’água

**ADC→** adc utilizado para leitura do sensor de temperatura interna da raspberry pi pico w


## Compilação e Execução
1. Certifique-se de que o SDK do Raspberry Pi Pico está configurado no seu ambiente.
2. Compile o programa utilizando a extensão **Raspberry Pi Pico Project** no VS Code:
   - Abra o projeto no VS Code, na pasta PRPJETO_MULTIRAREFAS tem os arquivos necessários para importar 
   o projeto com a extensão **Raspberry Pi Pico Project**.
   - Vá até a extensão do **Raspberry pi pico project** e após importar (escolher sdk de sua escolha) os projetos  clique em **Compile Project**.
3. Coloque a placa em modo BOOTSEL e copie o arquivo `mqtt_client.uf2`  que está na pasta build, para a BitDogLab conectado via USB.

**OBS: Devem importar o projeto para gerar a pasta build, pois a mesma não foi inserida no repositório**

## Colaboradores
- [PauloCesar53 - Paulo César de Jesus Di Lauro ] (https://github.com/PauloCesar53)
