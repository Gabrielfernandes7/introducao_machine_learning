# 📚 Conceitos Fundamentais de Machine Learning (ML)

## 🎯 1. Introdução e Definição Formal

**Machine Learning (ML)** é um subcampo da Inteligência Artificial (IA) que se concentra no desenvolvimento de algoritmos e modelos estatísticos. Estes modelos permitem que os sistemas de computadores **melhorem seu desempenho** em uma **Tarefa (T)** específica, através da **Experiência (E)**, medida por alguma **Métrica de Desempenho (P)**.

Esta definição é frequentemente resumida pela tríade **(T, E, P)**:

* **T - Tarefa (Task):** A função que o modelo deve aprender.
    * *Exemplos:* Classificação de imagens, Regressão de preços.
* **E - Experiência (Experience):** Os dados de treinamento (conjuntos de dados) fornecidos ao modelo.
* **P - Métrica de Desempenho (Performance):** A função de custo que quantifica o erro do modelo.
    * *Exemplos:* **MSE** (Erro Quadrático Médio) para Regressão; **Acurácia**, **Precision**, **Recall** e **F1-Score** para Classificação.

---

## 🧠 2. O Modelo em Machine Learning

Um **Modelo de Machine Learning** é um artefato de software que encapsula uma função matemática, treinada a partir dos dados (E), para calcular um valor de **saída (output)** com base em um ou mais valores de **entrada (input)**. Ele é o resultado final do processo de aprendizado.

---

## 📊 3. Tipos e Categorias de Machine Learning

Existem três categorias principais de algoritmos de ML, além do Semisupervisionado:

| Categoria | Descrição | Dados de Treinamento |
| :--- | :--- | :--- |
| **Supervisionado** | Aprende a partir de dados com as respostas corretas (*rótulos*). | Com Rótulos Conhecidos |
| **Não Supervisionado** | Identifica padrões e estruturas em dados sem respostas conhecidas. | Sem Rótulos |
| **Por Reforço** | Aprende por tentativa e erro, maximizando recompensas em um ambiente. | Sistema de Recompensa/Penalidade |

<div align="center">
    
![Diagrama ilustrando os principais tipos de aprendizado de máquina: Supervisionado, Não Supervisionado e por Reforço.](/docs/machine-learning-types.png)

</div>

### 3.1. Aprendizado Supervisionado

O Aprendizado Supervisionado é o termo geral para os algoritmos nos quais os dados de treinamento incluem **Valores de Recurso (Features)** e **Valores de Rótulo (Labels)** conhecidos. O objetivo é mapear a relação entre os recursos e os rótulos.

#### Tipos de Tarefa Supervisionada

1.  **Regressão (Regression):** O rótulo previsto pelo modelo é um **valor numérico contínuo**.
    * *Exemplo:* Previsão do preço de uma casa.
2.  **Classificação (Classification):** O rótulo previsto pelo modelo representa uma **categorização discreta** ou uma classe.

    * **Classificação Binária:** O rótulo determina se o item pertence a uma classe específica ou não (dois resultados mutuamente exclusivos: *Sim/Não*, *Spam/Não Spam*).
    * **Classificação Multiclasse:** O rótulo é previsto a partir de uma das **várias classes possíveis** (*Gato/Cachorro/Pássaro*).

### 3.2. Aprendizado Não Supervisionado

O Aprendizado Não Supervisionado envolve o treinamento de modelos usando dados que consistem apenas em **Valores de Recursos (Features)**, sem rótulos conhecidos. O foco é descobrir estruturas, distribuições ou padrões ocultos.

* **Clustering (Agrupamento/Clusterização):** Identifica semelhanças entre as observações com base em seus recursos e os agrupa em **clusters discretos**.
    * *Exemplo:* Agrupar flores semelhantes (por tamanho, pétalas, etc.) ou segmentar clientes por comportamento de compra.

---

## 📂 4. Módulos de Implementação (Notebooks)

Para detalhar a aplicação prática de cada tipo de tarefa, o conteúdo será dividido nos seguintes módulos práticos:

### 4.1. Módulo de Regressão

[Notebook de Regressão](/notebooks/supervisionado/regressao/regressao.ipynb)

### 4.2. Módulo de Classificação

*(Referência ao notebook de implementação de um modelo de classificação.)*

### 4.3. Módulo de Clustering

*(Referência ao notebook de implementação de um modelo de agrupamento.)*