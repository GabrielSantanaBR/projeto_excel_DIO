# Simulador de Investimentos em Fundos Imobiliários — DIO

Projeto desenvolvido para o desafio prático da **DIO**, com o objetivo de aplicar conceitos de Excel na construção de uma ferramenta de simulação de investimentos em **Fundos Imobiliários (FIIs)**.

A planilha permite informar os principais parâmetros de uma simulação, estimar a evolução do patrimônio ao longo do tempo, calcular dividendos mensais e sugerir uma distribuição do aporte de acordo com o perfil do investidor.

## 📥 Arquivo do projeto

➡️ [Baixar / abrir a planilha do desafio](Desafio_DIO_Simulador_Investimentos_FIIs.xlsx)

## 🎯 Objetivo do desafio

O desafio propõe desenvolver uma ferramenta prática em Excel capaz de auxiliar o usuário na simulação de investimentos em FIIs, automatizando cálculos e tornando a análise mais clara para a tomada de decisão.

A solução criada trabalha com perguntas comuns de um investidor, como:

- Quanto investir por mês;
- Por quanto tempo investir;
- Qual taxa de rendimento considerar;
- Quanto patrimônio pode ser acumulado;
- Quanto esse patrimônio pode gerar em dividendos;
- Como distribuir o aporte entre diferentes categorias de FIIs.

## 🧩 Estrutura da planilha

### 1. Simulador

Área principal do projeto. Nela o usuário informa os parâmetros da simulação e acompanha os resultados calculados automaticamente.

Principais recursos:

- salário mensal;
- percentual sugerido para investimento;
- investimento mensal sugerido;
- aporte mensal;
- prazo do investimento em anos;
- taxa de rendimento mensal;
- patrimônio acumulado;
- dividendos mensais estimados;
- projeções para 2, 5, 10, 20 e 30 anos;
- seleção do perfil de investidor;
- distribuição automática do aporte por categoria de FII;
- gráficos para facilitar a interpretação dos resultados.

### 2. Perfis

Base auxiliar utilizada pelo simulador para determinar os percentuais de distribuição do aporte.

Perfis disponíveis:

- Conservador;
- Moderado;
- Agressivo.

Categorias consideradas:

- Papel;
- Tijolo;
- Híbridos;
- FOFs;
- Desenvolvimento;
- Hotelarias.

### 3. Instruções

Guia rápido dentro do próprio arquivo explicando como preencher a planilha e quais recursos do Excel foram utilizados.

## 🧮 Recursos e conceitos de Excel aplicados

O projeto demonstra, na prática:

- **Fórmulas financeiras**, utilizando `FV` (`VF` no Excel em português) para projeção do patrimônio;
- **Referências absolutas e relativas** para manter os cálculos consistentes;
- **VLOOKUP / PROCV** para buscar a distribuição correspondente ao perfil selecionado;
- **SUM / SOMA** para totalizações;
- **ROUND / ARRED** para padronização dos resultados financeiros;
- **Validação de dados** com lista suspensa para escolha do perfil;
- **Formatação condicional** e barras de dados;
- **Tabela estruturada** para organização da base de perfis;
- **Gráficos** para visualizar a evolução patrimonial e a composição do aporte;
- formatação monetária e percentual;
- organização visual de entradas, cálculos e resultados.

## 🔄 Funcionamento da simulação

1. O usuário informa salário, percentual destinado a investimentos, prazo e rendimento esperado.
2. A planilha calcula automaticamente um valor sugerido de investimento mensal.
3. O patrimônio futuro é estimado com base em aportes recorrentes e juros compostos.
4. A estimativa de dividendos é calculada sobre o patrimônio projetado.
5. O usuário escolhe seu perfil de investidor em uma lista suspensa.
6. A planilha consulta a base da aba **Perfis** e distribui automaticamente o aporte entre as categorias de FIIs.
7. Cenários de longo prazo e gráficos ajudam a comparar os resultados.

## 📊 Cenários de longo prazo

A ferramenta compara automaticamente os resultados para os seguintes horizontes:

| Prazo | Resultado apresentado |
|---|---|
| 2 anos | Patrimônio projetado + dividendos/mês |
| 5 anos | Patrimônio projetado + dividendos/mês |
| 10 anos | Patrimônio projetado + dividendos/mês |
| 20 anos | Patrimônio projetado + dividendos/mês |
| 30 anos | Patrimônio projetado + dividendos/mês |

Isso permite visualizar de forma simples o efeito do tempo e dos juros compostos sobre os aportes mensais.

## 📁 Estrutura do repositório

```text
projeto_excel_DIO/
├── Desafio_DIO_Simulador_Investimentos_FIIs.xlsx
└── README.md
```

## ▶️ Como utilizar

1. Baixe o arquivo `.xlsx` disponível neste repositório.
2. Abra-o no Microsoft Excel 365 ou versão compatível.
3. Acesse a aba **Simulador**.
4. Preencha as células destinadas às entradas do usuário.
5. Escolha o perfil de investidor.
6. Analise os cálculos, cenários e gráficos gerados automaticamente.

## ✅ Objetivos de aprendizagem atendidos

Com este projeto foram praticados os objetivos propostos no desafio:

- criação de uma ferramenta de simulação de investimentos em Excel;
- aplicação de cálculos financeiros de rendimento e dividendos;
- uso de recursos para organização e análise de dados;
- automação de cálculos que seriam trabalhosos manualmente;
- documentação clara do processo técnico;
- utilização do GitHub para versionamento e compartilhamento do projeto.

## ⚠️ Aviso

Esta planilha possui finalidade **educacional e demonstrativa**. Os valores calculados são simulações e não constituem recomendação de investimento. Rentabilidades passadas ou estimadas não garantem resultados futuros.

---

Projeto desenvolvido como parte da formação da **DIO** para demonstrar conhecimentos práticos em Microsoft Excel e análise de dados.