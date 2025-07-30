# Mini Projeto de Análise de Dados

**Descrição:**  
Mini Projeto de Análise de Dados para um conjunto de dados sobre desempenho acadêmico de estudantes.

## Contexto

Este projeto tem como objetivo analisar um conjunto de dados contendo informações sobre estudantes do ensino médio, buscando identificar padrões e relações entre variáveis que influenciam o desempenho acadêmico (GPA e Nota).

O dataset utilizado está disponível em:  
https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset

## Colunas do Dataset (renomeadas)

- **EstudanteID**: Identificador único do estudante
- **Idade**: 15-18 anos
- **Gênero**: 0 = masculino, 1 = feminino
- **Etnia**: 0 = caucasiano, 1 = afro-americano, 2 = asiático, 3 = outra
- **Educação Parental**: 0 = nenhuma, 1 = ensino médio, 2 = alguma faculdade, 3 = bacharelado, 4 = superior
- **Horário de Estudos Semanal**: 0-20 horas
- **Ausência**: 0-30 faltas durante o ano letivo
- **Tutoria**: 0 = não, 1 = sim
- **Apoio parental**: 0 = nenhum, 1 = baixo, 2 = moderado, 3 = alto, 4 = muito alto
- **Extracurricular**: 0 = não, 1 = sim
- **Esportes**: 0 = não, 1 = sim
- **Música**: 0 = não, 1 = sim
- **Voluntariado**: 0 = não, 1 = sim
- **GPA**: Média de notas (escala 2,0-4,0)
- **Nota**: Quanto menor, melhor a nota

## O que o projeto faz

- Carrega e trata o dataset, renomeando colunas para o português.
- Realiza análises estatísticas e explora relações entre variáveis como gênero, etnia, apoio parental, atividades extracurriculares, ausências e desempenho acadêmico.
- Gera visualizações (gráficos de barras, linhas e dispersão) para facilitar a interpretação dos dados.
- Apresenta conclusões e recomendações baseadas nos resultados das análises.

## Como executar

1. Abra o notebook [mini_projeto.ipynb](mini_projeto.ipynb) no Google Colab ou Jupyter Notebook.
2. Certifique-se de ter o dataset disponível no caminho especificado no notebook.
3. Execute as células sequencialmente para reproduzir as análises e visualizações.

## Principais conclusões

- O apoio parental tem maior influência no GPA do que o nível de escolaridade dos pais.
- A participação em atividades extracurriculares está associada a um GPA médio mais alto.
- Existe uma correlação negativa moderada entre o número de ausências e o GPA.
- A quantidade de horas de estudo semanal não apresentou forte correlação com o desempenho.

## Requisitos

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Autores