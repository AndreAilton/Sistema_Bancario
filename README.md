# Objetivo Sistema_Bancario
Este código foi desenvolvido com o objetivo de simular um sistema bancário, com funcionalidades relacionadas a agências, clientes, empréstimos e cartões de crédito. Utilizando principalmente programação orientada a objetos (POO), considero que atingi este objetivo, dando margem a futuras atualizações no código, como Chave Pix, Conta Poupança, Milhas e Sistema de Moeda.

- 1 Fase Inicial
  Definição das Classes: **Agencia, ContaCorrente, e CartaoCredito** 

## Bibliotecas
Para atinjir o Objetivo Utilizei algumas bibliotecas basicas que não afetam o codigo diretamente em si
- **datetime e pytz**: para ajuste de horario e datas 
- **random.randint**: para geração de numeros aleatorios como do cartão de credito 
- **requests**: para usarmos API e 
- **copy**: para copiar listas sem altera-las
## Implementação da Agencia
A classe Agencia foi implementada, com os seguintes métodos: 
- Verificar o caixa
- Empréstimos
- Depósito no caixa
- Solicitação de empréstimo
- Realização de pagamentos
- Adição/remoção de clientes
- Cartões de crédito
 
 ela foi Fundamental para  o Desenvolvimento ja que sem ela um cliente não poderia abrir uma Contacorrente ou cartão de credito sem estar vinculado com a agencia previamente

## Implementação da ContaCorrente
A ContaCorrente foi desenvolvida para simular todas as funções que uma contacorrente basica poderia fazer Possui os metodos
consultas a historicos de transações
- Historico movimentações
- Saques
- Depositos
- Transferencias 


## Implementação da Classe CartaoCredito
A classe CartaoCredito foi implementada podendo ser criado um Cartão de Credito a quem ja possui uma ContaCorrente, onde apartir do momento em que for criado, vai ser vinculado a ContaCorrente e agencia. possui funções como 
- Consultas a Limite
- Limite Atual
- Pagamento de Fatura
- Ajuste de limite Atual
- Compras Online

## Testes e Validação
Foram realizados testes para verificar o funcionamento correto do código, garantindo que as funcionalidades estivessem operando conforme o esperado. Foram corrigidos eventuais erros e ajustados os comportamentos conforme necessário.

O código resultante fornece uma base sólida para a simulação de um sistema bancário básico, permitindo o controle de agências, clientes, empréstimos e cartões de crédito, com operações de depósito, solicitação de empréstimos, pagamentos e gerenciamento de clientes.
