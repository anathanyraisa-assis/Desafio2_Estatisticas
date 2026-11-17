# Análise de Dados — Desafio Técnico | Generation Brasil

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio técnico da **Generation Brasil**, com o objetivo de aplicar conceitos fundamentais de análise de dados utilizando Python e ferramentas de visualização.

A análise utiliza dados fictícios de vendas de ingressos de um festival musical para investigar o comportamento dos preços e identificar diferenças entre as categorias de ingressos.

## Objetivo da análise

Responder à seguinte pergunta de negócio:

**O valor pago pelo ingresso é parecido entre as vendas ou muda muito conforme o tipo de ingresso?**

Para responder, foram analisados os valores das vendas, considerando as diferentes categorias de ingressos e informações complementares sobre as atrações musicais.

## Ferramentas e tecnologias

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub

## Etapas desenvolvidas

O projeto foi dividido nas seguintes etapas:

1. **Carregamento dos dados:** importação das bases de vendas de ingressos e informações das atrações musicais.
2. **Conhecimento dos dados:** análise da estrutura das tabelas, identificação das colunas e compreensão das informações disponíveis.
3. **Qualidade dos dados:** verificação de valores ausentes, registros duplicados e integridade das chaves de relacionamento.
4. **Análise estatística:** cálculo de média, mediana, moda, desvio padrão, variância, valores mínimos e máximos.
5. **Relacionamento entre tabelas:** utilização da operação `merge` para combinar os dados de vendas com as informações das atrações.
6. **Análise por categorias:** comparação dos valores dos ingressos por tipo de ingresso e gênero musical.
7. **Identificação de outliers:** aplicação do método IQR para identificar possíveis valores extremos e avaliar seu impacto nas estatísticas.
8. **Análise da distribuição:** avaliação da assimetria, percentis e distribuição dos valores em faixas.
9. **Visualização dos dados:** criação de histogramas e boxplots para facilitar a interpretação dos resultados.
10. **Conclusões e recomendações:** interpretação dos resultados e elaboração de recomendações com base nas evidências encontradas.

## Principais resultados

A análise identificou diferenças expressivas entre os valores médios das categorias de ingressos:

| Tipo de ingresso | Valor médio |
|---|---:|
| Camarote | R$ 1.782,10 |
| VIP | R$ 825,69 |
| Pista Premium | R$ 415,83 |
| Pista | R$ 210,43 |

Outros resultados relevantes:

- Média geral dos ingressos: R$ 469,54.
- Mediana geral: R$ 290,00.
- Desvio padrão: R$ 455,12.
- Assimetria: 2,36, indicando uma distribuição positiva.
- Foram identificados 4.653 candidatos a outliers pelo método IQR.

Os valores extremos foram mantidos na análise, pois podem representar vendas legítimas de categorias mais caras, como camarote, não havendo evidências suficientes de erros de preenchimento.

## Conclusão

Os resultados demonstram que o valor pago pelos ingressos muda significativamente conforme a categoria escolhida.

O camarote apresenta o maior valor médio, enquanto a pista possui o menor. Também foi possível observar que os preços mais elevados influenciam a média geral, evidenciando a importância de analisar outras medidas estatísticas, como a mediana e o desvio padrão.

A análise reforça a importância de utilizar diferentes técnicas estatísticas e visualizações para compreender o comportamento dos dados e apoiar decisões de negócio.

## Aprendizados

Durante o desenvolvimento do desafio, foram aplicados e praticados conhecimentos de:

- Manipulação e exploração de dados com Pandas.
- Estatística descritiva.
- Agrupamento e comparação de dados.
- Relacionamento entre tabelas.
- Identificação e interpretação de outliers.
- Análise de distribuição e percentis.
- Construção de gráficos e interpretação de resultados.
- Pensamento analítico e resolução de problemas de negócio.

## Uso de Inteligência Artificial

A inteligência artificial foi utilizada como ferramenta de apoio durante o desenvolvimento, auxiliando na compreensão de conceitos, estruturação de códigos, interpretação dos resultados e organização das análises.

As etapas foram acompanhadas e revisadas durante a execução do projeto.

---

**Projeto desenvolvido como parte dos desafios técnicos da Generation Brasil.**
