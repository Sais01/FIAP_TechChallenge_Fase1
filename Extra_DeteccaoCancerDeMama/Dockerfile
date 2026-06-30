# Usa uma imagem oficial leve do Python
FROM python:3.10-slim

# Define o diretório de trabalho
WORKDIR /app

# Instala as dependências de sistema necessárias
RUN apt-get update && apt-get install -y gcc libglib2.0-0 libsm6 libxext6 libxrender-dev && rm -rf /var/lib/apt/lists/*

# Copia os arquivos do projeto para o container
COPY . /app

# Instala as bibliotecas do Python
RUN pip install --no-cache-dir jupyterlab ipywidgets pandas numpy scikit-learn matplotlib tensorflow opencv-python-headless pillow kagglehub seaborn

# Expõe a porta do Jupyter
EXPOSE 8888

# Comando para iniciar o Jupyter Lab
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root"]