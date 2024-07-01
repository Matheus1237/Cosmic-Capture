# Galeria de Fotos do Espaço
Este é um projeto desenvolvido em Django que permite aos usuários criar, visualizar, editar e excluir imagens relacionadas ao espaço sideral. Além das funcionalidades básicas de CRUD (Create, Read, Update, Delete) de imagens, o sistema também inclui autenticação de usuários para garantir a segurança e privacidade das informações.

## Funcionalidades Principais
### Autenticação de Usuários:

Registro e login de usuários para acessar o sistema.
### CRUD de Imagens:

Criar: Adicionar novas imagens à galeria.
Ler: Visualizar detalhes e thumbnails das imagens existentes.
Atualizar: Modificar informações ou substituir imagens já cadastradas.
Excluir: Remover imagens que não são mais necessárias.
### Galeria de Fotos Responsiva:

Interface amigável que se adapta a diferentes tamanhos de tela.

## Instalação

### Clone o repositório:
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

### Crie um ambiente virtual e instale as dependências:
python -m venv venv
source venv/bin/activate   # No Windows use `venv\Scripts\activate`
pip install -r requirements.txt

### Configure o banco de dados no arquivo settings.py conforme sua preferência (por exemplo, SQLite para desenvolvimento).

### Execute as migrações do Django para aplicar as alterações no banco de dados:
python manage.py migrate

### Inicie o servidor de desenvolvimento:
python manage.py runserver

### Acesse o projeto no seu navegador!

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
