# Finding_donors
Projeto do curso de Machine Learning da Udacity
## Projeto: Encontrando doadores para a CharityML

## Visão geral do projeto
Neste projeto, você aplicará técnicas de aprendizagem supervisionada e seu raciocínio analítico sobre os dados coletados pelo censo dos Estados Unidos para ajudar a CharityML (uma instituição de caridade fictícia) a identificar as pessoas com maior probabilidade de doar à causa deles. Primeiro, você fará uma exploração para saber como os dados do censo são gravados. Em seguida, aplicará uma série de transformações e técnicas de pré-processamento para manipular os dados e organizá-los em um formato com o qual poderá trabalhar. Depois, avaliará vários modelos de aprendizagem supervisionada de sua escolha sobre os dados para definir qual é o mais adequado para a solução. Depois disso, otimizará o modelo que você selecionou e o apresentará como sua solução para a CharityML. Por fim, você explorará o modelo escolhido e suas predições por debaixo dos panos para avaliar seu desempenho considerando os dados disponibilizados.
preço de venda previsto para as suas estatísticas.

## Destaques do projeto
Este projeto foi desenvolvido de modo que você se familiarize com os muitos algoritmos de aprendizagem supervisionada disponíveis em sklearn e também para mostrar como cada modelo funciona e performa em um determinado tipo de dado. É importante em machine learning compreender exatamente quando e onde um determinado algoritmo deve ser usado e quando deve ser evitado.

O que você aprenderá ao concluir este projeto:
- Como identificar se o pré-processamento é necessário e como aplicá-lo.
- Como estabelecer uma referência para uma solução do problema.
- O que cada um dos vários algoritmos de aprendizagem supervisionada realiza, considerando um conjunto de dados específico.
- Como avaliar se um candidato a modelo de solução é adequado ao problema.

## Requisitos de software

Este projeto utiliza os seguintes software e bibliotecas Python:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Matplotlib](http://matplotlib.org/)

Você também precisará ter um software instalado para rodar e executar um [notebook Jupyter](http://ipython.org/notebook.html)

Se você ainda não tem o Python instalado, é altamente recomendado que instale a distribuição [Anaconda](http://continuum.io/downloads), que já tem os pacotes acima incluídos. Certifique-se de selecionar o instalador Python 2.7, não o 3.x.

## Iniciando o projeto

Para esta tarefa, você pode achar a pasta `finding_donors`, contendo os arquivos de projeto necessários, no [GitHub de projetos de machine learning](https://github.com/udacity/br-machine-learning), dentro da pasta `projects`. Você pode baixar todos os arquivos de projetos que iremos usar neste programa Nanodegree diretamente desse repositório. Certifique-se de usar a versão mais recente dos arquivos ao concluir um projeto.

Este projeto contém três arquivos:

- `finding_donors_PT.ipynb`: Este é o arquivo principal com o qual você trabalhará em seu projeto.
- `census.csv`: O conjunto de dados do projeto. Você carregará esses dados no notebook.
- `visuals.py`: Um arquivo Python que contém o código de visualização que é executado nos bastidores. Não o modifique

No terminal ou janela de comando, navegue até a pasta contendo os arquivos do projeto; em seguida, use o comando `jupyter notebook finding_donors_PT.ipynb` para abrir uma janela ou aba do navegador e trabalhar com seu notebook. Alternativamente, você pode usar o comando `jupyter notebook` ou `ipython notebook` e navegar para o arquivo notebook na janela do navegador que abrir. Siga as instruções no notebook e responda a todas as perguntas apresentadas para concluir o projeto com sucesso. Um arquivo **README** também foi fornecido com os arquivos de projeto, contendo as instruções ou informações adicionais necessárias. 
