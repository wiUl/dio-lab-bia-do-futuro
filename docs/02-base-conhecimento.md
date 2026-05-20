# Base de Conhecimento

## Dados Utilizados

Descreva se usou os arquivos da pasta `data`, por exemplo:

| Arquivo | Formato | Utilização no Agente |
|---------|---------|---------------------|
| `transacoes.csv` | CSV | Analisar padrão de gastos do usuário |
| `synthetic_income_expense_data.csv` | CSV | Analisar padrão de gastos do usuário |

---

## Adaptações nos Dados

> Você modificou ou expandiu os dados mockados? Descreva aqui.

Inclui mais um dataset de padrões de gastos do usuário ja que minha solução é focada nisso

---

## Estratégia de Integração

### Como os dados são carregados?
> Descreva como seu agente acessa a base de conhecimento.

 Colocar os dados diretamente no prompt ou carregar os arquivos junto ao prompt

### Como os dados são usados no prompt?
> Os dados vão no system prompt? São consultados dinamicamente?

Injetando os dados no prompt para melhor entendimento e contexto por parte do agente

---

## Exemplo de Contexto Montado

> Mostre um exemplo de como os dados são formatados para o agente.

```
Dados do Usuário:
- Nome: João Silva
- Renda Mensal: R$ 5.000
- Gasto Mensal: R$ 7.500
- Gasto por tópico:
 -- Saúde: R$ 1.000
 -- Alimentação: R$ 2.500
 -- Entretenimento/Lazer: R$ 700
...

Últimas transações:
- 01/11: Supermercado - R$ 450
- 03/11: Streaming - R$ 55
...
```
