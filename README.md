# ADA - Exploratory Data Analysis
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=main)

- Instituição: Let's Code
- Curso: Santander Coders
- Disciplina: Técnicas de Programação I
- Professores: Matheus Barão Fiorin
- Alunos: Amanda Borges Matos Santana Magalhaes, Daniel Custodio Dias, Douglas Vieira Rocha, Karen Almeida Neves, Rhayza Pinto

Este projeto é uma exploração dos datasets: [Prouni 2005 - 2019](https://www.kaggle.com/datasets/saraivaufc/prouni) fornecidos pelo [Kaggle](https://www.kaggle.com/). O foco é realizar uma exploração e análise nesses dados.

A especificação completa do projeto pode ser encontrada em: [Projeto Final](https://github.com/DanielCustodioDias/Projeto_PROUNI/blob/main/utils/Projeto_final.md).

## Conteúdo

- Descrição dos Dados
- Objetivos
- Ferramentas Usadas
- Integrantes
- Recomendações
- Instalação
- Organização do projeto
- Contribuições

## Descrição dos Dados



## Objetivo

O objetivo desse projeto é de realizar uma análise exploratória dos dados do Prouni, verificar tendencias, como são distribuidas as bolsas e criar insights quanto ao projeto.

## Ferramentas Usadas 
Este projeto foi concluído usando Python e suas bibliotecas associadas, como NumPy, Pandas, Geopandas, Matplotlib, Seaborn e Ipykernel.

## Integrantes
Projeto desenvolvido pelos Devs:

- [Amanda Borges Matos Santana Magalhaes](https://github.com/magalhaesaamanda)
- [Daniel Custodio Dias](https://github.com/danielcustodiodias)
- [Douglas Vieira Rocha](https://github.com/dogaVrocha)
- [Karen Almeida Neves](https://github.com/KarenAlmeida23)
- [Rhayza Pinto](https://github.com/RhayzaPinto)

## Recomendações
- Cada desenvolvedor terá um notebook destinado à sua própria análise exploratória.
- Em relação aos commits será utilizado um padrão:
    - Commits de novas features. Ex: git commit -m "New: Readme"
    - Commits de updates. Ex: git commit -m "Update: Readme"
    - Commits de remoção. Ex: git commit -m "Delete: Readme"

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
PROUNI_2005_2019
 ┣ main
 ┃ ┣ edas
 ┃ ┃ ┣ amanda.ipynb
 ┃ ┃ ┣ daniel.ipynb
 ┃ ┃ ┣ douglas.ipynb
 ┃ ┃ ┣ karen.ipynb
 ┃ ┃ ┗ rhayza.ipynb
 ┃ ┣ tratamento
 ┃ ┃ ┗ tratamento.ipynb
 ┃ ┗ main.ipynb
 ┣ utils
 ┃ ┣ BR_Setores_2021_gpkg
 ┃ ┃ ┗ BR_Setores_2021.gpkg
 ┃ ┣ environment.yml
 ┃ ┣ Projeto_final.md
 ┃ ┗ requeriments.txt
 ┣ .gitignore
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