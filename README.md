# Documento de Visão do Projeto

## 1. Introdução
### 1.1 Propósito do Documento
Este documento descreve a visão geral do projeto da plataforma de aprendizado online.

### 1.2 Escopo do Projeto
O projeto visa desenvolver uma plataforma de aprendizado online que ofereça cursos, testes e outros recursos educacionais para estudantes. A plataforma estará disponível tanto para desktop quanto para dispositivos móveis.

### 1.3 Definições, Acrônimos e Abreviações
- **LMS**: Learning Management System (Sistema de Gerenciamento de Aprendizado)
- **UI**: User Interface (Interface do Usuário)
- **UX**: User Experience (Experiência do Usuário)

### 1.4 Referências
- [Link para o site oficial da plataforma](https://www.exemplo-learning-plataforma.com.br)

### 1.5 Visão Geral do Documento
Este documento apresenta informações detalhadas sobre o projeto, incluindo posicionamento, descrição dos stakeholders, características do produto, requisitos funcionais e não funcionais, restrições e análise de riscos.

## 2. Posicionamento
### 2.1 Oportunidade de Negócio
O mercado de educação online está em crescimento, com uma demanda crescente por plataformas flexíveis e acessíveis.

### 2.2 Declaração do Problema
A falta de uma plataforma abrangente de aprendizado online dificulta o acesso a recursos educacionais de qualidade.

### 2.3 Descrição do Produto
A plataforma oferecerá cursos, testes e interação entre estudantes e professores.

### 2.4 Benefícios do Produto
- Acesso a conteúdo educacional de alta qualidade
- Flexibilidade para estudar em qualquer lugar e a qualquer hora

## 3. Descrição dos Stakeholders e Usuários
### 3.1 Perfis dos Stakeholders
- Administradores
- Professores
- Estudantes

### 3.2 Perfis dos Usuários
- Estudantes: Acessam cursos, assistem aulas e realizam tarefas.
- Professores: Criam e gerenciam cursos, adicionam aulas e atividades.
- Administradores: Gerenciam usuários e cursos.

## 4. Visão Geral do Produto
### 4.1 Perspectiva do Produto
A plataforma será compatível com diversos sistemas operacionais e terá uma interface intuitiva.

### 4.2 Suposições e Dependências
- Disponibilidade de servidores e infraestrutura de TI.

### 4.3 Capacidades do Produto
- Cadastro de usuários
- Criação e gerenciamento de cursos
- Interação entre estudantes e professores

## 5. Características do Produto
### 5.1 Lista de Características
- Cadastro de usuários
- Criação de cursos
- Aulas e tarefas
- Mensagens e fóruns de discussão

### 5.2 Descrição Detalhada de Características
Detalhes sobre cada característica serão fornecidos no documento completo.

## 6. Requisitos Funcionais e Não Funcionais
### 6.1 Requisitos Funcionais
- Cadastro de usuários
- Criação de cursos
- Acompanhamento do progresso do curso

### 6.2 Requisitos Não Funcionais
- Segurança
- Desempenho

## 7. Restrições do Projeto
### 7.1 Tecnologia e Padrões
- Compatibilidade com Windows

### 7.2 Legislação e Regulamentações
- Proteção de dados pessoais

## 8. Análise de Riscos e Mitigação
Detalhes sobre os riscos e estratégias de mitigação serão fornecidos no documento completo.

## 9. Anexos
### 9.1 Glossário
- LMS: Sistema de Gerenciamento de Aprendizado
- UI: Interface do Usuário
- UX: Experiência do Usuário

### 9.2 Outros Anexos
Outros anexos relevantes serão incluídos no documento completo.

# Requisitos Funcionais

## 1. Cadastro de Usuários

| **Requisito ID** | **Título** | **Descrição** | **Entrada** | **Processamento** | **Saída** | **Restrições** | **Critérios de Aceitação** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| APOL-001 | Cadastro de Usuários | O sistema deve permitir que os usuários se cadastrem na plataforma, fornecendo informações como nome, e-mail e senha. | Dados do usuário (nome, e-mail, senha). | Verifica se o e-mail é único. Armazena os dados do usuário no banco de dados. | Mensagem de confirmação de cadastro bem-sucedido. Mensagem de erro se o e-mail já estiver em uso. | (a) Apenas usuários autenticados podem realizar cadastro. (b) Um usuário só pode se cadastrar uma vez. | (a) O usuário é cadastrado com sucesso. (b) O sistema impede cadastros duplicados. |

## 2. Criação de Cursos

| **Requisito ID** | **Título** | **Descrição** | **Entrada** | **Processamento** | **Saída** | **Restrições** | **Critérios de Aceitação** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| APOL-002 | Criação de Cursos | Professores devem poder criar e gerenciar cursos na plataforma. | Dados do curso (título, descrição, materiais, etc.). | Verifica se o professor está autenticado. Armazena os dados do curso no banco de dados. | Mensagem de confirmação de criação do curso. | (a) Apenas professores podem criar cursos. | O curso é criado com sucesso e está disponível na plataforma. |

## 3. Aulas e Tarefas

| **Requisito ID** | **Título** | **Descrição** | **Entrada** | **Processamento** | **Saída** | **Restrições** | **Critérios de Aceitação** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| APOL-003 | Aulas e Tarefas | Estudantes devem poder acessar aulas e tarefas associadas aos cursos. | Seleção de curso e aula/tarefa. | Verifica se o estudante está inscrito no curso. Exibe o conteúdo da aula ou detalhes da tarefa. | Conteúdo da aula ou detalhes da tarefa. | (a) O estudante deve estar inscrito no curso. | (a) O estudante acessa o conteúdo da aula ou detalhes da tarefa com sucesso. |

## 4. Interação entre Estudantes e Professores

| **Requisito ID** | **Título** | **Descrição** | **Entrada** | **Processamento** | **Saída** | **Restrições** | **Critérios de Aceitação** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| APOL-004 | Interação entre Estudantes e Professores | Estudantes e professores devem poder trocar mensagens e participar de fóruns de discussão. | Mensagens ou tópicos de discussão. | Verifica se o usuário está autenticado. Armazena as mensagens ou tópicos no sistema. | Mensagens enviadas ou tópicos criados. | (a) Apenas usuários autenticados podem participar. | (a) Mensagens são enviadas com sucesso. (b) Tópicos de discussão são criados e acessíveis. |

# Riscos do projeto

1. **Tempo de Resposta**:

   | Campo               | Descrição                                                                                   |
   |---------------------|---------------------------------------------------------------------------------------------|
   | Requisito ID        | NF-BIBL-001                                                                                  |
   | Título              | Tempo de Resposta                                                                            |
   | Descrição           | O sistema deve responder a todas as solicitações dos usuários em até 2 segundos.              |
   | Entrada             | Solicitação do usuário (ex. pesquisa de livro, reserva, empréstimo)                            |
   | Processamento       | O sistema processa a solicitação do usuário e retorna o resultado.                               |
   | Saída               | Resultado da solicitação do usuário (ex. lista de livros, confirmação de reserva)               |
   | Restrições          | Aplica-se a todas as solicitações feitas pelos usuários no sistema.                               |
   | Critérios de Aceitação | a. O tempo de resposta para todas as solicitações de usuários não excede 2 segundos. (b) A experiência do usuário não é prejudicada por lentidão no sistema. |

2. **Critérios de Qualidade**:

   | Campo               | Descrição                                                                                   |
   |---------------------|---------------------------------------------------------------------------------------------|
   | Requisito ID        | NF-BIBL-002                                                                                  |
   | Título              | Critérios de Qualidade                                                                       |
   | Descrição           | O sistema deve atender aos seguintes critérios de qualidade:                                    |
   |                     | a. **Segurança**: Os dados dos usuários devem ser protegidos por criptografia e autenticação robusta. |
   |                     | b. **Conformidade com Regulamentações**: O sistema deve seguir regulamentações de privacidade, como o GDPR. |
   |                     | c. **Desempenho Rápido**: O tempo de resposta não deve prejudicar a experiência do usuário. |
   |                     | d. **Compatibilidade**: A plataforma deve funcionar em sistemas operacionais como Windows, Mac OS e iOS. |
   |                     | e. **Escalabilidade**: O sistema deve suportar um grande número de usuários simultâneos. |

3. **Critérios de Plataforma**:

   | Campo               | Descrição                                                                                   |
   |---------------------|---------------------------------------------------------------------------------------------|
   | Requisito ID        | NF-BIBL-003                                                                                  |
   | Título              | Critérios de Plataforma                                                                       |
   | Descrição           | O sistema deve ser compatível com as seguintes plataformas:                                     |
   |                     | a. **Web**: A plataforma deve funcionar em navegadores modernos (Chrome, Firefox, Edge etc.). |
   |                     | b. **Mobile**: O aplicativo deve ser compatível com dispositivos móveis (iOS e Android).     |

4. **Escalabilidade**:

   | Campo               | Descrição                                                                                   |
   |---------------------|---------------------------------------------------------------------------------------------|
   | Requisito ID        | NF-BIBL-004                                                                                  |
   | Título              | Escalabilidade                                                                               |
   | Descrição           | O sistema deve ser projetado para lidar com um grande número de acessos simultâneos.           |
   |                     | a. **Estimativa de Acessos Simultâneos**: O sistema deve suportar pelo menos X acessos simultâneos durante horários de pico. |

Certamente! Vamos criar uma análise de risco para um projeto de desenvolvimento de software, seguindo o padrão IEEE-830. Abaixo estão os detalhes:

# Requisitos Não Funcionais

1. **Atraso na Entrega do Projeto devido à Falta de Recursos Disponíveis**:

   | Campo               | Descrição                                                                                   |
   |---------------------|---------------------------------------------------------------------------------------------|
   | Requisito ID        | NF-RISK-001                                                                                  |
   | Título              | Atraso na Entrega do Projeto devido à Falta de Recursos Disponíveis                            |
   | Descrição           | O projeto deve considerar os riscos associados à falta de recursos disponíveis e implementar medidas de mitigação. |
   | Entrada             | (a) Estimativa de recursos necessários para o projeto (b) Informações sobre a disponibilidade de recursos na empresa |
   | Processamento       | (a) Identificar causas potenciais de falta de recursos (b) Avaliar a probabilidade e o impacto do risco (c) Desenvolver estratégias de mitigação |
   | Saída               | (a) Plano de alocação de recursos (b) Plano de contingência para lidar com a falta de recursos (c) Monitoramento contínuo do risco |
   | Restrições          | (a) A análise de riscos deve ser realizada durante a fase de planejamento do projeto. |
   | Critérios de Aceitação | (a) Identificação, mitigação e monitoramento contínuo de riscos pela equipe. |

## Definição de Usuários e Stakeholders

### 1. **Usuários do Sistema**

| **Tipo de Usuário** | **Descrição**                                                                                                                                                                                                                   |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Estudantes          | - São os principais beneficiários da plataforma.<br>- Acessam cursos, assistem aulas, realizam tarefas e testes.<br>- Dependem da plataforma para seu aprendizado e progresso acadêmico.                                              |
| Professores         | - Criam e gerenciam conteúdo educacional.<br>- Oferecem cursos, aulas e tarefas.<br>- Interagem com os estudantes por meio de mensagens e fóruns.<br>- Avaliam o desempenho dos alunos.                                              |
| Administradores     | - Responsáveis pela manutenção e configuração do sistema.<br>- Gerenciam usuários, permissões e recursos.<br>- Monitoram o desempenho e a segurança da plataforma.<br>- Garantem a continuidade do serviço.                              |

### 2. **Stakeholders do Projeto**

| **Stakeholder ID** | **Nome**            | **Descrição**                                                                                                                                                                                                                   |
|--------------------|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SH-001             | Gerente de Projeto  | - Planeja, coordena, monitora e controla o projeto de desenvolvimento de software.<br>- Define o escopo, prazos e metas.<br>- Aloca recursos e gerencia riscos.<br>- Coordena a comunicação entre a equipe e os stakeholders.                |
| SH-002             | Equipe de Desenvolvimento | - Desenvolvedores, designers e outros profissionais envolvidos na criação da plataforma.<br>- Contribuem com a implementação técnica e a qualidade do código.<br>- Trabalham para atender aos requisitos do projeto.                    |
| SH-003             | Equipe de Testes    | - Realiza testes funcionais, de usabilidade e de segurança.<br>- Identifica e relata defeitos.<br>- Contribui para a qualidade do produto final.<br>- Garante que a plataforma atenda aos padrões e requisitos.                        |
| SH-004             | Clientes            | - Representam as instituições de ensino ou empresas que utilizarão a plataforma.<br>- Têm expectativas claras sobre funcionalidades e desempenho.<br>- Podem fornecer feedback valioso durante o desenvolvimento.                      |
| SH-005             | Investidores        | - Financiam o projeto e têm interesse no retorno do investimento.<br>- Acompanham o progresso e os resultados.<br>- Esperam que a plataforma seja bem-sucedida e gere benefícios financeiros.                                      |
| SH-006             | Órgãos Reguladores  | - Podem estabelecer diretrizes e regulamentações para plataformas de E-learning.<br>- Devem ser considerados para garantir conformidade legal.<br>- Influenciam o escopo e os requisitos do projeto.                               |

## Restrições do Projeto

Uma **restrição** é uma limitação ou condição imposta ao projeto que afeta sua execução, desenvolvimento ou resultado. Essas restrições podem ser de origem interna ou externa e devem ser consideradas ao longo do ciclo de vida do projeto. Vamos detalhar algumas das principais restrições para a nossa plataforma de E-learning:

### 1. **Restrições Tecnológicas**

| **Campo**          | **Descrição**                                                                                                                                                                                                                   |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Requisito ID**   | NF-CONST-001                                                                                                                                                                                                                     |
| **Título**         | Restrições Tecnológicas                                                                                                                                                                                                          |
| **Descrição**      | O projeto deve ser desenvolvido utilizando as tecnologias, linguagens de programação e padrões especificados pela empresa.                                                                                                       |
| **Entrada**        | - Lista de tecnologias e padrões aprovados pela empresa.                                                                                                                                                                         |
| **Processamento**  | - Selecionar as tecnologias e padrões apropriados para o projeto.                                                                                                                                                                 |
| **Saída**          | - Projeto desenvolvido de acordo com as tecnologias e padrões especificados.                                                                                                                                                       |
| **Restrições**     | - A equipe do projeto deve seguir as diretrizes e padrões estabelecidos pela empresa.                                                                                                                                             |
| **Critérios de Aceitação** | - O projeto é desenvolvido utilizando as tecnologias e padrões especificados.<br>- A revisão do código e da arquitetura confirma a conformidade com os padrões estabelecidos. |

### 2. **Restrições de Prazo**

| **Campo**          | **Descrição**                                                                                                                                                                                                                   |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Requisito ID**   | NF-CONST-002                                                                                                                                                                                                                     |
| **Título**         | Restrições de Prazo                                                                                                                                                                                                              |
| **Descrição**      | O projeto deve ser entregue dentro dos prazos estabelecidos.                                                                                                                                                                      |
| **Entrada**        | - Cronograma do projeto com datas de marcos intermediários e entrega final.                                                                                                                                                       |
| **Processamento**  | - Monitorar o progresso do projeto e garantir que as atividades estejam alinhadas com os prazos definidos.                                                                                                                        |
| **Saída**          | - Entrega do projeto conforme o cronograma.                                                                                                                                                                                       |
| **Restrições**     | - Cumprir os prazos estabelecidos para evitar atrasos e impactos negativos.                                                                                                                                                    |
| **Critérios de Aceitação** | - Todas as entregas intermediárias e a entrega final são realizadas dentro dos prazos previstos. |

### 3. **Restrições de Recursos**

| **Campo**          | **Descrição**                                                                                                                                                                                                                   |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Requisito ID**   | NF-CONST-003                                                                                                                                                                                                                     |
| **Título**         | Restrições de Recursos                                                                                                                                                                                                           |
| **Descrição**      | O projeto deve ser executado com os recursos disponíveis, incluindo equipe, orçamento e infraestrutura.                                                                                                                         |
| **Entrada**        | - Recursos alocados para o projeto (pessoas, equipamentos, ferramentas etc.).                                                                                                                                                      |
| **Processamento**  | - Gerenciar a utilização eficiente dos recursos disponíveis.                                                                                                                                                                      |
| **Saída**          | - Execução do projeto dentro dos limites de recursos definidos.                                                                                                                                                                    |
| **Restrições**     | - Evitar desperdício de recursos e garantir a sustentabilidade do projeto.                                                                                                                                                        |
| **Critérios de Aceitação** | - Os recursos são utilizados de forma otimizada e alinhada com o planejamento. |


## 3. **Visão Geral do Produto**

### 4.1 Perspectiva do Produto

A nossa plataforma de E-learning está inserida no contexto do mercado de educação online em constante expansão. Com um número crescente de estudantes e profissionais buscando oportunidades de aprendizado flexíveis e acessíveis, o nosso projeto visa desenvolver uma plataforma que ofereça cursos, testes e outros recursos educacionais. A plataforma estará disponível tanto para desktop quanto para dispositivos móveis.

### Público-Alvo

Os principais públicos-alvo da nossa plataforma são:

1. **Estudantes**:
   - Indivíduos que buscam cursos online para aprimorar suas habilidades profissionais, acadêmicas ou pessoais.
   - Alunos de instituições de ensino que desejam complementar sua formação com cursos adicionais.

2. **Professores e Instrutores**:
   - Educadores que desejam criar e gerenciar cursos online.
   - Especialistas em diversas áreas que podem compartilhar seu conhecimento por meio da plataforma.

3. **Administradores de Instituições de Ensino e Empresas**:
   - Responsáveis por oferecer oportunidades de aprendizado para seus alunos ou colaboradores.
   - Interessados em monitorar o progresso dos estudantes e avaliar o desempenho dos cursos.

### Proposta de Valor

A nossa plataforma oferece os seguintes benefícios:

- **Flexibilidade**: Os estudantes podem acessar os cursos a qualquer momento e de qualquer lugar, adaptando o aprendizado às suas agendas e necessidades.
- **Variedade de Conteúdo**: Cursos abrangem diversas áreas, desde habilidades técnicas até desenvolvimento pessoal.
- **Interação e Engajamento**: Recursos como fóruns de discussão e mensagens permitem a interação entre estudantes e professores.
- **Avaliação e Acompanhamento**: Os estudantes podem medir seu progresso por meio de testes e tarefas, enquanto os professores acompanham o desempenho.

## 4.2 Suposições e Dependências

### Suposições

1. A equipe terá acesso às tecnologias e plataformas especificadas pela empresa.
2. Os requisitos de hardware e software serão atendidos para garantir o funcionamento adequado da plataforma.

### Dependências

1. APIs de terceiros para autenticação e integração de conteúdo.
2. Serviços de hospedagem em nuvem para garantir escalabilidade e disponibilidade.

## 4.3 Capacidades do Produto

### Principais Funcionalidades

1. **Cursos e Aulas**:
   - Estudantes se inscrevem em cursos.
   - Professores criam e gerenciam cursos, adicionando aulas e conteúdo educacional.

2. **Tarefas e Atividades**:
   - Estudantes recebem tarefas e atividades relacionadas aos cursos.
   - Podem enviar respostas e acompanhar o progresso.

3. **Testes e Avaliações**:
   - Estudantes realizam testes e avaliações.
   - Configurações personalizáveis, como número de perguntas e tempo de resposta.

4. **Interação entre Usuários**:
   - Mensagens e fóruns de discussão permitem comunicação entre estudantes e professores.
   - Notificações mantêm os usuários atualizados.

### Requisitos de Desempenho

- Tempo de Resposta: Páginas devem carregar em menos de 2 segundos.
- Capacidade de Processamento: Suporte a pelo menos 1.000 usuários ativos simultaneamente.

### Características de Qualidade

- **Usabilidade**: Interface intuitiva, compatível com desktop e dispositivos móveis.
- **Segurança**: Autenticação segura, controle de acesso e proteção contra ataques.
- **Confiabilidade**: Disponibilidade contínua (99,9% de uptime) e backup regular.
- **Manutenibilidade**: Código bem documentado e atualizações ágeis.
