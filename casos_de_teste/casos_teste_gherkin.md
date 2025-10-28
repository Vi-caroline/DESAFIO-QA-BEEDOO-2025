
Funcionalidade: Gerenciamento de Cursos

  Cenário: Criar curso com sucesso
    Dado que o usuário administrador está logado
    E acessa o módulo de cursos
    Quando ele preenche o formulário com nome, descrição e imagem
    E clica no botão salvar
    Então o sistema deve criar o curso e listar na página principal

  Cenário: Criar curso com campos obrigatórios vazios
    Dado que o usuário está na tela de criação de curso
    Quando ele tenta salvar sem preencher os campos obrigatórios
    Então o sistema deve exibir mensagens de erro para cada campo vazio
