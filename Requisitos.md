# Requisitos
Aqui estão listados os requisitos especificados para o aplicativo sci-find com base no problema e escopo.

## Funcionalidades gerais

- **RFG-01** Centralização de postagens relacionadas a eventos e projetos acadêmicos;
- **RFG-02** Criação de eventos/projetos por professores ou organizadores;
- **RFG-03** Gerenciamento de eventos/projetos por professores ou organizadores;
- **RFG-04** Sistema de interesse/participação:
  
  - **RFG-04.1** Usuário pode demonstrar interesse em um evento;
  - **RFG-04.2** Caso vagas estejam esgotadas, o usuário pode entrar em lista de espera;
    
- **RFG-05** Notificações inteligentes:
  
  - **RFG-05.1** Avisos sobre abertura de vagas;
  - **RFG-05.2** Atualizações do evento/projeto;
  - **RFG-05.3** Lembretes próximos à data do evento.

## Interação do usuário

- **RFIU-01** Usuários poderão:
  
  - **RFIU-01.1** Explorar eventos por categorias;
  - **RFIU-01.2** Visualizar as informações gerais sobre evento ou projeto;
  - **RFIU-01.3** Filtrar por data, área de interesse ou tipo de atividade;
  - **RFIU-01.4** Salvar eventos de interesse.

## Sistema de perfis

- **RFSP-01** Integração com o sistema acadêmico (ex: SIGAA);
- **RFSP-02** Inscrição em evento utilizando o perfil de usuário;
- **RFSP-03** Candidatura para a organização/produção de evento ou projeto utilizando o perfil de usuário;
- **RFSP-04** Visualização de:
  
  - **RFSP-04.1** Perfil do organizador;
  - **RFSP-04.2** Informações do participante (para validação, por parte do organizador, de candidatura para a organização/produção de evento ou projeto).

# Requisitos Não Funcionais
- **RNF-01** Integridade: O sistema deve garantir a exatidão sobre os dados, independentemente de qualquer alteração.
- **RNF-02** Usabilidade: O sistema deve ser fácil aos usuários interagirem, isso significa, ter componentes bem explicados, design responsível e acessibilidade
- **RNF-03** Desempenho: O sistema deve suportar 1000 usuários simultâneos sem degradação significativa.
- **RNF-04** Confiabilidade: O sistema não deve passar mais que 2 horas fora do ar por falhas.
- **RNF-05** Segurança: Apenas pessoas autenticadas devem ter acesso às funcionalidades do sistema.

# Histórias de Usuário

- **HU-01** - Título: Criação de perfil integrado ao SIGAA
  - História de usuário: Eu, como usuário, quero poder criar um perfil integrando com o SIGAA para que eu possa pegar meu histórico de disciplinas e meus dados pessoais.
  - Critérios de Aceitação:
    - O sistema deve permitir login exclusivo via SIGAA (sem cadastro local).
    - Após o primeiro login, o sistema deve importar automaticamente nome, matrícula, e-mail e curso.
    - O usuário não precisa preencher manualmente nenhum dado pessoal.

- **HU-02** - Título: Sincronização automática com o SIGAA
  - História de usuário: Eu, como usuário, quero que meu perfil integrado com o SIGAA seja atualizado automaticamente a cada semestre para que meu perfil sempre esteja atualizado com meu ponto atual universitário.
  - Critérios de Aceitação:
    - O sistema deve permitir login exclusivo via SIGAA (sem cadastro local).
    - O histórico de disciplinas deve ser sincronizado semestralmente.
    - Meus dados devem ser sincronizados semestralmente.

- **HU-03** - Título: Criar, editar e cancelar eventos
  - História de usuário: Eu, como professor, quero poder manipular eventos para que os alunos possam participar.
  - Critérios de Aceitação:
    - O professor pode criar eventos com um formulário contendo título, descrição, data, local, vagas e requisitos.
    - O professor pode editar ou cancelar eventos próprios.
    - Alunos visualizam apenas eventos ativos e futuros.

- **HU-04** - Título: Acesso à lista de inscritos para comunicação pós-inscrição
  - História de usuário: Eu, como professor, quero poder pegar as informações dos inscritos para que depois que terminar a inscrição dos eventos, notificá-los sobre as próximas etapas.
  - Critérios de Aceitação:
    - O professor pode visualizar nome, matrícula e e-mail de todos os inscritos.
    - O sistema permite enviar notificações em massa para os inscritos de um evento.
    - A lista pode ser exportada (PDF).

- **HU-05** - Título: Definição de perfil desejado para apoiadores do evento
  - História de usuário: Eu, como professor, quero definir os requisitos para que saibam que tipos de participantes eu busco para apoiar meu evento para que eu consiga selecionar colaboradores mais alinhados com as necessidades da minha atividade.
  - Critérios de Aceitação:
    - Na criação do evento, há campo “Requisitos para colaboradores” (texto livre ou checklist).
    - Os requisitos aparecem na página pública do evento.
    - O professor pode editar os requisitos mesmo após o evento publicado.

- **HU-06** - Título: Visualização de perfil dos candidatos para escolha de participantes
  - História de usuário: Eu, como professor, quero ter acesso às informações dos inscritos para poder escolher os participantes de acordo com os requisitos do projeto.
  - Critérios de Aceitação:
    - O professor poderá ver o histórico do participante e outros dados de seu perfil para avaliá-lo.
    - Pode aceitar ou recusar candidaturas individualmente.
    - O sistema notifica o aluno sobre a decisão.

- **HU-07** - Título: Calendário com todos os eventos que o aluno deseja participar
  - História de usuário: Eu, como aluno, quero poder ter acesso a uma agenda que marcará todas as minhas atividades que quero participar para que eu possa organizar minha rotina acadêmica e não perder prazos importantes.
  - Critérios de Aceitação:
    - O sistema permite ter um calendário com os eventos em que o aluno está inscrito ou tem interesse.
    - Clicar em um evento no calendário abre seus detalhes.

- **HU-08** - Título: Candidatura voluntária para produção do evento
  - História de usuário: Eu, como aluno, quero me candidatar para ser colaborador de um evento para ajudar na produção e ganhar horas complementares.
  - Critérios de Aceitação:
    - Todo evento exibe um botão “Candidatar‑se como colaborador”.
    - O professor recebe a candidatura e pode aceitar/recusar; o aluno é notificado.

- **HU-09** - Título: Alerta proativo de novas vagas em áreas de interesse
  - História de usuário: Eu, como aluno, quero ser notificado quando abrir vagas em projetos de interesses conhecidos para que eu não tenha que pesquisar sempre que abrir o portal.
  - Critérios de Aceitação:
    - O aluno pode marcar “categorias/áreas de interesse” no perfil.
    - Quando um novo evento ou vaga for criado nessas áreas, uma notificação é enviada.
    - O aluno pode desativar esse alerta a qualquer momento.

- **HU-10** - Título: Lista de espera automática para eventos lotados
  - História de usuário: Eu, como aluno, quero poder entrar em uma fila de espera caso acabem as vagas para que possa ser incluído em caso de desistência de outros ou não precise me inscrever novamente caso abra mais vagas.
  - Critérios de Aceitação:
    - Ao tentar se inscrever em um evento sem vagas, o sistema pergunta se deseja entrar na fila de espera.
    - O aluno é posicionado automaticamente na ordem de chegada.
    - Se uma vaga abrir, o próximo da fila é notificado e tem X horas para confirmar; caso contrário, passa ao seguinte.

- **HU-11** - Título: Alertas de mudanças no evento e abertura de vagas para colaboradores
  - História de usuário: Eu, como aluno, quero poder ser notificado caso haja qualquer tipo de alteração nos eventos que irei participar, e também, se eu quiser ajudar em um evento lotado, receber uma notificação caso abra uma vaga para ajudar para que eu possa ficar sempre atualizado e ter chance de participar mesmo quando o evento estiver cheio.
  - Critérios de Aceitação:
    - O aluno recebe notificação (e‑mail) quando houver alteração em evento que já participa.
    - Se o evento estiver lotado para colaboradores, o aluno pode solicitar “aviso de vaga”.
    - Ao abrir vaga, os primeiros que solicitaram aviso são notificados.

- **HU-12** - Título: Registrar interesse para receber atualizações
  - História de usuário: Eu, como aluno, quero poder demonstrar interesse em um evento para que possa receber notificações sobre o período de inscrição ou atualizações do evento.
  - Critérios de Aceitação:
    - Botão “Tenho interesse” disponível mesmo antes de abrirem inscrições.
    - O sistema notifica o aluno quando as inscrições abrirem.
    - Também avisa sobre mudanças relevantes (data, local, requisitos).

- **HU-13** - Título: Alerta prévio para eventos inscritos ou organizados
  - História de usuário: Eu, como usuário, quero receber lembretes 1 dia antes de um evento que me inscrevi ou que estou organizando para não esquecer a data.
  - Critérios de Aceitação:
    - O sistema envia automaticamente uma notificação (push/e‑mail) 24h antes do início de cada evento em que o usuário é participante ou organizador.
    - O usuário pode desativar esse lembrete nas configurações.
    - O lembrete contém link direto para a página do evento.
