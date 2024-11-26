# Decoders para a Linha DTL

Este repositório contém os decoders para os endpoints da linha DTL da KHOMP.

Os decoders são funções JS que facilitam a interpretação dos dados enviados pelos endpoints ao servidor de rede IoT.

ATENÇÃO: Para cada servidor de rede IoT e também, modelo de endpoint da linha DTL, possui um tipo diferente de decoder.
Cuide na hora de selecionar o decoder do seu dispositivo.

## 1. Decoders Disponíveis

### 1.1 Decoders para o servidor de rede ChirpStack versão 4:

#### DTL-200:
- [DTL-200 na versão padrão](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-200/DTL-200-Default-para-ChirpStackV4.txt)

- [DTL-200 com sonda de nível](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-200/DTL-200-sonda-de-nivel-para-ChirpStackV4.txt)


#### DTL-300:
- [DTL-300 com sensor de conta pulso](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-300/DTL-300-Contador-de-pulso-ChirpstackV4.txt)

- [DTL-300 com sensor de temperatura e umidade](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-300/DTL-300-Temperatura-e-Umidade-ChirpStackV4.txt)

- [DTL-300 com sensor de vazamento por corda](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-300/DTL-300-Vazamento-por-contato-ChirpstackV4.txt)

- [DTL-300 com sensores de contato seco](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-300/DTL-300-contato-seco-3x-ChirpStackV4.txt)

- [DTL-300 com sensor de temperatura](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-300/DTL-300-sonda-temperatura-ChirpStackV4.txt)

#### DTL-485:
- [DTL-485 na versão padrão](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-485/DTL-485-Padrao-ChirpStackV4.txt)

- [DTL-485 com TC](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-485/DTL-485-TC-ChirpStackV4.txt)

#### DTL-500:
- [DTL-500 na versão padrão](https://github.com/support-khomp/iot-decoders/blob/main/Endpoints-Linha-DTL/ChirpStack-V4/DTL-500/DTL-500-Padrao.txt)

### 1.2. Decoders para o servidor de rede TTN:

Pendente atualizações.

##  2. SUPORTE
Para mais informações sobre os endpoints da linha DTL, você pode entrar em contato com o suporte da KHOMP através do e-mail suporte.iot@khomp.com , pelo telefone +55 (48) 3722.2930 ou através do whatsapp pelo número +55 (48) 9 9982-5358.

Para obter informações adicionais dos dispositivos LoRa da KHOMP, [clique aqui.](https://www.khomp.com/iot/pt/tecnologia/lora/)