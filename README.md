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

## 1. Introdução

Este documento apresenta a comparação de custos entre duas regiões da AWS para hospedar nossa API de Machine Learning: **São Paulo (BR)** e **Virginia do Norte (EUA)**.
O objetivo é avaliar a melhor opção considerando **custos, latência e requisitos legais de armazenamento de dados**.

A instância utilizada na comparação possui as seguintes características:

* Sistema operacional: Linux
* 2 vCPUs
* 1 GiB de memória RAM
* Até 5 Gbps de rede
* 50 GB de armazenamento
* Modelo de cobrança: On-Demand

---

## 2. Comparação de Custos

| Região                  | Custo Mensal (USD) |
| ----------------------- | ------------------ |
| São Paulo (BR)          | 17,38              |
| Virginia do Norte (EUA) | 11,13              |

**Observações:**

* A instância em Virginia do Norte é mais barata, porém a região de São Paulo oferece menor **latência** para usuários no Brasil.
* A escolha da região também é influenciada por **restrições legais**, já que a LGPD exige cuidado no armazenamento de dados sensíveis de cidadãos brasileiros.

---

## 3. Justificativa Técnica

Apesar do custo mensal mais elevado em São Paulo (USD 17,38 contra USD 11,13 em Virginia), a região brasileira foi escolhida pelos seguintes motivos:

1. **Latência reduzida:** A proximidade geográfica garante respostas mais rápidas da API para sensores e usuários no Brasil.
2. **Compliance legal:** A legislação brasileira exige que certos dados sensíveis sejam armazenados localmente, evitando riscos legais ao hospedar fora do país.
3. **Manutenção e suporte:** A região de São Paulo possui suporte e data centers que atendem diretamente o mercado brasileiro, facilitando monitoramento e manutenção.

**Conclusão:**
A escolha da região **São Paulo (BR)** equilibra desempenho, segurança e conformidade legal, apesar de um custo levemente superior.

---

## 4. Vídeo Demonstrativo

O vídeo explicativo da comparação de custos, incluindo a demonstração da AWS Pricing Calculator e a justificativa da escolha, está disponível no YouTube:

[Link do vídeo “não listado”](URL_DO_VIDEO_AQUI)

**Duração:** até 5 minutos

---

## 5. Referências

* [AWS Pricing Calculator](https://calculator.aws/#/?nc2=h_pr_calc)
* [LGPD – Lei Geral de Proteção de Dados](https://www.gov.br/secretariageral/pt-br/lgpd)



![AWS Pricing Calculator - Virginia](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/raw/main/assets/viginia_1.png)

![AWS Pricing Calculator - Virginia](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/blob/main/assets/virginia_2.png)

![AWS Pricing Calculator - Virginia](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/blob/main/assets/virginia_3.png)

![AWS Pricing Calculator - São Paulo](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/blob/main/assets/sao_paulo_1.png)

![AWS Pricing Calculator - São Paulo](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/blob/main/assets/sao_paulo_2.png)

![AWS Pricing Calculator - São Paulo](https://github.com/Startup-FarmTech-Solutions/Cap-1---FarmTech-na-era-da-cloud-computing/blob/main/assets/sao_paulo_3.png)


## 🗃 Histórico de lançamentos
    
* 0.1.0 - 05/08/2024
    
* 0.2.0 - 07/08/2024
*     
* 0.3.0 - 06/09/2024 - esse modelo contitui a predivisão com modelos binarizados do csv
  

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
