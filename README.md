# projeto-analisepreditivavendas

Este projeto visa criar um modelo preditivo para prever o tempo de entrega em um e-commerce brasileiro, utilizando o Olist Dataset. O pipeline inclui desde a preparação dos dados até a avaliação e visualização dos resultados. O modelo será avaliado com base em métricas como RMSE, MAE e R².

Dados os dados foram extraídos do Kaggle e estão disponíveis em: [Olist Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).


## Estrutura do Projeto
- **data/**: arquivos de dados brutos e processados
- **models/**: modelos treinados (não versionados no GitHub)
- **notebooks/**: notebooks de EDA, modelagem e visualização
- **README.md**: documentação do projeto
- **.gitignore**: regras para não versionar arquivos grandes/sensíveis

## Principais Etapas
1. **Exploração e preparação dos dados**
2. **Engenharia de features**
3. **Modelagem preditiva (Random Forest, XGBoost, LightGBM, CatBoost)**
4. **Validação cruzada e comparação de modelos**
5. **Visualização dos resultados e análise de erros**

## Como Executar
1. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
2. Execute os notebooks na ordem:
   - `01_data_preprocessing_eda.ipynb.ipynb`
   - `02_modelling_evaluation.ipynb`
   - `03_results_visualization.ipynb`

## Observações Importantes
- **Modelos salvos**: arquivos em `models/` não são versionados no GitHub devido ao tamanho.
- **Dados**: utilize os arquivos da pasta `data/` (Olist Dataset).
- **Reprodutibilidade**: utilize o mesmo random_state para splits e modelagem.

## Principais Bibliotecas Utilizadas
- pandas
- numpy
- scikit-learn
- xgboost
- lightgbm
- catboost
- matplotlib
- seaborn

Obrigado por acompanhar este projeto! Sinta-se à vontade para contribuir ou fazer perguntas.
