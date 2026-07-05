# 🧬 Análise Topológica de Capsídeos Virais via Grafos

Este projeto usa modelos de redes para analisar o formato, a estabilidade e como as partes das proteínas (como as capas dos vírus) se encaixam e se organizam na natureza.

---

## 🛠️ Pré-requisitos

Antes de começar, verifique se tem instalado em sua máquina:
* **Python 3.8** ou superior.
* **Git** (para clonar o repositório).

---

## 🚀 Instalação e Configuração

Siga os passos abaixo para clonar o repositório, configurar o ambiente virtual e instalar todas as dependências necessárias para rodar os notebooks e scripts.

### 1. Clonar o Repositório

Abra o seu terminal (ou prompt de comando) e execute:
```bash
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
cd seu-repositorio

## DOS (Windows)

# Criar o ambiente virtual
python -m venv venv

# Ativar o ambiente virtual
venv\Scripts\activate

## PowerShell (Windows0

# Criar o ambiente virtual
python -m venv venv

# Ativar o ambiente virtual
.\venv\Scripts\Activate.ps1

Obs: Se o PowerShell bloquear a execução do script, execute o comando Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process antes de tentar ativar.

## Linux / macOS

# Instalar suporte a venv (necessário em algumas distribuições Linux como Ubuntu)
sudo apt install python3-venv  # Execute se necessário

# Criar o ambiente virtual
python3 -m venv venv

# Ativar o ambiente virtual
source venv/bin/activate

### 3. Instalação das Dependências e do Jupyter

Com o seu ambiente virtual devidamente ativado (você verá o indicador `(venv)` no terminal), atualize o gerenciador de pacotes e instale as ferramentas do projeto junto com o Jupyter Notebook:

```bash
# Atualizar o pip
pip install --upgrade pip

# Instalar o Jupyter e todas as bibliotecas do projeto
pip install notebook Biopython ProDy pandas networkx matplotlib seaborn py3dmol scikit-learn plotly
