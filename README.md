# Ponderada de Programação – LED Interno (Arduino UNO)

## Introdução
Nesta atividade, o objetivo foi compreender o funcionamento básico do Arduino UNO e aplicar conceitos de lógica de programação para controlar um LED.
A proposta consistia em fazer o LED acender e apagar em intervalos definidos, simulando o efeito de piscar.
Posteriormente, o mesmo código foi adaptado para um LED externo, conectado em um protoboard e simulado no Tinkercad.


## Parte 1 – Blink LED Interno

### Descrição
O Arduino UNO possui um LED interno conectado ao pino digital 13.
Nesta primeira etapa, o LED foi programado para acender e apagar a cada 500 milissegundos, criando o efeito de piscar continuamente.

### Materiais Utilizados
- Arduino UNO
- Cabo USB
- Arduino IDE
- Resistores
- LEDS

### Código Utilizado

<p align="center">
  <img src="assets\imagens\CodigoPiscaPisca.png" alt="Foto LED aceso" width="400"/>
</p>


--- 
### Funcionamento
O código configura o pino 13 como saída e alterna seu estado entre ligado e desligado em intervalos de 0,5 segundo. O comando digitalWrite(13, HIGH) envia energia ao pino (ligando o LED), enquanto digitalWrite(13, LOW) corta a energia (apagando o LED). Assim, o LED pisca continuamente enquanto o programa estiver em execução.

---

### Evidências
Imagem do Arduino UNO com o LED aceso

<p align="center">
  <img src="assets\imagens\1LED.jpeg" alt="Foto LED aceso" width="400"/>
</p>

Vídeo Demonstração do LED piscando na placa: Assista ao vídeo

[Vídeo no YouTube](https://youtu.be/lkEv3r3x7mQ)

### Parte 2 – Simulação de Blink Externo no Tinkercad

Após compreender o funcionamento do LED interno, foi realizada uma simulação no Tinkercad utilizando um LED externo conectado em um protoboard. O objetivo foi replicar o mesmo comportamento de piscar, aplicando conceitos de ligação elétrica e uso de resistores.

### Materiais Utilizados
- Arduino UNO
- Protoboard
- LED
- Resistor de 220Ω
- Jumpers (fios de conexão)
- Tinkercad (para simulação)

### Código Utilizado

O código utilizado foi o mesmo do anterior

<p align="center">
  <img src="assets\imagens\CodigoPiscaPisca.png" alt="Foto LED aceso" width="400"/>
</p>

### Funcionamento
O funcionamento é idêntico ao da parte anterior, mas agora na plataforma.

### Evidências
Imagens Print da montagem no Tinkercad

<p align="center">
  <img src="assets\imagens\Tinkercad.png" alt="Foto LED aceso" width="400"/>
</p>

Link do projeto público no Tinkercad: https://www.tinkercad.com/things/6mwpCxE03LI-spectacular-jaban/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=StvxDIiSujk7066v8p8LJ7qs1ncMapeZj81u2ZNm7u8

---

### Resultados Obtidos
A atividade permitiu compreender de forma prática como o Arduino controla dispositivos eletrônicos simples, como LEDs. Foram aprendidos os conceitos de:

Definição de pinos como entrada e saída (pinMode())

Envio de sinais digitais (digitalWrite())

Controle de tempo com delay()

Importância de resistores em circuitos elétricos

Além disso, a transição do LED interno para o externo ajudou a reforçar os conceitos de montagem física e simulação.

--- 
### Indo além

Desafio de fazer mais de um LED acender

Imagem do Arduino UNO com mais de um LED  aceso

<p align="center">
  <img src="assets\imagens\3LEDS.png" alt="Foto LED aceso" width="400"/>
</p>

[Vídeo no YouTube](https://youtu.be/PqppheeiRQ0)

---

###  Conclusão
Com esta prática, foi possível aprender na prática como programar o Arduino e como controlar componentes eletrônicos simples. O teste com o LED interno mostrou o funcionamento básico da placa, e a simulação no Tinkercad ajudou a entender como montar circuitos corretamente. A atividade foi importante para desenvolver o raciocínio lógico e compreender melhor o funcionamento de sistemas embarcados.