# Data_Salaries
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=main)

- Instituição: Let's Code
- Curso: Santander Coders
- Disciplina: Estatística
- Professores: Gabriel Novais
- Alunos: Amanda Magalhaes, Daniel Custodio, Mariah Moreira e Marcia Freitas

Este projeto é uma exploração dos datasets: [Data Science Salaries 2023 ](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023/) fornecidos pelo [Kaggle](https://www.kaggle.com/). O foco é realizar uma exploração e análise nesses dados.


## Conteúdo

- Descrição dos Dados
- Objetivos
- Ferramentas Usadas
- Integrantes
- Recomendações
- Instalação
- Organização do projeto
- Contribuições


## Objetivo

O objetivo desse projeto é de realizar uma análise exploratória dos dados de salarios de pessoas atuantes na area de dados e criar insights quanto ao projeto.

## Ferramentas Usadas 
Este projeto foi concluído usando Python e suas bibliotecas associadas, como NumPy, Pandas, Geopandas, Matplotlib, Seaborn e Ipykernel.

## Integrantes
Projeto desenvolvido pelos Devs:

- [Amanda Magalhaes](https://github.com/magalhaesaamanda)
- [Daniel Custodio](https://github.com/danielcustodiodias)
- [Mariah Moreira]([https://github.com/KarenAlmeida23](https://github.com/mariah-moreira))
- [Marcia Furtado]([https://github.com/RhayzaPinto](https://github.com/marciafurtadodf))

## Recomendações
- Cada desenvolvedor terá um notebook destinado à sua própria análise exploratória.
- Em relação aos commits será utilizado um padrão:
    - Commits de novas features. Ex: git commit -m "Adicionando: Readme"
    - Commits de updates. Ex: git commit -m "Alterando: Readme"
    - Commits de remoção. Ex: git commit -m "Deletando: Readme"

## Instalação
Foi utilizado o [Python](https://www.python.org/) v3.11.

### Conda
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://conda.io/). Portanto para prosseguir necessita-se de sua [instalação](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
conda env create -f environment.yml
```

- Ativar
```sh
conda activate ada_eda_env
```

- Desativar
```sh
conda deactivate
```

### Requirements
Pode-se utilizar o arquivo requirements.txt para criar o ambiente virtual.

- Criar ambiente virtual
```sh
python -m venv ada_eda_env
```

- Ativar
```sh
source ./ada_eda_env/bin/activate
```

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
pip install -r requirements.txt
```

- Desativar
```sh
deactivate
```

## Organização do projeto
```sh
Projeto Estatistica
 ┣ data
 ┃ ┗ ds_salaries.csv
 ┣ main
 ┃ ┣ edas
 ┃ ┃ ┣ amanda.ipynb
 ┃ ┃ ┣ daniel.ipynb
 ┃ ┃ ┗ mariah.ipynb
 ┃ ┗ EDA.ipynb
 ┣ utils
 ┃ ┣ georef
 ┃ ┃ ┣ world_countries.dbf
 ┃ ┃ ┣ world_countries.shp
 ┃ ┃ ┗ world_countries.shx
 ┃ ┣ environment.yml
 ┃ ┣ Projeto_final.md
 ┃ ┗ requeriments.txt
 ┣ .gitattributes
 ┣ .gitignore
 ┣ LICENSE
 ┗ README.md
```

## Contribuições
As contribuições são sempre bem-vindas. Se você é um desenvolvedor, cientista de dados ou analista, pode contribuir para o projeto de várias maneiras, tais como:

- Criar novos notebooks;
- Desenvolver novas análises;
- Encontrar e corrigir erros;
- Ajudar a documentar o código;
- Refatorar o código existente.








dados
