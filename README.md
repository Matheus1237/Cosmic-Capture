# Galeria de Fotos do Espaço
Este é um projeto desenvolvido em Django que permite aos usuários 1.Criar, 2.Visualizar, 3.Editar e 4.Excluir imagens relacionadas ao espaço sideral. Além das funcionalidades básicas de CRUD (Create, Read, Update, Delete) de imagens, o sistema também inclui autenticação de usuários para garantir a segurança e privacidade das informações.

## Funcionalidades Principais
### Autenticação de Usuários:

Registro e LOGIN de usuários para acessar o sistema.
### CRUD de Imagens:

1.Criar: Adicionar novas imagens à galeria.
2.Ler: Visualizar detalhes e thumbnails das imagens existentes.
3.Atualizar: Modificar informações ou substituir imagens já cadastradas.
4.Excluir: Remover imagens que não são mais necessárias.
### Galeria de Fotos Responsiva:

Interface amigável que se adapta a diferentes tamanhos de tela.

## Instalação

### 1.Clone o repositório:
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

### 2.Crie um ambiente virtual e instale as dependências:
python -m venv venv
source venv/bin/activate   # No Windows use `venv\Scripts\activate`
pip install -r requirements.txt

### 3.Configure o banco de dados no arquivo settings.py conforme sua preferência (por exemplo, SQLite para desenvolvimento).

### 4.Execute as migrações do Django para aplicar as alterações no banco de dados:
python manage.py migrate

### 5.Inicie o servidor de desenvolvimento:
python manage.py runserver

### 6.Acesse o projeto no seu navegador!

## Tecnologias Utilizadas
Python
Django
HTML/CSS
JavaScript
Bootstrap
SQL

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou relatar problemas na página de issues do projeto.

## Licença
Este projeto está licenciado sob a Licença MIT.
