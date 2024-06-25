# Análise de Desempenho de Funcionários

Este projeto tem como objetivo analisar o desempenho dos funcionários de uma empresa, identificando padrões e fatores que influenciam o desempenho, ajudando o departamento de RH a tomar decisões mais informadas sobre promoções, treinamentos e melhorias no ambiente de trabalho.

## Objetivos do Projeto

1. Coletar e carregar os dados de funcionários de um arquivo CSV.
2. Explorar e limpar os dados, garantindo sua qualidade e consistência.
3. Realizar uma análise exploratória detalhada para identificar padrões e tendências.
4. Aplicar engenharia de características para melhorar a qualidade dos dados de entrada.
5. Analisar e visualizar o desempenho dos funcionários.
6. Fornecer conclusões e recomendações baseadas nos insights obtidos.

## Estrutura do Projeto

- `data/`: Contém o arquivo CSV com os dados dos funcionários (`employee_performance_data.csv`).
- `notebooks/`: Notebooks Jupyter utilizados para a análise e desenvolvimento do projeto.
- `scripts/`: Scripts Python para pré-processamento e funções auxiliares.
- `results/`: Resultados e visualizações gerados durante o projeto.
- `README.md`: Documentação detalhada do projeto, incluindo informações sobre o dataset, etapas do projeto e resultados.

## Como Utilizar

1. Clone este repositório em sua máquina local:

```sh
git clone https://github.com/seu-usuario/analise-desempenho-funcionarios.git
````
2.Instale as dependências necessárias:
```
pip install -r requirements.txt
````
# Dataset
O arquivo employee_performance_data.csv contém os seguintes atributos dos funcionários:

- EmployeeID: Identificação única do funcionário.
- Age: Idade do funcionário.
- Department: Departamento em que o funcionário trabalha.
- YearsAtCompany: Número de anos que o funcionário está na empresa.
- JobRole: Função do trabalho.
- PerformanceScore: Nota de desempenho (escala de 1 a 5).
- LastPromotion: Anos desde a última promoção.
- TrainingTimesLastYear: Número de treinamentos no último ano.

# Conclusões
- Funcionários no departamento de Desenvolvimento tendem a ter pontuações de desempenho mais altas.
- Funções de trabalho como Desenvolvedor e Gerente apresentam variabilidade significativa nas pontuações de desempenho.
- Há uma correlação positiva entre o número de treinamentos no último ano e a pontuação de desempenho.
- A razão de promoção para anos na empresa pode influenciar a pontuação de desempenho, sugerindo que promoções mais frequentes podem estar associadas a melhores desempenhos.
