<body>
<h1 align="center"> QUALIDADE DO VINHO 🍷 </h1>

<div>
  <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> 
        <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white"/>  
        <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/> 
        <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/>  <br><br>
        <img src="https://github.com/ViniciusSilveiraCampos/Qualidade_Do_Vinho/assets/108243297/69e158a1-f5a9-49cf-a852-19b1b433ec40" width="473.5px" height="308.5px"  >

  #

<p align="center">
  O projeto de Classificação de Vinhos com Rede Neural Perceptron, desenvolvida para explorar técnicas de aprendizado de máquina na análise e classificação de vinhos com base em suas características. Utilizando uma abordagem de rede neural perceptron, este projeto visa criar um modelo capaz de identificar e categorizar diferentes tipos de vinhos com base em atributos da sua base de dados.

<br>
<br>


<div>
  <h2 align="left" style="font-size: 24px"> DADOS 📊 </h2>
  <p>
    <img src="https://github.com/ViniciusSilveiraCampos/QualidadeDoVinho-/assets/108243297/584fa298-1d16-45ea-98fe-92b9ea0283d3" width=40% height=30% align="right">
</div>

<div>
  <p align="justify">
- O conjunto de dados: https://archive.ics.uci.edu/dataset/109/wine <br> <br>
- Esses dados são resultados de uma análise química de
vinhos cultivados na mesma região da Itália, mas derivados de três
cultivares diferentes. 
A análise determinou as quantidades de 13 constituintes
encontrado em cada um dos três tipos de vinhos. <br> <br>
- Há 178 classificações, dividadas entre as três cultivas, com maior porcentual da segunda classe: 
    </p>
</div>
<br>
<div>

<br>
<br>

## PRECISÃO. 🎯
- A rede neural, sem a necessidade de validação cruzada. Apenas o embaralhamento dos dados alcançou um porcentual de acerto de 93%. 
<p align='center'>
<img src='https://github.com/ViniciusSilveiraCampos/QualidadeDoVinho/assets/108243297/68022328-e071-4aa7-8170-35d1be0115c8' width=40% height=30%>

  
##  Estrutura da Rede Neural. 🤖
- A rede neural é composta pelas treze entradas, com duas camadas camadas ocultas, cada uma com oito neurônios ligadas as três camadas de saida. 

```python
classificador = nn.Sequential(
    nn.Linear(13, 8, bias=True),
    nn.ReLU(),
    nn.Linear(8, 8, bias=True),
    nn.ReLU(),
    nn.Linear(8, 3, bias=True))
```

<p align='left'>
<img src='https://github.com/ViniciusSilveiraCampos/QualidadeDoVinho-/assets/108243297/c00593ed-c748-472b-9ff1-589c394c7444' width=70% height=70%>
