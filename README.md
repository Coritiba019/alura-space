# Alura Space - Guia de Instalação e Execução

Este é um guia simples para clonar, configurar e executar o projeto Alura Space em seu ambiente local.

## Pré-requisitos

Antes de começar, verifique se você possui os seguintes requisitos instalados em seu sistema:

1. Python (versão 3.11 ou superior)
2. Git

## Clone o projeto
git clone [https://github.com/seu-usuario/alura_space.git](https://github.com/Coritiba019/alura-space.git)

## Entre na pasta do projeto
cd alura_space

## Crie o ambiente virtual

### No Windows

python -m venv .env

### No Linux
python3 -m venv .env

## Ative o ambiente virtual

### No Windows
.env\Scripts\activate

### No Linux
source .env/bin/activate

## Instale as dependências
pip install -r requirements.txt

## Inicie o projeto
python manage.py runserver

Agora você pode acessar o projeto em `http://localhost:8000/` no seu navegador.

Lembre-se de manter o terminal aberto enquanto o projeto estiver em execução. Você pode parar o servidor pressionando `Ctrl+C` no terminal.

Espero que essas instruções tenham sido úteis! Se você seguiu os passos corretamente, o projeto Alura Space deve estar rodando em seu ambiente local. Se tiver alguma dúvida, sinta-se à vontade para perguntar!
