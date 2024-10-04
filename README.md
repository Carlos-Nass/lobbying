### Links Importantes

Backend: https://github.com/Carlos-Nass/lobbying_backend

Frontend: https://github.com/Carlos-Nass/lobbying-frontend

Jira: https://lobbying.atlassian.net/jira/software/projects/SCRUM/boards/1?atlOrigin=eyJpIjoiMzU1ZmExYWJhOWM1NGNmYmE5MDZiMTBhYTgxYjMxNmUiLCJwIjoiaiJ9


# Lobbying

O ambiente empresarial está cada vez mais dinâmico e competitivo, a gestão eficaz dos recursos humanos é essencial para o sucesso organizacional. O Lobbying visa desenvolver uma plataforma tecnológica para facilitar a filtragem de vagas baseado no perfil comportamental do usuário.

## Objetivo Principal

O objetivo principal do Lobbying é desenvolver e implementar uma solução para facilitar a gestão de recursos humanos dentro das organizações. A plataforma resultante visa oferecer fácil acesso a vagas disponíveis e cadastradas dentro do próprio sistema, realizando uma filtragem customizada baseada no perfil do usuário.

### Problemas a resolver

**Falta de perfil de candidatos**: Um dos problemas na seleção de candidatos para vagas é que uma empresa necessita de um perfil específico para uma vaga e com os sistemas de hoje em dia é difícil saber o perfil de uma pessoa antes de realizar uma entrevista.

**Foco em resultados**: Ao evitar entrevistas desnecessárias com candidatos promissores apenas no currículo, usuário apenas conseguiriam visualizar vagas apenas que se encaixam com seu perfil comportamental.

## Requisitos

### Requisitos funcionais

RF-001 - O sistema deve permitir o cadastro de usuários.

RF-002 - O sistema deve mostrar os testes de personalidade disponíveis para o usuário 

RF-003 - O sistema deve receber dados dos testes de comportamento e processá-los.

RF-004 - O sistema deve ser capaz de recomendar vagas baseado no perfil comportamental.

RF-005 - O sistema deve permitir o armazenamento dos resultados dos testes e das vagas cadastradas no sistema.

RF-006 - O sistema deve liberar uma próxima avaliação nos testes de personalidade apenas três meses depois da realização inicial.

### Requisitos Não-Funcionais 

RNF-001 - O sistema deve fornecer segurança tais como proteção de dados sensíveis dos funcionários, garantindo conformidade com regulamentações de privacidade, como GDPR (Regulamento Geral de Proteção de Dados) e LGPD (Lei Geral de Proteção de Dados).

RNF-002 - O sistema deve ter controle de acesso baseado em papéis para garantir que apenas usuários autorizados tenham acesso a informações confidenciais.

RNF-003 - O sistema deve ter resposta rápida, mesmo em períodos de pico de uso.

RNF-004 - O sistema deve ter capacidade de lidar com grandes volumes de dados, especialmente em empresas com muitos funcionários

RNF-005 - O sistema deve ter uma interface intuitiva e amigável para facilitar o uso por parte dos usuários.

RNF-006 - O sistema deve ser capaz de escalar o sistema conforme a demanda cresce.

RNF-007 - O sistema deve ter facilidade de manutenção e atualização do sistema, incluindo correções de bugs e implementação de novos recursos.

## Casos de Uso

![Diagrama de caso de uso (1)](https://github.com/user-attachments/assets/abc3a582-30df-41e3-8bd9-f359888c5fc3)

## Modelo C4

### Nível 1

![image5](https://github.com/user-attachments/assets/c4b0d772-8970-4dac-80bf-70ff250f8e3a)

### Nível 2 

![image3](https://github.com/user-attachments/assets/f2a7bad4-cdaa-4eaf-a5ca-5977c159b927)

### Nível 3

![Cópia de Diagrama em branco](https://github.com/user-attachments/assets/ba2d4ae3-2f17-454d-aa1e-8142c5e07579)

## Diagrama de Classe

![Diagrama em branco (4)](https://github.com/user-attachments/assets/232730c3-be91-4053-820f-d0128b1fb42b)

# Stack Tecnológica

Nessa parte do documento será abordado o conjunto de tecnologias, ferramentas e frameworks que serão utilizadas para desenvolver e executar o projeto. Ela abrange todas as camadas necessárias, desde o desenvolvimento do front-end e back-end até a infraestrutura subjacente. 

## Linguagens de Programação:

*Java*: Foi selecionada a linguagem Java para desenvolver os serviços principais devido à sua ampla adoção, robustez, segurança e portabilidade. A vasta quantidade de recursos e bibliotecas disponíveis também facilita o desenvolvimento e manutenção do código.

## Frameworks e Bibliotecas:

*Spring Boot*: Será utilizado o Spring Boot para desenvolver os serviços Java, aproveitando sua simplicidade, produtividade e recursos integrados, como injeção de dependência, segurança, e suporte a APIs RESTful.

*React.js*: Para o desenvolvimento do frontend, foi escopado o React.js devido à sua eficiência, flexibilidade e robustez. A abordagem de componentes reutilizáveis facilita a construção de interfaces de usuário interativas e responsivas.

## Banco de Dados:

*Postgres*: Foi decidido o uso do Postgres como banco de dados relacional para armazenar dados estruturados, devido à sua confiabilidade, desempenho e ampla adoção na indústria.

## Ferramentas de Desenvolvimento e Gestão de Projeto:

*IDEs*: Será utilizado IntelliJ IDEA para desenvolvimento Java e Visual Studio Code para desenvolvimento React e Node.js devido à sua ampla gama de recursos, integração com ferramentas de controle de versão e suporte a plugins.

*Controle de Versão*: Foi selecionado o Git como sistema de controle de versão distribuído, hospedado em plataformas como GitHub.

*Ferramentas de Gestão de Projeto*: Para gestão de projetos, será usado metodologias ágeis, como Kanban, e ferramentas como Jira para planejamento de tarefas e acompanhamento de progresso.

*Ferramentas de CI/CD*: Será implementado pipelines de integração contínua e entrega contínua (CI/CD) utilizando ferramentas como o Jenkins para automatizar o processo de compilação, teste e implantação do código em ambientes de produção.
