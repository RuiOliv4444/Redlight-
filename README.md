# Projeto de Gestão de Restaurantes e Francesinhas

## Introdução

Este projeto tem como objetivo desenvolver uma aplicação web para gestão de restaurantes e francesinhas, utilizando o framework Django. A aplicação permite registrar, listar, atualizar e deletar informações sobre restaurantes e francesinhas, além de possibilitar a busca e ordenação desses itens. O projeto visa proporcionar uma interface intuitiva e eficiente para gerenciamento desses dados, facilitando a administração e visualização das informações.

## Instalação das Ferramentas Requeridas

Para executar este projeto, é necessário ter o Python e o Django instalados no seu ambiente de desenvolvimento. Siga os passos abaixo para a instalação:

### Instalação do Python
- Baixe e instale a versão mais recente do Python a partir do site oficial: [Python Downloads](https://www.python.org/downloads/).
- Após a instalação, verifique se o Python foi instalado corretamente executando o seguinte comando no terminal:
  ```bash
  python --version

##Instalação do Django
-Instale o Django utilizando o pip, que é o gerenciador de pacotes do Python. Execute o seguinte comando no terminal:
  ```bash
  pip intall django
```
##Configuração e Execução do Projeto

Após a instalação das ferramentas, siga o passo abaixo para configurar e executar o projeto:
- Navegue até o diretório do projeto
  ```bash
  cd red_project
```
Aplicação das migrações do Django
Antes de iniciar o servidor, é necessário aplicar as migrações para criar as tabelas no banco de dados. Execute o comando:
  ```bash
  python manage.py migrate
```
##Execução do servidor Django
-Inicie o servidor Django para acessar a aplicação. Utilize o comando:

##População da Base de Dados
-Caso a base de dados ainda não esteja carregada, é necessário executar o script populate_db.py para adicionar os dados iniciais. Execute o seguinte comando no terminal:
  ```bash
  python populate_db.py
```
Após seguir esses passos, a aplicação estará disponível e pronta para uso. Acesse o servidor local através do navegador utilizando o endereço padrão http://127.0.0.1:8000/.
