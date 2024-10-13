**O código realiza uma análise para entender como reduzir o cancelamento de clientes, aplicando as seguintes medidas:**

**Filtragem de Contratos:** Remove clientes com contratos mensais, já que todos eles cancelaram. A ideia é focar em contratos trimestrais e anuais.
**Controle de Atrasos:** Exclui clientes com mais de 20 dias de atraso, pois eles são propensos a cancelar. Assim, apenas clientes com menos atrasos são considerados.
**Monitoramento de Contatos:** Filtra clientes que ligaram para o call center até 4 vezes, para evitar cancelamentos devido a alta frequência de ligações.

Por fim, o código mostra a taxa de cancelamento após aplicar esses filtros, em formato percentual.
