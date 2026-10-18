# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

## 📌 Sobre o projeto

Este projeto consiste no desenvolvimento de uma ferramenta interativa no Microsoft Excel para simular investimentos em Fundos de Investimento Imobiliário (FIIs).

A planilha permite calcular o patrimônio acumulado a partir de aportes mensais e de uma taxa de rendimento estimada, além de projetar os dividendos mensais e comparar diferentes horizontes de investimento.

O projeto foi desenvolvido como parte de um desafio prático da [DIO](https://www.dio.me/), com foco na aplicação de fórmulas, organização de dados e construção de uma ferramenta voltada à resolução de um problema de negócio.

## 1. Perguntas de negócio

A ferramenta foi desenvolvida para responder às seguintes perguntas:

- **Quanto investir por mês:** valor do aporte mensal informado pelo usuário.
- **Por quantos anos investir:** período escolhido para a simulação.
- **Qual a taxa de rendimento mensal:** percentual de rendimento estimado para a carteira.
- **Quanto de patrimônio será acumulado:** valor futuro estimado ao final do período de investimento.
- **Quanto será recebido em dividendos mensais:** estimativa de dividendos calculada com base no patrimônio acumulado e na taxa de distribuição mensal utilizada.

As respostas são apresentadas na planilha, junto às configurações e aos resultados da simulação.

## 2. Fórmulas utilizadas

### Função VF

A função `VF` (Valor Futuro) é utilizada para calcular o patrimônio acumulado ao longo do período de investimento, considerando a taxa de rendimento, os aportes periódicos e o prazo escolhido.

Ela também permite projetar diferentes cenários de investimento para **2, 5, 10, 20 e 30 anos**, facilitando a comparação dos resultados ao longo do tempo.

### Função PROCV e chave composta

A função `PROCV` é utilizada para buscar o percentual de alocação correspondente ao perfil de investidor e ao tipo de fundo imobiliário.

Para isso, é utilizada uma chave composta que combina o perfil e o tipo de FII, como `Conservador-PAPEL`. Essa chave permite localizar o percentual correto na tabela auxiliar e calcular a distribuição do aporte mensal.

## 3. Intervalos nomeados

Os intervalos nomeados facilitam a leitura das fórmulas e a manutenção da planilha.

| Intervalo nomeado | Finalidade |
|---|---|
| `aporte` | Representa o valor do aporte mensal. |
| `taxa_mensal` | Representa a taxa de rendimento mensal estimada. |

## 4. Perfis e percentuais de alocação

A ferramenta permite selecionar um entre três perfis de investidor: Conservador, Moderado e Agressivo. Cada perfil possui uma distribuição percentual entre seis tipos de fundos imobiliários.

### Distribuição dos aportes

| Tipo de FII | Conservador | Moderado | Agressivo |
|---|---:|---:|---:|
| PAPEL | 30% | 32% | 50% |
| TIJOLO | 50% | 40% | 10% |
| HÍBRIDOS | 10% | 8% | 5% |
| FOFs | 10% | 0% | 5% |
| DESENVOLVIMENTO | 0% | 10% | 20% |
| HOTELARIAS | 0% | 10% | 10% |
| **Total** | **100%** | **100%** | **100%** |

Os percentuais foram definidos com base na tabela de alocação utilizada no simulador, seguindo o modelo didático do desafio da DIO. Cada perfil totaliza 100%, garantindo que todo o aporte seja distribuído entre as categorias apresentadas.

## 5. Alterações em relação à ferramenta do Expert

[Descrever as alterações realizadas em relação à ferramenta apresentada pelo Expert Felipe Aguiar, como melhorias visuais, gráficos, novas simulações ou funcionalidades adicionais.]

## 6. Evidências de funcionamento

### Simulação com perfil Conservador

[Inserir print da planilha preenchida com o perfil Conservador.]

### Simulação com perfil Agressivo

[Inserir print da planilha preenchida com o perfil Agressivo.]

As capturas de tela devem demonstrar a mesma simulação nos dois perfis, evidenciando como a seleção altera a distribuição percentual dos aportes entre os tipos de fundos imobiliários.

## ⚠️ Aviso

Este simulador possui finalidade exclusivamente educacional. Os resultados são estimativas matemáticas baseadas nos parâmetros informados e não representam garantia de rentabilidade futura.

Os rendimentos e dividendos dos fundos imobiliários podem variar, e o investimento está sujeito a riscos. Os perfis e percentuais apresentados são exemplos didáticos e não constituem recomendações de investimento.

## 📚 Créditos

Projeto desenvolvido como parte do desafio prático de Excel da **Digital Innovation One (DIO)**, com base nas orientações e nos conteúdos apresentados pelo expert **Felipe Aguiar (Felipão)**.

[Digital Innovation One — DIO](https://www.dio.me/)

[Planilha de referência do Expert](https://hermes.dio.me/files/assets/a04b81b1-8e35-4e72-aeb9-98aed8ed4403.xlsx)
