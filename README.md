📝 Roteiro da Atividade: Levantamento de Requisitos – Connexa (Etapa 1)
🎯 Objetivo da Atividade
Realizar o levantamento de requisitos a partir de um cenário fictício, organizando-os em user stories com critérios de aceitação bem definidos e criando um backlog de produto utilizando o Azure DevOps Boards.

📌 Cenário Fictício
Produto: Connexa

Problema: Alunos universitários têm dificuldade em encontrar colegas para formar grupos de estudo. O processo atual é desorganizado e pouco eficiente (grupos de WhatsApp, murais físicos, etc.).
Solução Proposta: Uma plataforma web para criar, buscar e participar de grupos de estudo de forma estruturada.
Cada grupo deve possuir, no mínimo: matéria, objetivo (ex: prova, projeto), local (online/presencial) e um limite de participantes.
👥 Organização da Atividade
Grupos de Trabalho: 3 a 5 alunos.
Ferramenta Principal: Azure DevOps Boards → Para criação do backlog e gestão das user stories.
🚀 Criação do Backlog (User Stories)
O objetivo desta etapa é traduzir as necessidades do produto Connexa em um backlog funcional. O backlog é uma lista priorizada de funcionalidades que guiará o desenvolvimento futuro do projeto.

🔹 Parte 1: Acessando o Azure Boards
Para iniciar a atividade, é necessário que um integrante do grupo crie a organização e o projeto no Azure DevOps. O acesso pode ser feito diretamente com a sua conta institucional.

Instruções de Acesso:

Acesse o site do Azure DevOps: https://aex.dev.azure.com/.
Clique em "Start free" (Começar gratuitamente).
Na tela de login da Microsoft, utilize suas credenciais institucionais (o mesmo e-mail e senha que você usa para acessar o Teams, Outlook, etc.).
Após o login, o sistema pode pedir para confirmar alguns detalhes. Prossiga para criar sua Organização (sugestão: NomeDaSuaFaculdade-SuaTurma) e seu primeiro Projeto.
Ao criar o projeto, dê um nome a ele (ex: Connexa-Grupo01), mantenha a visibilidade como "Private" (Privado) e, nas configurações avançadas, selecione o processo "Agile" em Work item process.
Após a criação, navegue até a seção "Boards" > "Backlogs" no menu lateral esquerdo. É aqui que vocês irão criar e gerenciar suas User Stories.
🔹 Parte 2: Estrutura e Criação das User Stories
Cada funcionalidade do produto deve ser descrita como uma User Story, seguindo o modelo padrão para garantir clareza e foco no valor para o usuário.

Modelo da User Story
Como um [tipo de usuário], eu quero [realizar uma ação] para que eu possa [alcançar um benefício].
Exemplo Detalhado de User Story com Critérios de Aceitação
A seguir, um exemplo completo de como uma User Story deve ser documentada no Azure DevOps.

📌 User Story: Cadastro de Usuário (titulo)
Descrição:

Como um aluno universitário,
eu quero me cadastrar na plataforma Connexa usando meu e-mail institucional,
para que eu possa criar, buscar e participar de grupos de estudo com segurança e legitimidade.

Critérios de Aceitação:

✅ O formulário de cadastro deve conter os campos: nome completo, e-mail institucional, curso, período/semestre e senha.
✅ O sistema deve validar que o e-mail informado pertence ao domínio da universidade .
✅ A senha deve ter no mínimo 8 caracteres, contendo pelo menos uma letra maiúscula, uma minúscula e um número.
✅ O sistema não deve permitir o cadastro de um e-mail que já exista na base de dados.
✅ Mensagens de erro claras devem ser exibidas caso algum campo seja preenchido incorretamente (ex: "O e-mail informado não é um e-mail institucional válido").
✅ Após o preenchimento correto dos dados, o usuário deve ser redirecionado para uma página de sucesso ou para a tela de login.
✅ Um e-mail de confirmação de cadastro deve ser enviado para o endereço informado.
Prioridade: Alta

📍 Ponto de Verificação e Requisitos da Atividade
O backlog do projeto no Azure DevOps deve conter no mínimo 6 a 10 user stories relevantes para o produto Connexa.
Cada user story deve possuir critérios de aceitação claros e testáveis (mínimo de 2 critérios por story).
As stories devem ser priorizadas (arraste e solte as stories na ordem de importância no backlog).
✅ Critérios de Entrega (Via Microsoft Teams)
A entrega da atividade deverá ser feita através da aba "Tarefas" no Microsoft Teams, contendo os seguintes itens:

URL do Projeto no Azure DevOps:

No painel do seu projeto, copie a URL completa do navegador. Certifique-se de que os instrutores foram convidados para a sua organização para que possam visualizar o backlog.
Para convidar um usuário: vá em "Organization Settings" > "Users" > "Add users".
Cópia de Tela (Screenshot) do Backlog:

Tire uma cópia de tela nítida da sua tela de "Boards" > "Backlogs" no Azure DevOps, mostrando a lista de User Stories criadas, priorizadas.
📖 Referências e Recursos Adicionais
Para aprofundar seus conhecimentos sobre a criação de requisitos ágeis e o uso do Azure Boards, consulte os materiais abaixo:

Documentação Oficial:

Microsoft Learn: Introdução ao Azure Boards
Microsoft Learn: Criar seu Backlog no Azure Boards
Guias sobre User Stories:

Atlassian Agile Coach: Guia completo sobre User Stories
Vídeos Tutoriais:

YouTube: Azure DevOps - Plan your work with Azure Boards (em inglês)
