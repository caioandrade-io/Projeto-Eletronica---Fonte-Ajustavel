# Projeto Eletrônica Computação - Fonte Ajustável



## Componentes
| Quantidade    | Componentes  | Preço |
|------------|------------------|-------------|
| 2x   | Resistor 4.3K  | R$0,11 (unidade) |
| 2x  | Resistor 1K| R$0,07 (unidade) |
| 1x   | Resistor 100(5 W)     | R$1,98 |
| 1x   | Transistor 2N2222A     | R$2,60|
| 1x   | Capacitor 1000UF       | R$19,35|
| 1x   | Potenciometro 1W     | R$8,75 |
| 1x   | Ponte de Diodo KBP06       | R$4,00 |
| 1x   | LED 10 MM      | R$2,50|
| 1x   | Protoboard   | R$39,10 |
| 1x   | Diodo Zener   | R$0,50 (unidade)|


## Descrição dos Componentes
- **TRANSFORMADOR**: Componente elétrico que altera o valor da tensão alternada (CA) utilizando indução eletromagnética. No circuito, é o responsável por diminuir a diferença de potencial de 127V para a margem final alcançada pela fonte (3V-12V). 

- **PONTE RETIFICADORA (PONTE DE DIODOS)**: Circuito formado por quatro diodos conectados de maneira específica para realizar a retificação de onda completa. Sua principal função é converter a corrente alternada (CA) em corrente contínua (CC), permitindo que a corrente elétrica "corra" sempre no mesmo sentido. No circuito, a ponte retificadora recebe a tensão alternada proveniente do transformador e a converte em uma tensão contínua pulsante. 

- **CAPACITOR**: Componente eletrônico capaz de armazenar energia elétrica temporariamente em um campo elétrico. No circuito desenvolvido, foi utilizado um capacitor de 1000 µF, sua função é armazenar carga elétrica quando a tensão atinge seus picos e liberá-la quando essa tensão diminui, assim, uniformizando a corrente e reduzindo as suas ondulações (#ripples#).

- **DIODO ZENNER** - Componente responsável por definir o limite máximo de tensão da nossa fonte. Quando a tensão tenta ultrapassar o valor máximo do nosso circuito (12 V), o diodo começa a conduzir corrente, evitando que ela continue aumentando. Dessa forma, ele protege o circuito e garante que a saída da fonte nunca ultrapasse esse limite. Em outras palavras, no nosso circuito, o diodo Zener "segura" a tensão máxima em 12 V, permitindo que a fonte seja ajustada com segurança em qualquer valor entre 3 V e 12 V.
  
- **RESISTORES** - Componentes que têm a função de limitar a corrente elétrica que circula pelo circuito, evitando que ela ultrapasse valores que possam danificar os outros componentes. Além disso, eles ajudam a controlar a distribuição da tensão no circuito, contribuindo para que a fonte funcione de forma estável.
Potenciômetro - Componente que permite ajustar a tensão de saída da fonte. Ao girar seu eixo, sua resistência é alterada, modificando a tensão fornecida pelo circuito. No nosso projeto, ele é o componente responsável por permitir que a saída seja regulada de forma contínua entre 3 V e 12 V.

- **TRANSISTOR** - Componente utilizado para controlar a passagem de corrente no circuito. No nosso projeto, ele trabalha em conjunto com o diodo Zener, regulando a corrente que passa por ele e contribuindo para que a fonte mantenha uma tensão de saída estável durante o ajuste entre 3 V e 12 V.










## Imagem do Circuito (Falstad)

<img width="835" height="298" alt="image" src="https://github.com/user-attachments/assets/2662686c-2e88-40bd-ab76-f6a35b188ed8" />


**Obs --> Circuito com a carga teste, como foi feito os cálculos para o pleno funcionamento do projeto.**

<img width="922" height="358" alt="image" src="https://github.com/user-attachments/assets/815ab65f-0a42-434d-a429-d226d3189e13" />

**Obs --> Circuito sem a carga teste, por isso, nao foi necessário adcionar o resistor de 100 Ohms para proteger o transistor.**

### Ripples ao Longo do Circuito
#### Na entrada do Transformador

<img width="581" height="187" alt="image" src="https://github.com/user-attachments/assets/9a923baa-8483-474d-9043-82574ca16bf5" />

#### Após a ponte retificadora

<img width="578" height="187" alt="image" src="https://github.com/user-attachments/assets/30f1f8da-9d72-411b-b373-3937cea3fc1c" />

#### Após o capacitor

<img width="577" height="193" alt="image" src="https://github.com/user-attachments/assets/bdef63e6-e6de-451e-92ce-4a08471d6b68" />

## EasyEDA Placa do Circuito Impresso (PCB)
<img width="828" height="439" alt="PCB_PCB_fonteajustavel_2_2026-07-02-1-1" src="https://github.com/user-attachments/assets/b66a7bb1-5598-42e0-aa8b-a809c034466a" />




## Video | Explicação do Projeto

https://drive.google.com/drive/folders/1JDEcJlynEaKJ3IBIwu-h6EHguiN8ARvE?usp=drive_link\

## Imagem do projeto

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/578ce786-689b-431e-9ff1-fcce0f726546" />

## Cálculo Capacitor 

<img width="777" height="847" alt="image" src="https://github.com/user-attachments/assets/3d3b211b-e6b6-4ad1-9e9e-320e2dd201a7" />









## Grupo

Caio Andrade Oliveira - 17929272\
Davi Gabriel Gottardi - 17885361\
Bernardo Moreira Brandão Bastos - 17881401\
Enzo Ferreira Amorim - 17887488






