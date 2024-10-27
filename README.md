---

# Análise de Cancelamento de Clientes 📊🚫

Este projeto realiza uma análise detalhada para entender e reduzir o cancelamento de clientes. A abordagem foca em identificar padrões e aplicar filtros específicos para melhorar a retenção, concentrando esforços nos clientes com maior probabilidade de manterem contratos.

## Objetivo 🎯

O principal objetivo deste projeto é **reduzir a taxa de cancelamento** através da aplicação de medidas específicas que ajudam a identificar clientes que estão mais propensos a cancelar e tomar ações preventivas para retenção.

## Estratégia de Redução de Cancelamento 🛡️

A análise aplica as seguintes medidas para reduzir a taxa de cancelamento:

1. **Filtragem de Contratos**:
   - **Problema:** Clientes com contratos mensais apresentaram alta taxa de cancelamento.
   - **Solução:** Remover clientes com contratos mensais da análise para focar em contratos trimestrais e anuais, que têm maior chance de retenção.

2. **Controle de Atrasos**:
   - **Problema:** Clientes com muitos dias de atraso nos pagamentos tendem a cancelar seus contratos.
   - **Solução:** Excluir clientes com mais de **20 dias de atraso** para focar naqueles que têm menos tendência ao cancelamento.

3. **Monitoramento de Contatos**:
   - **Problema:** Uma alta frequência de chamadas para o call center pode indicar insatisfação, levando ao cancelamento.
   - **Solução:** Filtrar clientes que ligaram para o call center **até 4 vezes**, identificando um comportamento mais estável.

## Resultados 📈

Após aplicar os filtros mencionados, o código calcula e exibe a **taxa de cancelamento** ajustada, mostrando o impacto das medidas aplicadas. Os resultados são apresentados em formato percentual para facilitar a análise e a tomada de decisão.

## Como Executar o Projeto 🏃‍♂️

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/emerson10110/pythonInsights.git
   ```
2. **Navegue até o diretório do projeto**:
   ```bash
   cd nome-do-repositorio
   ```
3. **Instale as dependências necessárias** (se houver):
   ```bash
   pip install -r requirements.txt  # Exemplo para projetos Python
   ```
4. **Execute o script de análise**:
   ```bash
   python analise_cancelamento.py  # Ajuste para o nome do seu script
   ```

## Tecnologias Utilizadas 🛠️

- **Linguagem de Programação:** Python (ou outra linguagem que você estiver usando)
- **Análise de Dados:** Pandas, NumPy (ou outras bibliotecas relevantes)
- **Visualização de Resultados:** Matplotlib, Seaborn (se aplicável)

## Contribuições 🤝

Contribuições são bem-vindas! Se você tem ideias para melhorar a análise ou sugerir novas abordagens para reduzir o cancelamento, sinta-se à vontade para abrir **Issues** e enviar **Pull Requests**.

## Licença 📄

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Feito com dedicação para ajudar a melhorar a retenção de clientes 💪.

---

![Cligacao](https://github.com/user-attachments/assets/e08f44ac-79f2-488f-9231-4ed3f34ae204)

![total](https://github.com/user-attachments/assets/72416790-0a6b-4060-b4fe-816e9b37280b)

