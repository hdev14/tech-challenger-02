# Tech Challenger Fase 2

## Requisitos

- **Python 3.9+** (o ambiente de referência usa Python 3.9.6)
- `pip` e o módulo `venv` (já incluídos na instalação padrão do Python)

As dependências estão listadas em [`requirements.txt`](requirements.txt):

- `numpy`, `pandas` — manipulação de dados
- `scikit-learn` — modelagem e avaliação
- `matplotlib` — visualização
- `ipykernel`, `jupyter` — execução dos notebooks

## Instalação

Crie e ative um ambiente virtual e instale as dependências.

```bash
# 1. Criar o ambiente virtual na raiz do repositório
python3 -m venv venv

# 2. Ativar o ambiente virtual
source venv/bin/activate

# 3. Atualizar o pip e instalar as dependências
pip install --upgrade pip
pip install -r requirements.txt
```

