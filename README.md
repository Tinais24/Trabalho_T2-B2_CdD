# Criação do venv
python3 -m venv venv

# Ativação do venv
source vev/bin/activate

# Comando para baixar as bibliotecas
python -m pip install streamlit pandas scikit-learn joblib

# Comando para rodar o streamlit
python3 -m streamlit run app.py

# Opicional - Se der erro quando for classificar os atributos da arma, depois de rodar o comando abaixo, execute o comando de abrir o streamlit novamente
python3 treinar.py