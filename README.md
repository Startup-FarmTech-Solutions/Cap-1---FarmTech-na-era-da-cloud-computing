FIAP - Faculdade de Informática e Administração Paulista 

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# FarmTech na era da cloud computing


## 👨‍🎓 Integrantes: 
- <a href="https://github.com/Vitor985-hub">Vitor Eiji Fernandes Teruia 
- <a href="https://github.com/BPilecarte">Beatriz Pilecarte de Melo 
- <a href="https://github.com/AntonioBarros19">Antonio Ancelmo Neto barros 
- <a href="https://github.com/matheusbento04">Matheus Soares Bento da Silva 
- <a href="https://github.com/yggdrasilGit">Francismar Alves Martins Junior 

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/leonardoorabona">Lonardo Ruiz</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/andregodoichiovato">André Godoi</a>


## 📜 Descrição

Este projeto tem como objetivo utilizar algoritmos de Inteligência Artificial para analisar dados de clima e solo de uma fazenda de médio porte (200 hectares), com o intuito de prever o rendimento agrícola de diversas culturas.

As atividades envolvem:

- Análise exploratória dos dados climáticos e de solo;
- Detecção de padrões e agrupamentos por meio de clusterização;
- Modelagem preditiva com cinco algoritmos diferentes de regressão supervisionada;
- Avaliação dos modelos com métricas adequadas (R², MAE, RMSE etc.);
- Apresentação de conclusões, limitações e recomendações com base nos resultados obtidos.


## 📁 Estrutura de pastas
```
.
├── assets/
├── dados/
│   └── crop_yield.csv
├── notebooks/
│   ├── .ipynb_checkpoints/
│   └── jupyter notebook VitorEiji_rm562099_pbl_fase4
└── README.md
```
## 🔧 Como executar o código

### Pré-requisitos
- Python 3.10+
- Jupyter Notebook ou JupyterLab
- Bibliotecas utilizadas:
  - pandas, numpy, matplotlib, seaborn
  - scikit-learn
 
 ### passo a passo 

 1 - clone o repositório
```
https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing.git
```
2 - execute o notebook 
```
jupyter notebook VitorEiji_rm562099_pbl_fase4.ipynb
```

## Entrega 2 – Comparação de custos na AWS

Para hospedar nossa API de Machine Learning, usamos a **AWS Pricing Calculator** com uma instância Linux:

- 2 vCPUs
- 1 GiB de memória
- Até 5 Gbps de rede
- 50 GB de armazenamento

### Estimativa de custos (On-Demand)

| Região                  | Custo Mensal (USD) |
|-------------------------|------------------|
| São Paulo (BR)          | 25,00            |
| Virginia do Norte (EUA) | 18,00            |

> Apesar de Virginia do Norte ser mais barata, escolhemos **São Paulo (BR)** devido à **baixa latência e restrições legais de dados locais**.

![AWS Pricing Calculator - São Paulo](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/raw/main/assets/viginia_1.png)

![AWS Pricing Calculator - São Paulo](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/raw/main/assets/viginia_2.png)

![AWS Pricing Calculator - São Paulo](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/raw/main/assets/viginia_3.png)

<iframe src="https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/blob/main/assets/Edit%20Amazon%20EC2.pdf" width="800" height="600" style="border:1px solid #ccc;" scrolling="yes"></iframe>



Link do vídeo demonstrativo: [YouTube – comparação de regiões](https://youtu.be/seu_link_nao_listado)

## 🗃 Histórico de lançamentos
    
* 0.1.0 - 05/08/2024
    
* 0.2.0 - 07/08/2024
*     
* 0.3.0 - 06/09/2024 - esse modelo contitui a predivisão com modelos binarizados do csv
  

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
