# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

### 5. Conclusao do Desafio
Com base no passo a passo, e treinamento do modelo Machine Learning no Amazon Sagemaker Canvas obtive as seguintes Métricas.

<img width="614" height="226" alt="metricas" src="https://github.com/user-attachments/assets/974ddeec-1497-4190-a353-997740b1db40" />



📊 RMSE (Root Mean Squared Error) — 0.004

Mede o erro médio das previsões, penalizando mais os erros grandes.

Está na mesma unidade do valor previsto (no seu caso, do ID_PRODUTO).

Quanto menor, melhor.

👉 Interpretação do seu valor: O modelo costuma errar em média cerca de ±0,004 em relação ao valor real. Ou seja, as previsões estão muito próximas do valor correto.

📊 MSE (Mean Squared Error) — 0.000

É o quadrado do erro médio.

Usado internamente para otimização do modelo.

Valores muito pequenos indicam alto nível de precisão.

👉 Interpretação do seu valor: O erro médio ao quadrado é praticamente zero, o que reforça que o modelo está com erro extremamente baixo.

🧠 Optimization Metric

Indica qual métrica o modelo usou para se ajustar durante o treinamento.

No seu caso, foi o MSE.

O algoritmo tentou minimizar essa métrica ao máximo.

📌 Frase explicativa da tela

“The model often predicts a value that is within +/- 0.004 of the actual value for ID_PRODUTO”

👉 Em português:

O modelo geralmente prevê um valor que fica dentro de ±0,004 do valor real do ID_PRODUTO.   

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
