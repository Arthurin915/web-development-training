# Projeto: To-Do-List
Projeto simples para aprendizado de JavaScript puro (ou algum framework, caso já esteja familiarizado com JS puro).

### Lista de Tarefas Simples (front-end):
- Criar uma interface para criar tarefas com um input para descrevê-la e um botão de adicionar
- Listar as tarefas adicionadas permitindo editá-las ou removê-las
- Não é possível adicionar tarefas com a mesma descrição
- Estilização fica a seu critério, aproveite para ampliar seus conhecimentos em CSS
- Pode-se usar as tecnologias que preferir, contanto que o HTML seja semântico, seguindo estrutura do HTML5.

Após finalizar o front-end, você deverá criar um back-end e um banco de dados para persistir as tarefas criadas.

### Lista de Tarefas Simples (back-end)
- Criar uma api REST utilizando .NET
- Poder ler, criar, editar e deletar tarefas no banco de dados (CRUD)
- SGBD fica a seu critério, pode-se usar in memory, banco local ou como preferir. Aproveite para se desafiar.
- Estruturar sua api utilizando Repository pattern
- Criar queries para o banco de dados utilizando Dapper ou ADO.NET

### Integrar front-end e back-end
- Ler tarefas criadas ao abrir a página
- Modificar lógica de criação, atualização e remoção de tarefas para utilizar a API criada
- Os dados devem ser persistidos no banco de dados, ao recarregar a página deve-se recuperar os dados salvos


Exemplo: 

<img src="images/to-do-list-00.png">

Imagem meramente ilustrativa, estilize a página do jeito que preferir.


### Desafios extras:
- Possibilidade de marcar tarefa como concluída
- Criar repositório utilizando Entity Framework ao invés de dapper/ado.net para as queries
- Criar categorias ao inserir tarefas
