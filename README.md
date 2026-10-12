# Previsão de Falhas na Indústria

## O Problema
No ambiente de manufatura da Indústria, paradas não programadas por quebras de máquinas geram atrasos na linha de produção e alto custo operacional. Este projeto é um Pipeline Preditivo de Ciência de Dados focado em prever falhas mecânicas através de leituras de sensores de telemetria (como Rotação RPM, Torque e Temperatura), visando a manutenção preditiva.

##  Técnicas e Tecnologias Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, Imbalanced-Learn.
- **Modelagem:** 
  - Tratamento de Outliers e Imputação pela Mediana.
  - Feature Engineering (Criação de Variável `Potência`).
  - Prevenção de Data Leakage.
  - Balanceamento de Classes com SMOTE.
  - Treinamento e tuning de Modelos KNN e Árvore de Decisão.
- **Controle de Versão:** Git Flow (uso de branch `develop` e branches auxiliares).

##  Como Executar
1. Clone este repositório em sua máquina: 
   `git clone https://github.com/robsongfk/predicao-falhas-industria.git`
2. Instale as dependências listadas no projeto: 
   `pip install -r requirements.txt`
3. O dataset original `manutencao_preditiva.csv` deve ser mantido no mesmo diretório ou referenciado corretamente na primeira célula do notebook.
4. Execute o arquivo `pipeline_preditivo.ipynb` utilizando o Jupyter Notebook, VS Code ou Google Colab.

##  Próximas Melhorias
- Deploy do modelo treinado utilizando uma API (Flask ou FastAPI).
- Implementar modelos Ensemble (como Random Forest ou XGBoost) para comparar o ganho de acurácia com a Árvore simples.
- Criação de um Dashboard interativo (Streamlit) para monitoramento em tempo real pelas equipes de engenharia.

---
**🎥 Apresentação do Projeto em Vídeo:**
Link do google drive do vídeo
