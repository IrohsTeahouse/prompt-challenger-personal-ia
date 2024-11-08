<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
#Contexto
Você é um personal trainer especialista e irá auxiliar na montagem de um treino ideal, baseando-se nas variáveis abaixo:

#Variáveis
{{Tipo Alimentação}} = Refeições não balanceadas
{{Periodo de treino}} = 5 dias
{{Tipo de treino}} = Cardio, HIIT, Maquinário
{{Quanto tempo tem disponível}} = 2 horas
{{Qual objetivo}} = Ganho de massa

#Regras

Regra 1: Tipo de Alimentação
Identificar qual tipo alimentação  nas variáveis foi informado
-Refeições não balanceadas, geralmente refeições rápidas que faltam nutrientes
-Refeições balanceadas, são aquelas que dão todos os nutrientes necessários
-Refeições com suplementação, para além das balanceadas inclui foco nos micros e macros nutrientes para desenvolvimento muscular, ou perda de gordura

Regra 2: Periodo de treino
Verificar os dias disponíveis para gerar o treino necessário
-1 dia, Full Body: Treino que trabalha o corpo todo em uma única sessão.
-3 dias, ABC: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
5 dias, ABCDE: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

Regra 3: Tipo de treino
Verificar o tipo de treino escolhido
-Funcional, Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
-Maquinário, Exercícios feitos em máquinas, com foco em isolar grupos musculares.
-Peso Livre, Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
-Cardio, Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
-HIIT, Treinos intervalados de alta intensidade, ótimos para queima de gordura.
Regra 4: Quanto tempo tem disponível
Verificar o tempo para poder intercalar os descansos e tempo de cada série do treino todo

Regra 5: Qual objetivo
Verificar qual objetivo e apartir disso definir se o tipo de treino escolhido poderá cumprir com o objetivo, caso não seja coerente o tipo de treino com o objetivo, altere o tipo de treino para que melhor se encaixe.
-Ganho de massa, focado em desenvolvimento muscular e resistência
-Perda de peso, focado em perda de peso e aumento na resistência

#Resultado Esperado
Com base nos valores informados e as regras, gere um treino que corresponda coerentemente com as regras e valores.

------------------------------------------------------------------------------------------------------------------
Resultado obtido pelo prompt com uma tentativa via Chatgpt

Para montar o treino ideal, vamos seguir as regras estabelecidas, analisando cada variável e ajustando os exercícios para atingir o objetivo de ganho de massa muscular.

---

## Análise das Variáveis e Regras

1. **Tipo de Alimentação**: 
   - **Refeições não balanceadas** — Para ganhos de massa muscular, seria essencial equilibrar a alimentação. Recomendo uma revisão para incluir proteínas, carboidratos complexos e gorduras saudáveis em cada refeição. Sem essa base, o ganho de massa pode ser comprometido, ainda que o treino seja intenso.

2. **Período de Treino**:
   - **5 Dias** — Este período permite o uso do método **ABCDE**, que foca em diferentes grupos musculares a cada dia, permitindo um trabalho detalhado e recuperação adequada entre sessões.

3. **Tipo de Treino**:
   - **Cardio, HIIT e Maquinário** — Cardio e HIIT são muito benéficos para a saúde cardiovascular e perda de gordura, mas para ganho de massa, o treino precisará priorizar exercícios com **maquinário e pesos livres**. Cardio leve pode ser usado como aquecimento.

4. **Tempo Disponível**:
   - **2 Horas** — Com esse tempo disponível, podemos distribuir os exercícios, aquecimentos e descansos para otimizar o treino sem pressa. Treinos com séries de 3 a 4 exercícios por grupo muscular com intervalos de descanso de 1-2 minutos entre as séries são ideais.

5. **Objetivo**:
   - **Ganho de Massa** — Este objetivo exige foco em exercícios que promovam a hipertrofia muscular (repetições entre 8-12, com carga moderada a alta).

---

## Estrutura do Treino

### Segunda-feira: Peito e Abdômen
- **Aquecimento**: 5 minutos de cardio leve
- **Supino Inclinado com Halteres** – 4x8-12
- **Supino Reto no Maquinário** – 4x8-12
- **Crossover** – 3x10-12
- **Flexão de Braço** (pelo menos 3 séries até a falha)
- **Abdômen**: Crunch no Maquinário – 3x15

### Terça-feira: Costas
- **Aquecimento**: 5 minutos de cardio leve
- **Puxada Alta** – 4x8-12
- **Remada Curvada** – 4x10
- **Remada Baixa no Maquinário** – 4x10
- **Pulldown** – 3x10-12

### Quarta-feira: Pernas
- **Aquecimento**: 5 minutos de cardio leve
- **Agachamento Livre** – 4x8-12
- **Leg Press** – 4x10
- **Extensão de Pernas no Maquinário** – 4x10
- **Flexão de Pernas no Maquinário** – 3x12
- **Panturrilhas**: Gêmeos no Maquinário – 3x15-20

### Quinta-feira: Ombros e Abdômen
- **Aquecimento**: 5 minutos de cardio leve
- **Desenvolvimento com Halteres** – 4x8-12
- **Elevação Lateral no Maquinário** – 4x10
- **Elevação Frontal com Halteres** – 3x12
- **Abdômen**: Elevação de Pernas – 3x15

### Sexta-feira: Braços
- **Aquecimento**: 5 minutos de cardio leve
- **Rosca Direta no Maquinário** – 4x10
- **Rosca Martelo com Halteres** – 3x12
- **Tríceps Pulley** – 4x10
- **Tríceps Francês com Halteres** – 3x12

---

### Dicas e Ajustes
- **Cardio**: Mantenha o cardio leve como aquecimento para não comprometer o ganho de massa.
- **HIIT**: Relegue o HIIT para o final de apenas dois dias na semana, para manter a resistência sem afetar a hipertrofia.
- **Alimentação**: Reforçar o consumo de proteínas e, se possível, adicionar suplementação (whey protein, BCAA) pós-treino.

Este plano atende aos objetivos e maximiza o ganho de massa muscular.
