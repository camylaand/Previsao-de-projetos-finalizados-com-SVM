# Previsão de Projetos Finalizados com SVM

Este projeto utiliza **SVM (Support Vector Machine)** para prever se um projeto será finalizado ou não, com base em duas variáveis: `horas_esperadas` e `preco`.

## Funcionalidades

- Carrega dados de projetos e cria a coluna `finalizados`.  
- Visualiza os dados com gráficos de dispersão, separando projetos finalizados e não finalizados.  
- Remove projetos com `horas_esperadas = 0` para limpeza dos dados.  
- Divide os dados em **treinamento** e **teste**.  
- Treina modelos **LinearSVC** e **SVC**, avaliando a acurácia.  
- Aplica **StandardScaler** para normalizar os dados e melhorar a performance do modelo.  
- Visualiza a fronteira de decisão do modelo usando gráficos 2D (`contourf`).
