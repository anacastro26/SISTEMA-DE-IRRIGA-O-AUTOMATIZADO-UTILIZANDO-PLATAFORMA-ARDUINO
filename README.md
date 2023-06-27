# SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO
# Introdução

Um sistema de irrigação automatizado torna o processo de irrigação mais eficiente, econômico e preciso. Com o uso da plataforma Arduino, é possível criar um sistema de irrigação automatizado que pode ser controlado e monitorado remotamente.

O sistema de irrigação automatizado utilizando plataforma Arduino é composto por sensores, válvulas e bombas. Os sensores são responsáveis por detectar a umidade do solo e enviar essa informação para a plataforma Arduino. Com base nessa informação, o Arduino determina se é necessário irrigar ou não. Se for necessário irrigar, o Arduino aciona as válvulas para abrir e permitir a passagem da água, e também aciona a bomba para fazer a água fluir.

Além disso, o sistema de irrigação automatizado utilizando plataforma Arduino é econômico e sustentável, pois evita desperdícios de água e energia. Com a utilização de sensores, é possível garantir que a irrigação seja feita somente quando necessário, evitando o excesso de água e reduzindo o consumo de energia.

## Definição do problema

O ritmo de vida atual está cada vez mais corrido devido a diversos fatores, como trabalho, família, lazer e trânsito caótico, resultando em perda de tempo para deslocamentos. Isso acaba impedindo as pessoas de realizarem atividades simples, como cuidar de uma planta.

Ter uma planta em casa vai além da beleza das flores. Algumas espécies estimulam a liberação de adrenalina em nosso corpo, aumentando os níveis de energia e oxigenação, além de nos ajudarem a relaxar. Elas também umidificam o ar durante a transpiração, tornando o ambiente mais agradável.

As plantas trazem inúmeros benefícios para a vida humana, no entanto, os sistemas de irrigação disponíveis no mercado nem sempre atendem às necessidades dos consumidores, já que diferentes plantas requerem quantidades diferentes de água. Distribuir a mesma quantidade de água para plantas distintas pode resultar na perda das plantas e no desperdício de água, gerando um novo problema.

Diante desse desafio, este projeto busca pesquisar sistemas de irrigação automatizados, com foco na plataforma Arduino, a fim de desenvolver um protótipo de sistema de irrigação preciso, de baixo custo e adequado para pequenos agricultores e jardins.

## Arquitetura da aplicação

Para o desenvolvimento deste protótipo de sistema de irrigação automatizado
com Arduino precisou-se dos seguintes itens:

- IDE do Arduino;
- Placa Arduino UNO;
- Módulo Sensor Medidor Capacitivo de Umidade do Solo;
- Protoboard;
- Relé;
- Bomba d’água submersa;
- Jumpers;

## Simulação do desenvolvimento

- Diagrama de Caso e Uso
    
   
    ![Diagrama de Caso e Uso](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/4cf52286-c95e-475d-b1e7-8c890746ee2e)

- Conexões
    
    A conexão do sistema realizada da seguinte maneira:
    os sensores de umidade do solo são conectados aos pinos analógicos da placa Arduino. Esses sensores serão responsáveis por medir a umidade do solo e fornecer os dados para o controle do sistema de irrigação.
    
    A bomba d'água é conectada aos pinos digitais da placa Arduino, através de relés. O relé é utilizados para controlar o acionamento a bomba, ligando-a ou desligando-a conforme a necessidade de irrigação.
    
    
    ![Imagem do WhatsApp de 2023-06-25 à(s) 16 29 0 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/1db9139a-b96e-43fa-90bd-ed74dca0895a)
![Imagem do WhatsApp de 2023-06-25 à(s) 17 20 11 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/080ea70e-f34b-47b3-a6e7-e440d201b2eb)
![Imagem do WhatsApp de 2023-06-25 à(s) 16 29 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/3aea4254-b351-45ac-a181-895efe29a0d3)
![Imagem do WhatsApp de 2023-06-25 à(s) 16 29 02 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/b1c4de8b-fe02-4a1d-91b6-46ce59480dcd)


- Terrário
    
    O terrário foi construído utilizando tábuas com formas geométricas, proporcionando uma estrutura na qual é possível inserir vidros. Essa configuração permite a entrada de luz solar e proporciona uma visão clara do interior.
    
![Imagem do WhatsApp de 2023-06-25 à(s) 16 29 01 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/0b3d81b3-f821-4f92-94bf-f52eda48065a)
![Imagem do WhatsApp de 2023-06-25 à(s) 16 29 03 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/277e30d0-c0a8-443f-b1fe-49e2aaf0cb4d)
![Imagem do WhatsApp de 2023-06-25 à(s) 16 28 59 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/1d25a5a0-71df-40f2-ae6c-e7380a5e2987)
![Imagem do WhatsApp de 2023-06-25 à(s) 16 29 00 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/ad949867-9490-4715-8616-bf9d165495f9)


## Alterações, testes, validação

Devido a alguns problemas técnicos, nossa bomba d'água submersa apresentou defeitos e, infelizmente, não temos tempo suficiente para encontrar uma substituta. Diante dessa situação, surgiu a ideia de utilizar uma bomba de limpador de para-brisa de 12 volts para fornecer água ao nosso canteiro.


![44457 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/f86d545f-ee3d-4a3f-ac7d-a0ff109d2083)
![157 (1)](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/3b23fffa-6e88-4661-ba9e-288b429e5c48)

Após realizarmos testes com a bomba de para-brisa, constatamos que sua pressão era muito forte, resultando em um excesso de água e o risco de molhar pessoas próximas. Diante dessa situação, surgiu a ideia de utilizar um rolo removedor de pelos e sujeiras de roupas.

O rolo foi cortado ao meio e envolvido com fita isolante, criando assim uma estrutura similar a um chuveiro. Fizemos alguns furos na base do rolo para permitir que a água passasse apenas por esses orifícios, evitando que fosse jogada em jatos altos.

Dessa forma, embora a pressão da água não tenha diminuído, essa solução ajudou a controlar o fluxo, permitindo que a água saísse de forma mais controlada e evitando respingos indesejados.





https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/1683517f-9b56-49c3-a4cf-a11587a95f38



![Imagem do WhatsApp de 2023-06-25 à(s) 16 29 05](https://github.com/anacastro26/SISTEMA-DE-IRRIGA-O-AUTOMATIZADO-UTILIZANDO-PLATAFORMA-ARDUINO/assets/79887747/af05583f-be0a-45ce-aaf8-d8c64c74dffc)


## Execução do código

A execução do código foi realizada por meio da IDE Arduino, e o código foi transferido (upload) para a placa Arduino.

```arduino
#define rele 3
#define sensor 2

bool irrigar = false;
void setup()
{
pinMode(rele, OUTPUT);
pinMode(sensor, INPUT);

digitalWrite( rele, HIGH);
}

void loop()
{
irrigar = digitalRead(sensor);

if(irrigar)
{
digitalWrite(rele, LOW);
}
else
{
digitalWrite(rele, HIGH);
}

delay(500);
}
```

## Conclusão

O sistema de irrigação baseado na plataforma Arduino oferece uma solução automatizada e eficiente para regar as plantas, criando um ambiente propício ao seu crescimento saudável e permitindo o monitoramento da umidade do solo.

Para aprimorar ainda mais o sistema, é essencial considerar projetos futuros que visem aumentar a precisão e a eficiência do processo de irrigação. Realizar uma análise mais aprofundada do solo e das necessidades específicas das plantas pode resultar em um desempenho ainda mais satisfatório. Ao incorporar esses dados em um sistema inteligente, seria possível realizar ajustes mais complexos e personalizados.

A implementação de um sistema de monitoramento online em tempo real traria benefícios significativos. Isso permitiria acompanhar os dados de umidade do solo, status da irrigação e outras informações relevantes de forma contínua. O desenvolvimento de um aplicativo dedicado simplificaria a experiência do usuário, tornando mais fácil compreender e interpretar os dados coletados.

Essas melhorias contribuiriam para otimizar o uso da água e melhorar a eficiência da irrigação, resultando em um crescimento saudável das plantas. Além disso, proporcionariam uma gestão mais sustentável dos recursos hídricos, promovendo a conservação e o uso responsável da água.
