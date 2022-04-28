# ExercicioTDD2

### Requisitos

Implementar um sistema de geração de nota fiscal a partir de uma fatura.

Uma fatura contém o nome e endereço do cliente, tipo do serviço e valor da fatura.

O gerador de nota fiscal deverá gerar uma nota fiscal que contém nome do cliente, valor da nota e valor do imposto a ser pago.

O valor da nota é o mesmo do valor da fatura.

Já o cálculo do imposto a ser pago deve seguir as seguintes regras:

- Caso o serviço seja do tipo "CONSULTORIA", o valor do imposto é de 25%;
- Caso o serviço seja do tipo "TREINAMENTO", o valor do imposto é 15%;
- Qualquer outro, o valor do imposto é 6%

Ao final da geração da nota fiscal, o sistema ainda deve enviar essa nota por e-mail, para o SAP, e persistir na base de dados.

## Entrega/MVP
Código responsável por **geração e encaminhamento** da nota fiscal para os processos acima citados 
