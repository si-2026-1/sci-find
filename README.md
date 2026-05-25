# sci-find

Ferramenta de busca e gerenciamento de pesquisa e extensão.

# Problema

Atualmente, a divulgação e gerenciamento de eventos e projetos universitários ocorre de forma descentralizada, utilizando diferentes canais como redes sociais, murais físicos, e-mails institucionais ou comunicação informal.

Como consequência:

- Muitos alunos não ficam sabendo de eventos relevantes.
- Projetos acadêmicos têm baixa adesão de participantes.
- Informações importantes se perdem ou não chegam ao público-alvo.
- Inscrições, emissões de certificado e candidatura de voluntários são ineficientes.

A falta de centralização prejudica tanto organizadores quanto interessados, criando uma lacuna na comunicação e engajamento da universidade.

# Escopo

O sistema será direcionado para a comunidade acadêmica, incluindo:

- **Alunos**: poderão buscar, acompanhar e participar de eventos e projetos.
- **Professores**: poderão criar, divulgar e gerenciar eventos e projetos.
- **Interessados externos (opcional)**: dependendo da política da instituição, poderão visualizar eventos abertos ao público.

Inicialmente, o sistema será voltado para uso interno universitário, com futura possibilidade de expansão.

# Requisitos

## Funcionalidades

- Centralização de postagens relacionadas a eventos e projetos acadêmicos;
- Criação e gerenciamento de eventos/projetos por professores ou organizadores;
- Sistema de interesse/participação:
  - Usuário pode demonstrar interesse em um evento;
  - Caso vagas estejam esgotadas, o usuário pode entrar em lista de espera;

- Notificações inteligentes:
  - Avisos sobre abertura de vagas;
  - Atualizações do evento/projeto;
  - Lembretes próximos à data do evento.

## Interação do usuário

- Usuários poderão:
  - Explorar eventos por categorias;
  - Visualizar as informações gerais sobre evento ou projeto;
  - Filtrar por data, área de interesse ou tipo de atividade;
  - Salvar eventos de interesse.

## Sistema de perfis

- Integração com o sistema acadêmico (ex: SIGAA);
- Inscrição em evento utilizando o perfil de usuário;
- Candidatura para a organização/produção de evento ou projeto utilizando o perfil de usuário;
- Visualização de:
  - Perfil do organizador;
  - Informações do participante (para validação, por parte do organizador, de candidatura para a organização/produção de evento ou projeto).

## User Stories

- Eu como usuário quero poder criar um perfil, integrando com o Sigaa, para que eu possa pegar meu histórico de disciplinas e meus dados pessoais.
- Eu, como usuário, quero receber lembretes 1 dia antes de um evento que me inscrevi ou que estou organizando, para não esquecer a data.

- Eu como professor quero poder manipular eventos para que os alunos possam participar.
- Eu como professor quero poder pegar as informações dos inscritos para que depois que terminar a inscrição dos eventos notifica-los sobre as próximas etapas.
- Eu como professor quero definir os requisitos para que saibam que tipos de participantes eu busco para apoiar meu evento para que eu consiga selecionar colaboradores mais alinhados com as necessidades da minha atividade.

- Eu como aluno quero poder ter acesso a uma agenda que marcará todas as minhas atividades que quero participar para que eu possa organizar minha rotina acadêmica e não perder prazos importantes.
- Eu, como aluno, quero me candidatar para ser colaborador de um evento, para ajudar na produção e ganhar horas complementares.
- Eu como aluno quero poder ser notificado caso haja qualquer tipo de alteração nos eventos que irei participar, e também, se eu quiser ajudar em um evento lotado, receber uma notificação caso abra uma vaga para ajudar, assim eu posso ficar sempre atualizado posso ter chance de participar mesmo quando o evento estiver cheio.

## Requisitos Não Funcionais

- Integridade: O sistema deve garantir a exatidão sobre os dados, independentemente de qualquer alteração.
- Usabilidade: O sistema deve ser fácil aos usuários interagirem, isso significa, ter componentes bem explicados, design responsível e acessibilidade
- Desempenho: O sistema deve suportar 1000 usuários simultâneos sem degradação significativa.

# Detalhes do Produto

## Aplicativo sci-find

O sci-find será um aplicativo que contará com versões mobile e web voltado para a divulgação e gerenciamento de eventos e projetos acadêmicos.

## Funcionalidades adicionais

### Calendário integrado

- Permite ao usuário visualizar eventos em formato de calendário;
- Possibilidade de adicionar eventos de interesse automaticamente;
- Envio de lembretes com base nas datas cadastradas.

### Sistema de notificações

- Notificações em tempo real sobre:
  - Atualizações de eventos;
  - Mudanças de status (ex: vagas abertas/encerradas);
  - Novos eventos relacionados aos interesses do usuário.

### Criação de páginas de eventos

- Organizadores poderão:
  - Criar páginas com informações e detalhes sobre o evento/projeto;
  - Definir requisitos para a candidatura para a organização/produção do evento;
  - Definir número máximo de inscritos/participantes;
  - Definir requisitos para a certificação de participantes inscritos.

### Integração com SIGAA

- Autenticação utilizando dados institucionais;
- Garantia de confiabilidade das informações dos usuários;
- Facilidade na identificação entre organizadores e participantes.

## Diferenciais do sistema

- Centralização de informações acadêmicas relacionadas à envetos/projetos;
- Melhor comunicação entre alunos, professores e instituições de ensino;
- Aumento na participação e produção de eventos/projetos acadêmicos;
- Experiência personalizada baseada em interesses do usuário;
- Ampliação da oferta de candidatos para a produção acadêmica.

# Membros

- Heitor de Mattos - 211055281
- Pedro Vale de Souza - 231038733
- Arthur Arruda Frauches -241017728
