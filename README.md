# login-cad
🚀 README
📜 DESCRIÇÃO

Este projeto é um sistema básico para login e cadastro de usuários, composto por uma página de login e uma página de cadastro. A interação é gerenciada com JavaScript, e o estilo é definido com CSS e Bootstrap.

🗂 ESTRUTURA DO PROJETO

1. Página de Login (login.html)
A página de login permite que os usuários insiram e-mail, senha e CPF. Caso todos os campos sejam preenchidos corretamente, o usuário é redirecionado para a página de cadastro.

🎯FUNCIONALIDADES

Campos do Formulário:

E-mail (loginEmail)
Senha (loginSenha)
CPF (loginCpf)
Botão "ACESSAR":

Aciona a função acessar() ao ser clicado.

🔧 FUNÇÃO AO ACESSAR()

Propósito: Verifica se todos os campos (e-mail, senha e CPF) estão preenchidos.
Funcionamento:
Obtém os valores dos campos de e-mail, senha e CPF.
Se algum campo estiver vazio, exibe um alerta solicitando o preenchimento dos campos.
Se todos os campos estiverem preenchidos, redireciona para cadastro.html.

2. Página de Cadastro (cadastro.html)
A página de cadastro permite inserir nome, e-mail e CPF, e exibe uma tabela com os usuários cadastrados, oferecendo opções para edição e exclusão de registros.

📋 Funções do JavaScript
Arrays de Dados:

dadosLista: Armazena os nomes dos usuários.
EmailLista: Armazena os e-mails dos usuários.
cpfLista: Armazena os CPFs dos usuários.
Função salvarUser():

Propósito: Adiciona um novo usuário à lista e atualiza a tabela.
Funcionamento:
Obtém os valores dos campos de nome, e-mail e CPF.
Verifica se todos os campos estão preenchidos e se o CPF é válido.
Adiciona os dados às listas e chama a função criarLista() para atualizar a tabela.
Limpa os campos após o salvamento.
Função criarLista():

Propósito: Cria e atualiza a tabela exibida na tela.
Funcionamento:
Gera o cabeçalho da tabela.
Itera sobre as listas de dados e cria linhas para cada usuário.
Atualiza o conteúdo da tabela com as novas informações.
Função editar(i):

Propósito: Permite a edição de um registro existente.
Funcionamento:
Preenche os campos de entrada com os dados do usuário selecionado para edição.
Remove o usuário da lista para evitar duplicação.
Função excluir(i):

Propósito: Remove um usuário da lista.
Funcionamento:
Remove o usuário das listas de dados, e-mail e CPF.
Atualiza a tabela para refletir a exclusão.
Função validarEmail():

Propósito: Valida se o e-mail inserido é válido.
Funcionamento:
Verifica se o e-mail contém @ e ..
Exibe um alerta caso o e-mail seja inválido.
Função validarCPF(cpf):

Propósito: Valida o CPF fornecido.
Funcionamento:
Remove caracteres não numéricos do CPF.
Verifica o comprimento e se todos os dígitos são iguais.
Valida os dígitos verificadores do CPF.
Exibe um alerta se o CPF for inválido e retorna false. Retorna true se o CPF for válido.

📋 REQUISITOS

Navegador moderno com suporte a HTML, CSS e JavaScript.
Conexão com a Internet para carregar o Bootstrap a partir da CDN.

 🚀COMO USAR

Abrir a Página de Login: Acesse login.html em um navegador.
Preencher o Formulário de Login: Insira e-mail, senha e CPF. Clique no botão "ACESSAR" para ser redirecionado para a página de cadastro.
Usar a Página de Cadastro: Em cadastro.html, preencha os campos e salve os dados. Use os botões para editar ou excluir registros na tabela.
Se precisar de mais ajustes ou informações adicionais, é só me avisar!




