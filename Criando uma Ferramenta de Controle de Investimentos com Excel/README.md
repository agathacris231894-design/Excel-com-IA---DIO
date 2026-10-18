# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

## 📌 Sobre o projeto

Este projeto consiste no desenvolvimento de uma ferramenta interativa no Microsoft Excel para simular investimentos em Fundos de Investimento Imobiliário (FIIs).

A planilha permite calcular o patrimônio acumulado a partir de aportes mensais e de uma taxa de rendimento estimada, além de projetar os dividendos mensais e comparar diferentes horizontes de investimento.

O projeto foi desenvolvido como parte de um desafio prático da [DIO](https://www.dio.me/), com foco na aplicação de fórmulas, organização de dados e construção de uma ferramenta voltada à resolução de um problema de negócio.

## 🎯 Objetivos

Desenvolver uma ferramenta que permita responder às seguintes perguntas:

- Quanto investir mensalmente?
- Por quantos anos investir?
- Qual será o rendimento mensal estimado?
- Qual patrimônio poderá ser acumulado ao longo do tempo?
- Quanto esse patrimônio poderá gerar em dividendos mensais?

## ⚙️ Funcionalidades

- Simulação de investimentos com aportes mensais.
- Cálculo do patrimônio futuro com a função `VF` do Excel.
- Estimativa de dividendos mensais com base no patrimônio acumulado e na taxa de distribuição considerada.
- Projeção de cenários para 2, 5, 10, 20 e 30 anos.
- Sugestão de aporte mensal equivalente a 30% do salário informado.
- Distribuição dos aportes entre seis tipos de fundos imobiliários.
- Seleção de perfil de investidor por meio de uma lista suspensa.
- Consulta de percentuais de alocação com `PROCV` e chave composta.

## 🧮 Fórmulas e conceitos aplicados

### Função VF

A função `VF` (Valor Futuro) é utilizada para estimar o patrimônio acumulado ao longo do período de investimento, considerando uma taxa de rendimento e aportes periódicos.

Ela permite simular como contribuições mensais podem crescer ao longo do tempo.

### Função PROCV e chave composta

A função `PROCV` é utilizada para localizar o percentual de alocação correspondente ao perfil de investidor e ao tipo de fundo imobiliário selecionados.

Para isso, uma chave composta combina essas duas informações, permitindo identificar a distribuição adequada para cada combinação de perfil e categoria de fundo.

### Intervalos nomeados

Os intervalos nomeados tornam as fórmulas mais legíveis e facilitam a manutenção da planilha.

Intervalos previstos no projeto:

- `aporte`: valor investido mensalmente.
- `taxa_mensal`: taxa de rendimento mensal estimada.

Outros intervalos poderão ser adicionados conforme a implementação.

## 👤 Perfis de investidor

A ferramenta utiliza uma tabela auxiliar para definir a distribuição percentual dos aportes entre seis tipos de fundos imobiliários, de acordo com o perfil selecionado.

Os percentuais serão documentados após a definição da tabela de alocação. Cada perfil deverá totalizar 100%.

**Origem dos percentuais:** [preencher com os critérios utilizados e informar se foram adaptados do exemplo apresentado no desafio da DIO].

As distribuições têm finalidade didática e não constituem recomendação de investimento.

## 🛠️ Tecnologias e ferramentas

- Microsoft Excel
- Fórmulas financeiras e funções de pesquisa
- Validação de dados
- Intervalos nomeados
- Tabelas auxiliares
- Visualização e organização de dados

## 📈 Resultados e demonstração

Esta seção será atualizada após a conclusão da planilha.

Serão incluídas capturas de tela demonstrando:

- A tela principal do simulador preenchida com valores fictícios.
- As projeções de patrimônio e dividendos.
- A alteração da distribuição dos aportes ao trocar o perfil de investidor.

## 💡 Aprendizados

O desenvolvimento deste projeto permite praticar:

- Tradução de perguntas de negócio em cálculos e indicadores.
- Aplicação de fórmulas financeiras no Excel.
- Organização e consulta de dados por meio de tabelas auxiliares.
- Uso de referências absolutas e intervalos nomeados.
- Validação de dados para tornar a ferramenta mais interativa.
- Construção de uma interface simples e intuitiva para o usuário.
- Análise de cenários para apoiar a tomada de decisão.

## 🚀 Melhorias futuras

- Criar um gráfico de pizza dinâmico para visualizar a distribuição dos aportes.
- Implementar uma simulação automática com aporte equivalente a 30% do salário.
- Adicionar novos cenários de investimento.
- Aprimorar a interface para facilitar a utilização da ferramenta.
- Incluir comparações visuais entre diferentes perfis de investidor.

## ⚠️ Aviso

Este simulador possui finalidade exclusivamente educacional. Os resultados são estimativas matemáticas baseadas nos parâmetros informados e não representam garantia de rentabilidade futura.

Fundos imobiliários apresentam riscos, e os dividendos podem variar ao longo do tempo. Os perfis e percentuais de alocação são exemplos didáticos, não recomendações financeiras.

## 📚 Créditos

Projeto desenvolvido como desafio prático de Excel da [Digital Innovation One (DIO)](https://www.dio.me/), com base nas orientações e nos conteúdos apresentados pelo expert Felipe Aguiar.

---

**Status do projeto:** Em desenvolvimento.
