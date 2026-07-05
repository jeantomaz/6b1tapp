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
git clone https://github.com/jeantomaz/6b1tapp.git
cd seu-repositorio
```

### 2. Configurando o Ambiente Virtual

#### Windows (DOS)

Criar o ambiente virtual

```bash
python -m venv venv
```

Ativar o ambiente virtual

```bash
venv\Scripts\activate
```

#### Windows (PowerShell)

Criar o ambiente virtual

```bash
python -m venv venv
```

Ativar o ambiente virtual

```bash
.\venv\Scripts\Activate.ps1
```

Obs: Se o PowerShell bloquear a execução do script, execute o comando Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process antes de tentar ativar.

#### Linux / macOS

Instalar suporte a venv (necessário em algumas distribuições Linux como Ubuntu)

```bash
sudo apt install python3-venv  # Execute se necessário
```

Criar o ambiente virtual
```bash
python3 -m venv venv
```

Ativar o ambiente virtual
```bash
source venv/bin/activate
```

### 3. Instalação das Dependências e do Jupyter

Com o seu ambiente virtual devidamente ativado (você verá o indicador `(venv)` no terminal), atualize o gerenciador de pacotes e instale as ferramentas do projeto junto com o Jupyter Notebook:


Atualizar o pip

```bash
pip install --upgrade pip
```

Instalar o Jupyter e todas as bibliotecas do projeto

```bash
pip install notebook Biopython ProDy pandas networkx matplotlib seaborn py3dmol scikit-learn plotly
```
