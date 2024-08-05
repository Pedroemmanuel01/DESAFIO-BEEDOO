# Desafio Beedoo

Este repositório contém o projeto do Desafio Beedoo, que consiste na análise e criação de cenários e casos de teste para o módulo de cursos do sistema Beedoo.

## User Story

**Título:** Gerenciamento de Cursos no Módulo Beedoo

Como um usuário do sistema Beedoo,
Eu quero ser capaz de criar, listar e excluir cursos,
Para que eu possa gerenciar o catálogo de cursos oferecidos pela instituição.

### Critérios de Aceitação

#### Criação de Curso:

- O usuário deve poder acessar uma página de criação de curso.
- O usuário deve poder preencher todos os campos obrigatórios (Nome do Curso, Descrição, Instrutor, URL da Imagem de Capa, Data de Início, Data de Fim, Número de Vagas e Tipo de Curso).
- Ao clicar no botão "Cadastrar curso", o sistema deve validar os dados e, em caso de sucesso, exibir a mensagem "Curso cadastrado com sucesso" e adicionar o curso à lista de cursos.

**Validações:**

- A Data de Fim deve ser posterior à Data de Início.
- O Ano deve ser composto por 4 dígitos.
- O Número de Vagas deve ser um valor positivo.
- Todos os campos obrigatórios devem ser preenchidos.

#### Listagem de Cursos:

- O usuário deve poder acessar uma página que lista todos os cursos cadastrados.
- A lista deve exibir o Nome do Curso, Descrição, Data de Início, Data de Fim, Número de Vagas e um botão para excluir o curso.

#### Exclusão de Curso:

- O usuário deve poder excluir um curso existente clicando no botão "Excluir" correspondente ao curso.
- Ao excluir um curso, o sistema deve exibir a mensagem "Curso excluído com sucesso" e remover o curso da lista.

### Decisões Tomadas para Criar a User Story

#### Análise de Requisitos

Foram analisados os requisitos do módulo de cursos do Beedoo Chalenge, levando em consideração as funcionalidades principais oferecidas: criação, listagem e exclusão de cursos. Identificamos os campos necessários para a criação de um curso e os critérios de validação para garantir a integridade dos dados.

#### Criação da User Story

A user story foi elaborada para cobrir os três principais fluxos do módulo de cursos:

- Criação de Curso
- Listagem de Cursos
- Exclusão de Curso

#### Critérios de Aceitação

Foram definidos critérios de aceitação claros e objetivos para cada funcionalidade, garantindo que todas as validações necessárias fossem contempladas. As mensagens de sucesso e erro foram especificadas para proporcionar um feedback adequado ao usuário.

### Cenários e Casos de Teste

Os cenários e casos de teste foram detalhados para cobrir tanto os casos de sucesso quanto os de erro, incluindo fluxos de exceção e validação de dados. Utilizamos a linguagem Gherkin para descrever os casos de teste de forma clara e padronizada, facilitando a automação futura e a comunicação entre as partes envolvidas.

### Planilha de Casos de Teste

Todos os cenários e casos de teste foram documentados em uma planilha no Google Docs, com link disponibilizado a seguir: [Planilha de Casos de Teste](https://docs.google.com/spreadsheets/d/17pFm0KkfXbkDZoSLFmxVFVWIHrR38459hZLodnTANTA/edit?usp=drive_link).

Na planilha constam três páginas: **Casos de Teste**, **Melhorias** e **Controle de Bugs**.

### Evidências de Teste

As evidências de teste foram geradas em formato MP4 e armazenadas no Google Drive, com links adicionados a seguir:

- [Controle de Bugs](https://drive.google.com/drive/folders/1cp1x809CQWy0Zk-NsP3TGg2XT5fa-k-u?usp=drive_link)
- [Evidências de Testes](https://drive.google.com/drive/folders/1T7u77-u4rgufVmKPzoYBqinU4r3loN4v?usp=drive_link)

### Organização do Repositório

O repositório foi organizado para conter todas as informações necessárias para a avaliação do desafio, incluindo a documentação da user story, os casos de teste, as evidências de teste e os links para os documentos no Google Docs e Drive.

### Teste não Validado

Teste relacionado ao numero limite de caracteres por campo, com base nesse teste surgiu a melhoria e duvida ao desenvolvedor quanto a quantidade maxima em cada campo.
