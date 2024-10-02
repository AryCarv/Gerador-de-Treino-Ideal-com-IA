# Gerador-de-Treino-Ideal-com-IA

Este repositório apresenta um modelo de gerador de treino com Inteligência Artificial para pessoas que querem emagrecer ou ganhar massa muscular. O objetivo com o uso deste modelo é servir de apoio para o Personal Treiner poder auxiliar seus alunos com maior praticidade e eficiência.

## Tópicos

- [📝 Introdução](#-Introdução)
- [💪 Biotipos corporais](#-Biotipos-corporais)
- [📅 Dias disponíveis para treino](#-Dias-disponíveis-para-treino)
- [🏋️ Tipos de exercícios](#-Tipos-de-exercícios)
- [⏱ Tipos e horários da sua alimentação](#-Tipos-e-horários-da-sua-alimentação)
- [📌 Equipamentos de apoio para o seu exercício](#-Materiaal-de-apoio-para-o-seu-tipo-físico)
- [🛠️ Regras de negócio](#-Regras-de-negócio)


## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados de acordo com a necessidade e interesse de cada pessoa. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

| **Biotipo** | **Descrição**                                                                         |
| ----------- | ------------------------------------------------------------------------------------- |
| Ectomorfo   |	Corpo mais magro, difícil ganhar peso e massa muscular.                               |
| Mesomorfo   |	Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura. |
| Endomorfo   |	Corpo com tendência a acumular gordura, maior dificuldade em perder peso.             |

Nota: O usuário escolhe o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias disponíveis para treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo da quantidade mínima de dias informado na área da variável "Periodização", o assistente vai criar uma das peiodizações de treino abaixo:

| **Dias na semana** | **Tipo de treino sugerido** |
| ------------------ | --------------------------- |
| 1 dia              | Treino Full bory            |
| 3 dias             | Treino ABC                  |
| 5 dias             | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.
---

## 🏋️ Tipos de exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Tipo de treino** | **Descrição**                                                                                                 |
| ------------------ | ------------------------------------------------------------------------------------------------------------- |
| **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| **Hiit**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## ⏱ Tipos e horários da sua alimentação

Ao iniciar uma rotina de treinos semanal é importante estabelecer uma dieta equilibrada ao longo dos dias para que se obtenha melhores resultados com a atividade física. Dessa forma, para cada perfil de usuário o assistente (IA) vai determinar a melhor dieta e os horários adequados para alimentação, considerando o biotipo da pessoa e sua necessidade e interesse com os exercícios.

---

## 📌 Equipamentos de apoio para o seu exercício

Para cada biotipo e modalidade de exercícios o Assistente (IA) vai recomendar alguns aparelhos ou equipamentos para auxiliar o usuário nos treinos e com isso, poder alcançar melhores resultados.

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

# O Prompt

## Contexto

Você é um especialista em educação física e vai montar um plano de treinamento personalizado para pessoas de diferentes biotipos considerando as três vaiáveis abaixo:

## Variáveis
  
- {{Biotipo}}
- {{Periodização}}
- {{Tipo de treino}}

## Regras

Regra 1: Biotipo

Identificar qual o tipo corporal da pessoa conforme informado na variável {{Biotipo}} acima, que vai ser um dos três tipos especificados abaixo:

- Ectomorfo_	Corpo mais magro, difícil ganhar peso e massa muscular.
- Mesomorfo_	Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
- Endomorfo_	Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Regra 2: Periodização

Dependendo da quantidade mínima de dias informado na área da variável {{Periodização}}, criar uma das peiodizações de treino abaixo.

- 1 dia_	Treino Full Body
- 3 dias_	Treino ABC
- 5 dias_	Treino ABCDE

Regra 3: Tipo de treino

- Funcional_ São exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
- Maquinário_ São exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre_ São exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
- Cardio_ São exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
- HIIT_ São	treinos intervalados de alta intensidade, ótimos para queima de gordura.

Regra 4: Tipos e horários para se alimentar

Recomende a alimentação adequada para cada biotipo e modalidade de exercício escolhida e praticada durante a semana, tanto o que é importante comer antes do treino como depois, para que se obtenha melhores resultados com a atividade física.

Regra 5: Equipamentos de apoio para os exercícios

Recomende também, para cada biotipo e modalidade de exercícios, alguns aparelhos ou equipamentos para auxiliar o usuário nos treinos para com isso poder alcançar melhores resultados.

## Resultado esperado

Com base nos valores informados na área das variáveis e com as guidelines, crie um treino ideal para cada pessoa que corresponde com a combinação dessas 5 regras.
