# Computação Bioinspirada

# Sobre o projeto

Esse repositório consiste em trabalhos realizados para a disciplina optativa do curso de Sistemas de Informação da Universidade Federal de Uberlândia de **Computação Bioinspirada**.

## O que é Computação Bioinspirada

Na natureza podemos observar exemplos variados de soluções eficientes para uma gama de problemas, como uma colônia de formigas que se organiza para estabelecer uma rota entre o ninho e a comida, afim de suprir suas necessidades de alimento. Assim como podemos notar a forma como nossos neurônios funcionam processando e transmitindo informações através de sinais eletro-químicos e se interconectando formando uma **rede neural biológica**.

Técnicas tradicionais de computação, muitas vezes, não são eficientes para resolver um grande número de problemas que são facilmente resolvidos por processos naturais como, por exemplo, problemas de otimização e reconhecimento de padrões. 

**Computação Bioinspirada** é o projeto de algoritmos baseado em princípios biológicos.
Exemplos: Redes Neurais Artificiais, Sistemas Imunológicos Artificiais, Computação Evolucionária, Inteligência de Enxames, etc (MEDEIROS et al., 2005).

# Modelo Perceptron

Um dos estudos desse projeto foi a implementação de um modelo **Perceptron** para classificar duas diferentes espécies da flor Iris, os resultados obtidos se encontram no arquivo de Relatório.


<img src="https://aiml.com/wp-content/uploads/2023/09/perceptron-a-neuron-2.png"  width="100%" height="280"/>

# Combinando algoritmo genético (AG) com Perceptron

Outra implementação dessa disciplica foi o desenvolvimento de um classificador que combine **algoritmo genético** para otimização de pesos em uma rede neural do tipo **Perceptron**.

O classificador foi desenvolvido seguindo os passos abaixo:
1. Selecionar um conjunto de dados para treinamento
2. Gerar população de pesos (matriz) com AG
3. Aplicar Perceptron para classificar
4. Evoluir pesos com AG até um criterio de parada
5. Seleção, recombinação e mutação
6. Usar melhor individuo (train_weights) para classificar demais dados

Os resultados obtidos estão localizados no arquivo Relatório na respectiva pasta.

# 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido em **Python**, utilizando **Jupyter Notebooks** como ambiente de desenvolvimento, com as seguintes bibliotecas:

- **[scikit-learn (sklearn)](https://scikit-learn.org/)** – Utilizada para construção e avaliação de modelos de machine learning.
- **[Matplotlib (matplotlib.pyplot)](https://matplotlib.org/)** – Usada para criação e visualização de gráficos.
- **[NumPy (numpy)](https://numpy.org/)** – Biblioteca fundamental para computação numérica com arrays e operações matemáticas.
- **[Pandas](https://pandas.pydata.org/)** – Usada para manipulação e análise de dados em estruturas como DataFrames.


> 💡 O ambiente Jupyter Notebook permite visualizações interativas, execução passo a passo e anotações junto ao código.

# ▶️ Como executar o projeto

Siga os passos abaixo para executar o projeto localmente utilizando **Python** e **Jupyter Notebook**:

### 1. Pré-requisitos

- [Python 3.x](https://www.python.org/)
- [pip](https://pip.pypa.io/en/stable/)
- [Jupyter Notebook](https://jupyter.org/)

### 2. Clone o repositório

```bash
git clone https://github.com/victor-marcal/Computacao-Bioinspirada.git
```

### Alternativa via Google Colab

Acesse o [Google Colab](https://colab.research.google.com) vá em "Abrir notebook" escolha o método via GitHub e informe o endereço: https://github.com/victor-marcal/Computacao-Bioinspirada.git


# Contato

- [LinkedIn](https://www.linkedin.com/in/victor-hugo-buiatti/) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg" width="25" height="20" style="vertical-align: middle;"/>
- victorhugobuiatti@gmail.com - victorhugobuiatti@gmail.com <img src="https://img.icons8.com/?size=100&id=P7UIlhbpWzZm&format=png&color=000000" width="25" height="20" style="vertical-align: middle;"/>


## Referências

- MEDEIROS, T. H. de; SILVA, F. L. da; SOUZA, R. A. de. *Computação Bioinspirada Aplicada à Robótica*. 2005.
- AIML. *What is a Perceptron?* Disponível em: <https://aiml.com/what-is-a-perceptron/>. Acesso em: 18 abr. 2025.

