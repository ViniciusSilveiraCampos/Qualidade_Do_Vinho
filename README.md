<h2 align="justify"> QUALIDADE DO VINHO 🍷 </h2>

<p align="justify">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> 
    <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white"/>  
    <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/> 
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/> 
</p>    
<p align='justify'>
Este projeto visa aplicar técnicas de machine learning para a classificação de vinhos com base em suas características químicas. Utilizamos uma rede neural para realizar a classificação e avaliamos seu desempenho com uma matriz de confusão e uma análise visual das previsões. </p>

<br>

<h2> Descrição do Projeto 📝</h2>
<p align='justify'>
    O projeto inclui as seguintes etapas:
    <br> <br>
    1. <code>Importação das Bibliotecas</code>: Carregamos todas as bibliotecas necessárias, como `pandas`, `numpy`, `seaborn`, `scikit-learn` e `torch`. 
    <br> <br>
    2. <code> Preparação dos Dados</code> Carregamos a base de dados de vinhos, renomeamos as colunas, e realizamos a codificação das classes. 
    <br> <br>
    3. <code> Divisão dos Dados</code>: Separamos os dados em conjuntos de treinamento e teste. 
    <br> <br>
    4. <code> Construção do Modelo</code>: Definimos uma rede neural com duas camadas escondidas usando a biblioteca PyTorch.
    <br> <br>
    5. <code> Treinamento do Modelo</code>: Treinamos o modelo usando a função de perda de entropia cruzada e o otimizador Adam. 
    <br> <br>
    6. <code> Avaliação</code>: Avaliamos o modelo usando uma matriz de confusão e uma visualização com `seaborn`.
    <br>
</p>
<p align='justify'>
Para executar este projeto, você precisará ter o Python instalado em seu sistema, juntamente com as seguintes bibliotecas: </p>
- pandas <br>
- numpy <br>
- seaborn <br>
- scikit-learn <br> 
- torch <br>

<br>

<h2> Base de dados 💾 </h2>


<p align='center'><img src="https://github.com/ViniciusSilveiraCampos/QualidadeDoVinho-/assets/108243297/584fa298-1d16-45ea-98fe-92b9ea0283d3" width=50%> </p>


- O conjunto de dados: https://archive.ics.uci.edu/dataset/109/wine <br> <br>
- Esses dados são resultados de uma análise química de
vinhos cultivados na mesma região da Itália, mas derivados de três
cultivares diferentes. 
A análise determinou as quantidades de 13 constituintes
encontrado em cada um dos três tipos de vinhos. <br> <br>
- Há 178 classificações, dividadas entre as três cultivas, com maior porcentual da segunda classe: 


<h2> Resultados 📊 </h2>
<p align='justify'> 
O modelo foi treinado por 2000 épocas, e a precisão e a perda foram monitoradas durante o treinamento. Abaixo está a matriz de confusão resultante da avaliação do modelo:
</p>

```python
sns.heatmap(matriz, annot=True)
```

<p align='center'>
<img src='https://github.com/ViniciusSilveiraCampos/QualidadeDoVinho/assets/108243297/68022328-e071-4aa7-8170-35d1be0115c8' width=50%> </p>

<p align='justify'>
O desempenho do modelo foi medido pela acurácia e pela visualização da matriz de confusão. A acurácia média durante o treinamento foi registrada em cada época.
</p>



## Contato

Link do Projeto: https://github.com/ViniciusSilveiraCampos/Qualidade_Do_Vinho/blob/main/Classificação_Vinhos.ipynb


---

