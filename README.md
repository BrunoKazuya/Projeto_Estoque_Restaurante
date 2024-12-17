# **Sistema de Gerenciamento de Estoque para Restaurantes**

Este projeto é uma aplicação web desenvolvida em **Django** para realizar o gerenciamento de estoque de ingredientes em restaurantes. O sistema permite registrar, consultar, adicionar e remover ingredientes de forma eficiente, exibindo mensagens de feedback ao usuário.

---

## **Funcionalidades Principais**

1. **Registrar Ingredientes**  
   - Permite adicionar novos ingredientes ao estoque, informando o nome e a quantidade inicial.

2. **Adicionar Quantidade**  
   - Caso o ingrediente já exista, a quantidade é atualizada automaticamente.

3. **Consultar Ingredientes**  
   - Permite buscar um ingrediente pelo nome e visualizar sua quantidade disponível no estoque.

4. **Remover Ingredientes**  
   - Remove uma quantidade especificada de um ingrediente e alerta o usuário caso o estoque chegue a zero.

5. **Mensagens de Feedback**  
   - Exibe mensagens visuais de sucesso, erro ou alerta para cada operação realizada.

---

## **Tecnologias Utilizadas**

- **Python**: Linguagem principal do projeto.  
- **Django**: Framework para desenvolvimento web em Python.  
- **SQLite**: Banco de dados leve utilizado no projeto.  
- **HTML/CSS**: Estruturação e estilização das páginas.  

---

## **Pré-requisitos**

Para rodar o projeto em sua máquina, você precisa ter:  
1. **Python 3.x** instalado.  
2. **Pip** (gerenciador de pacotes Python) instalado.  
3. **Git** (para controle de versões, opcional).

---

## **Instalação e Configuração**

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DA_PASTA_DO_PROJETO>

2. **Instale o Suporte para Ambientes Virtuais**:
   ```bash
   sudo apt-get install python3-venv

3. **Crie um ambiente virtual**:
    ```bash
    python3 -m venv .venv

4. **Ative o Ambiente Virtual**:
   ```bash
   source .venv/bin/activate #mac/linux
   .venv\Scripts\activate #windows

5. **Configure o Ambiente no Editor de Código (VSCode)**:
   
   Ctrl+Shift+P
   Digite "Python: Select Interpreter".
   selecione o ambiente virtual na pasta do projeto que começa com ./.venv ou .\.venv

6. **Atualize o Gerenciador de Pacotes (pip)**
   ```bash
    python -m pip install --upgrade pip


7.**Instale o Django no ambiente virtual**
    ```bash
   python -m pip install django

8.**Crie o Projeto Django**
   ```bash
   django-admin startproject (nome_do_seu_projeto)

9.**Aplique as migrações no banco de dados**:
   ```bash
   python manage.py makemigrations

   ```bash
   python manage.py migrate

10. **Execute o servidor de desenvolvimento**:
   ```bash
   python manage.py runserver

11. **Execute o servidor de desenvolvimento**:
   Abra o navegador e acesse:
   http://127.0.0.1:8000/


## **Como Utilizar o Sistema**

**Página Inicial (Home)**:
        Acesse as funcionalidades principais do sistema.

**Registrar Novo Ingrediente**:
        Preencha o formulário com o nome do ingrediente e a quantidade inicial.
        O ingrediente que não existia é adicionado no banco de dados

**Procurar Ingrediente**:
        Informe o nome do ingrediente para verificar a quantidade disponível no estoque.

**Atualizar Ingrediente**:
        Preencha o formulário com o nome do ingrediente e a quantidade inicial.
        É atualizado o valor da quantidade de ingredientes no banco de dados

**Remover Ingrediente**:
        Informe o nome do ingrediente e a quantidade a ser removida.
        Caso o estoque chegue a zero, o sistema exibirá uma mensagem de alerta.


Autores

    Bruno Kazuya
    Douglas Pereyra
    Henrique Zucoloto
    Renato Calacina
