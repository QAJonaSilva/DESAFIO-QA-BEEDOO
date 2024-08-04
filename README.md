# Desafio-QA-Beedoo

## PROJETO: Cadastrar e Listar Cursos

# ********** User story **********

Como um usuário
Eu quero cadastrar e listar cursos
Para que eu possa gerenciar os cursos oferecidos pela minha instituição
E ter acesso às informações relevantes de cada curso


# ********** Cenários levantados para validação **********

1- Cadastrar um novo Curso

- O Usuário pode inserir o "Nome do curso", "Descrição do curso", "URL da imagem da capa", "Instrutor", 
"Data de início", "Data fim", "Número de vagas" e o "Tipo de curso" (Presencial ou online).

- O sistema deve validar os dados inseridos, garantindo que todos os campos obrigatórios sejam 
preenchidos e que as datas sejam válidas

- Após a validação, o sistema deve salvar o novo Curso no banco de dados

2- Listar os Cursos cadastrados

- O Usuário poderá visualizar uma lista com todos os cursos cadastrados.

- A lista deve apresentar "Nome do curso", "Instrutor", "Data de início", "Data fim", "Número de vagas"
e o "Tipo de curso" (Presencial ou online).

- O Usuário poderá filtrar a lista de cursos por "Nome do curso", "Instrutor", "Data de início", "Data fim" ou
"Tipo de curso" (Presencial ou online).

- O Usuário poderá visualizar detalhes de um curso especifico ao clicar em seu Nome

- O Usuário deve conseguir excluir curso através do botão "EXCLUIR CURSO"


