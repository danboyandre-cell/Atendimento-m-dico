# 🏥 Sistema de Atendimento Médico

Aplicação desenvolvida no **Bubble.io**, com o objetivo de facilitar o gerenciamento de atendimentos médicos, agendamentos, pacientes e profissionais da saúde.

O sistema possui controle de acesso por perfil de usuário, garantindo que médicos e recepcionistas tenham permissões específicas de acordo com suas responsabilidades.

## 🔐 Autenticação e Controle de Acesso

O sistema utiliza autenticação e cadastro por meio de tokens de autorização.

Para realizar o primeiro cadastro, o usuário precisa solicitar um token ao seu superior. Existem dois tipos de tokens:

- **Token para recepcionistas:** utilizado para autorizar o cadastro de novos recepcionistas.
- **Token para médicos e dentistas:** utilizado para autorizar o cadastro de profissionais da saúde.

Cada perfil possui permissões específicas, garantindo que os usuários acessem somente as funcionalidades correspondentes à sua função.

## 👥 Perfis de Usuário e Permissões

### Recepcionista
- Cadastrar, consultar, editar e excluir pacientes.
- Criar e gerenciar horários de atendimento dos médicos.
- Realizar agendamentos de consultas.
- Cadastrar usuários médicos e dentistas.

### Médico
- Visualizar exclusivamente seus próprios agendamentos.
- Consultar os pacientes relacionados aos seus atendimentos.
- Realizar o atendimento dos pacientes cadastrados.
- Consultar históricos de atendimentos e informações clínicas dos pacientes sob sua responsabilidade.

## 📸 Demonstração das Telas

### 🔐 Tela de Login
Página inicial de autenticação, onde os usuários acessam o sistema utilizando suas credenciais.

![Tela de Login](./screenshots/tela%20login.png)

### 🎟️ Token para Fazer Cadastro
Tela destinada à validação do token de autorização, necessário para permitir o cadastro de novos usuários no sistema.

![Token para Cadastro](./screenshots/token%20para%20fazer%20cadastro.png)

### 👤 Cadastro de Colaborador
Formulário para cadastrar novos colaboradores, como recepcionistas, permitindo o acesso ao sistema conforme as permissões atribuídas ao perfil.

![Cadastro de Colaborador](./screenshots/tela%20cadastro%20colaborador.png)

### 🩺 Cadastro de Médico
Tela destinada ao cadastro de médicos e dentistas, permitindo registrar profissionais que utilizarão o sistema.

![Cadastro de Médico](./screenshots/tela%20cadastro%20medico.png)

### ➕ Adicionar Médico
Tela utilizada pela recepcionista para adicionar médicos ao sistema.

![Adicionar Médico](./screenshots/tela%20adicionar%20medico.png)

### 👥 Cadastro de Pacientes
Tela para cadastrar e gerenciar as informações dos pacientes atendidos pelo estabelecimento.

![Cadastro de Pacientes](./screenshots/cadastro%20paciente.png)

### 📝 Pop-up de Cadastro de Paciente
Janela utilizada para inserir as informações necessárias durante o cadastro de um novo paciente.

![Pop-up Cadastrar Paciente](./screenshots/pop-up%20cadastrar%20paciente.png)

### ✏️ Pop-up de Edição de Paciente
Janela que permite atualizar as informações de pacientes já cadastrados.

![Pop-up Editar Paciente](./screenshots/pop-up%20editar%20paciente.png)

### 🗑️ Confirmação de Exclusão de Paciente
Mensagem de confirmação apresentada antes de excluir o cadastro de um paciente, evitando exclusões acidentais.

![Confirmação de Exclusão](./screenshots/mensagem%20confirmar%20excluir%20paciente.png)

### 📅 Calendário de Agendamentos
Calendário utilizado para visualizar a organização dos agendamentos e os horários disponíveis para atendimento.

![Calendário de Agendamentos](./screenshots/calendario%20agendamento.png)

### 🗓️ Tela de Agendamento
Tela destinada ao gerenciamento dos agendamentos, relacionando pacientes e profissionais da saúde.

![Tela de Agendamento](./screenshots/tela%20agendamento.png)

### ⏰ Cadastro de Horários
Tela utilizada para configurar os horários de atendimento dos médicos, permitindo organizar sua disponibilidade.

![Tela de Horários](./screenshots/tela%20horarios.png)

### ➕ Pop-up de Novo Horário
Janela utilizada para adicionar um novo horário de atendimento à agenda do profissional.

![Pop-up Novo Horário](./screenshots/pop-up%20novo%20horario.png)

### 🩺 Horários do Usuário Médico
Tela destinada à visualização e organização dos horários de atendimento vinculados ao médico.

![Horários do Médico](./screenshots/tela%20horario%20usuario%20medico.png)

### ✏️ Pop-up de Edição de Agendamento
Janela utilizada para editar informações de um agendamento existente.

![Editar Agendamento](./screenshots/popup%20editar%20agendamento.png)

### 📋 Histórico de Atendimentos
Tela destinada à consulta dos atendimentos realizados, permitindo acompanhar o histórico de consultas.

![Histórico de Atendimento](./screenshots/historico%20atendimento.png)

### 🗂️ Histórico Clínico
Tela destinada à consulta das informações clínicas e do histórico dos pacientes, auxiliando o profissional durante o acompanhamento médico.

![Histórico Clínico](./screenshots/historico%20clinico.png)

### 👨‍⚕️ Histórico do Usuário Médico
Tela relacionada ao histórico do médico no sistema, permitindo visualizar informações vinculadas ao seu perfil.

![Histórico do Médico](./screenshots/usuario%20medico%20historico.png)

## 🛠️ Tecnologia Utilizada

- Bubble.io — desenvolvimento da aplicação utilizando a plataforma No-Code.

## 🎯 Objetivo do Projeto

Desenvolver um sistema para otimizar a rotina de atendimento médico, facilitando o gerenciamento de pacientes, profissionais, horários e consultas, com controle de acesso baseado nas funções de cada usuário.
