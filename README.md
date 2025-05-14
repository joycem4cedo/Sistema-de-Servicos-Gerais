# 🛠️ SSG - Sistema de Serviços Gerais

Em 2024, atuei como **Scrum Master** no desenvolvimento do **SSG**, um sistema web criado para conectar prestadores de serviços domésticos (como encanadores, diaristas, eletricistas, entre outros) com clientes que necessitam desses serviços. O projeto foi realizado sob orientação do professor **Daniel Vidal** e fez parte das atividades práticas do curso técnico em desenvolvimento de sistemas.

## 👥 Papel no Projeto

Como Scrum Master, fui responsável por facilitar a comunicação entre os integrantes da equipe, remover impedimentos, garantir a organização e entrega contínua das funcionalidades do sistema e manter os princípios ágeis durante todas as etapas do projeto. Também contribuí ativamente no acompanhamento técnico e na integração entre as áreas de front-end, back-end e banco de dados.

## 🔍 Visão Geral

O SSG permite que prestadores registrem seus serviços e disponibilizem horários. Clientes podem agendar serviços diretamente pela plataforma. Um sistema de notificações permite que prestadores aceitem ou recusem os pedidos, e os clientes recebem a resposta automaticamente.

### 🎯 Funcionalidades principais

- Cadastro e login de clientes e prestadores
- Criação e listagem de serviços
- Agendamento com controle de status: Pendente, Aceito ou Negado
- Histórico de serviços prestados com avaliações
- Sistema de notificação (resposta de agendamento)
- Estrutura de herança no banco de dados (cliente/prestador)

## 💻 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript  
- **Backend**: PHP (procedural)  
- **Banco de Dados**: MySQL  
- **Servidor**: Apache (XAMPP/WAMP)

## 🧠 Modelagem do Banco de Dados

O banco de dados relacional foi modelado com relações entre `cliente`, `prestador`, `servicos`, `agendamentos` e `servicos_prestados`, aplicando conceitos de herança e integridade referencial.

### Principais Tabelas

- `cliente`: informações de autenticação
- `prestador`: especialização associada ao cliente
- `servicos`: serviços disponíveis
- `agendamentos`: gestão de horários e status
- `servicos_prestados`: histórico e avaliação de serviços

📂 O script do banco de dados está incluído neste repositório: [`ssg.sql`](./ssg.sql)

## 🔄 Metodologia

O desenvolvimento seguiu os princípios do Scrum, com:

- Reuniões semanais (weekly Scrums)
- Backlog de produto organizado
- Divisão em sprints
- Entregas incrementais com foco na funcionalidade central
- Feedback contínuo e retrospectivas

---

📌 O SSG foi uma experiência significativa em desenvolvimento colaborativo, gestão de time e aplicação prática de metodologias ágeis em um ambiente real de projeto.
