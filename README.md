#Análise e Predição de Tarifas da Uber: Explorando Padrões e Construindo Modelos Preditivos
Este projeto tem como objetivo analisar e prever tarifas da Uber com base no conjunto de dados Uber Fares Dataset, obtido no Kaggle. Exploramos padrões nos preços das corridas e desenvolvemos modelos de aprendizado de máquina para prever tarifas com base em variáveis relevantes.

📊 Dataset
O conjunto de dados Uber Fares Dataset contém informações sobre corridas da Uber, incluindo:

Origem e destino (latitude/longitude)
Distância percorrida
Horário da corrida
Clima e condições atmosféricas
Tarifa cobrada
Esses dados permitem explorar padrões e treinar modelos para prever tarifas com base em fatores como distância e horário da corrida.

🛠 Tecnologias Utilizadas
Linguagem: Python
Bibliotecas:
Pandas → Manipulação e análise de dados
NumPy → Operações matemáticas
Matplotlib e Seaborn → Visualização de dados
Scikit-learn → Construção e avaliação de modelos preditivos
📈 Etapas do Projeto
Coleta e pré-processamento dos dados

Remoção de valores nulos e inconsistentes
Conversão de tipos de dados
Extração de variáveis relevantes (ex: horário do dia, distância)
Análise exploratória dos dados (EDA)

Distribuição das tarifas
Relação entre distância e preço
Impacto do horário e clima na tarifa
Construção de modelos preditivos

Modelos testados: Regressão Linear, Random Forest e XGBoost
Avaliação dos modelos com métricas como RMSE e R²

🚀 Como Executar o Projeto

Clone o repositório:
git clone https://github.com/usuario/analise-tarifas-uber.git
cd analise-tarifas-uber

Instale as dependências:
pip install -r requirements.txt

Execute o script de análise:
python main.py

📌 Resultados e Conclusões
A distância da corrida é o fator mais determinante no preço da tarifa.
Corridas durante horários de pico e sob condições climáticas adversas tendem a ter tarifas mais altas.
O modelo Random Forest apresentou melhor desempenho na predição das tarifas.
🤝 Contribuição
Contribuições são bem-vindas! Para contribuir:

Faça um fork do repositório.
Crie uma branch para suas alterações (git checkout -b minha-feature).
Envie um pull request para revisão.
📜 Licença
Este projeto está sob a licença MIT.

