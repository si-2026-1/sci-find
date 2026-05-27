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

# Histórias de Usuários
- **HU-01**  - Título: Criação de perfil integrado ao SIGAA
 -História de usuário: Eu, como usuário, quero poder criar um perfil integrando com o SIGAA para que eu possa     pegar meu histórico de disciplinas e meus dados pessoais.
 -Critérios de Aceitação:
  -O sistema deve permitir login exclusivo via SIGAA (sem cadastro local).
  -Após o primeiro login, o sistema deve importar automaticamente nome, matrícula, e-mail e curso.
  -O usuário não precisa preencher manualmente nenhum dado pessoal.




