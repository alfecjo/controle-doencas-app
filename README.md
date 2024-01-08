# ☕ Frameworks Web
![Angular](Angular.jpg)

## Este material foi desenvolvido em resposta a disciplina 'FrameWorks Web', a qual faz parte do curso de Pós Graduação em Tecnologia Java, ministrado pela Universidade Tecnológica Federal do Paraná.
🎉 Trata-se do projeto final, construido, utilizando o Framework Angular 16, associado a linguagem TypeScript.

🥋 Se você está entrando no Angular agora, bem como TypeScript, vou deixar um comentário apenas para orientá-lo, caso considere o código desta entrega estranho. Existem todos os níveis de dificuldade, entretanto, por não se tratar do uso do padrão para gerenciamento de estados Redux, para ser mais específico, o qual, dentro do Angular recebe o nome @ngrx, os níveis de dificuldade são menores, levando em consideração que a curva de aprendizado para a programação convencional é razoavelmente inferior.

Por esta razão, a dificuldade apresentada no projeto pelo professor e os demais colegas, foi considerada MEDIANA. Foram tratados assuntos como componentes, serviços, roteamento, e manipulação de formulários. Durante o desenvolvimento, aprendi a estruturar um projeto Angular de forma organizada, utilizando módulos para separar funcionalidades e garantir uma arquitetura escalável. Também explorei a poderosa linguagem TypeScript, que adiciona tipagem estática ao JavaScript, trazendo mais segurança ao desenvolvimento.

Caso não entenda de primeira, continue tentando, pois, o sucesso não só reside nos melhores, mas também, nos persistentes, que considero meu caso (_😎tirei nota máxima). Desenvolver software, nada mais é que descartar a possibilidade de desistência, independente de qualquer motivo!

## Deve-se utilizar:

   - O Angular CLI versão 16.0.0 ou superior;
   - Versão específica do TypeScript compatível com a versão do Angular CLI utilizada;
   - Mínimo Angular 16 para garantir compatibilidade;
   - Utilização das versões recomendadas para as principais dependências, conforme especificado no arquivo package.json;
   - Requisitos específicos para Node.js, seguindo as diretrizes do Angular CLI;
   - Outras dependências e bibliotecas conforme necessário para o projeto.

Certifique-se de consultar a documentação oficial do Angular para obter informações detalhadas sobre requisitos e configurações específicas para a versão desejada.

## 🔍 Projeto

### 👨‍💻 Framework Angular - Linguagem TypeScript

- A avaliação da disciplina se dará pela entrega de um projeto de uma aplicação web desenvolvido com o uso do framework Angular, sendo que o tema e o escopo do projeto deverá ser definido pelo aluno logo no início da disciplina. A aplicação deve ser desenvolvida progressivamente durante a disciplina, ou seja, à medida em que o aluno vai estudando o conteúdo semanal. É uma forma de praticar o conteúdo estudado e transformar em aprendizado. As atividades semanais (com entregas que valem nota) estão em sua maioria relacionadas ao projeto. - Desta forma, se o aluno realizar progressivamente as atividades, no final da disciplina, espera-se que ele tenha o projeto concluído para apresentar como produto para a avaliação. No entanto, nas atividades semanais não serão cobradas funcionalidades funcionais e completas, mas apenas o uso mínimo de algumas características do framework. Certamente, o projeto final a ser apresentado como avaliação conterá múltiplos usos destas características e aprofundamentos destes, resultado da motivação do aluno em satisfazer o escopo do projeto proposto.

O projeto para ser contemplado com a nota máxima precisa conter implementado pelo menos a totalidade de uma lista de tópicos pré-definida pelo Professor e ser funcional, ou seja, satisfazer o escopo proposto no início da disciplina. Esta lista de itens está organizada em forma de checklist para melhor orientar o aluno no processo de desenvolvimento do projeto e também para dar uma maior exatidão no cálculo da nota da avaliação. Mas vale salientar que, se o aluno preencher um item e for comprovado que ele não fez ou não sabe explicar, será penalizado com a retirada de nota deste e de outro item feito.

### ⏰ Etapas

  - Definir o tema e escopo do projeto (os temas escolhidos podem ser vistos na planilha (somente leitura)).
  - Criar o repositório no GitHub conforme a estrutura de branches do Gitflow.
  - Editar o Readme.md com o checklist de tópicos.
  - Projetar os protótipos das telas e incluir o link no Readme.md
  - Realizar as atividades semanais, tentando tratar como entregas parciais do projeto.
  - Fazer o deploy da aplicação no GitHub Pages e incluir o link no Readme.md
  - Entregar o projeto final.
  - Gravar um vídeo (entrega do link) ou fazer um relatório textual (entrega em PDF) apresentando o projeto desenvolvido de acordo com o checklist.

 ### 👷 Integrantes:
  - O projeto deverá ser desenvolvido individualmente.

### 💎 Tema:
  - O tema precisa ser único dentre os alunos da turma;
  - O tema só será válido após o aceite do Professor;
  - Os temas já escolhidos e aprovados pelo Professor podem ser vistos na planilha.
  - A aplicação é para uso pessoal, e não deve prever comunicação com outros softwares ou perfis de contas de usuários;

### 📑 Exigências Gerais:

  - O projeto precisa ser armazenado no repositório do GitHub ou similar e o endereço do repositório ser informado ao professor.
  - O checklist com os itens implementados deve constar no README.md do repositório do projeto.
  - O projeto precisa ser hospedado do GitHub Pages ou similar e o endereço de acesso deve ser informado no README.md
  - O sistema deve ser implementado contendo as funcionalidades referentes aos tópicos apresentados a seguir. Também serão consideradas as boas práticas de programação em JavaScript/TypeScript, uso adequado de notações e conceitos aprendidos. Ainda, serão avaliados os wireframes/protótipos do sistema.
  - A estrutura de checklist pode ser copiado do projeto roubank no GitHub disponível no seguinte endereço: https://github.com/utfpr-gp/roubank-app 

## 🕵️ Critérios de aceite e avaliação:

### 👁️‍🗨️ Tópicos/Checklist

  - Criar o repositório no GitHub com a estrutura do Gitflow, ou seja, branches main e develop.
  - Usar componentes de algum framework CSS (Bootstrap, Materialize ou outro).
  - Apresentar as telas com layout responsivo usando ou não algum framework CSS.
  - Construir páginas web com o conceito de componentes. 
  - Criar o layout da aplicação com componentes, ou seja, o cabeçalho e rodapé precisam ser componentes.
  - Usar pelo menos dois tipos de data-binding (Interpolation, Property Binding, Event Binding e Two Way Data Binding).
  - Passar dados via hierarquia de componentes, ou seja, usando @Input ou @Output.
  - Mapear componentes à rotas no módulo de rotas.
  - Criar navegação entre páginas por meio de rotas.
  - Passar dados entre componentes que representam diferentes telas via parâmetros de rotas. 
  - Validar campos do formulário com REGEX e apresentar os erros.
  - Desabilitar o botão de submit enquanto o formulário está inválido.
  - Fazer requisições a API com tratamento da resposta com Promises ou Observables.
  - Cadastrar uma entidade usando uma API (JSON Server).
  - Apresentar uma lista de dados com a diretiva estrutural ngFor.
  - Usar a diretiva ngIf
  - Formatar a apresentação de dados com Pipes.
  - Build e deploy da aplicação.

## 🎯 Minhas entregas:

### 🏆 Este projeto tem como objetivo implementar requisitos impostos pela disciplína Frameworks Web, a título de avaliação. Trata-se de uma aplicação web que possibilita rastrear comunidades afetadas por doenças infectocontagiosas. (ex: cadastro, alteração, deleção, listagem), sendo o diferencial, a facilidade de uso e operação pelo cliente;

   -  O frontend da aplicação foi desenvolvido com Angular e o backend foi simulado pela implementação de uma API Fake, usando o JSON Server;

   - Endereço de Deploy: <https://alfecjo.github.io/controle-doencas-app/cadastro>

   - Protótipo: <https://www.figma.com/file/Ic3EmqlxEY73UzVz18HHWG/controleDoencas?type=design&node-id=7%3A14&t=CIo2pmdvdcptwzRV-1>

### 📽️ Click na imagem e assista ao vídeo de apresentação do Projeto..     

[![Assista ao Vídeo de Apresentação do Projeto](https://img.youtube.com/vi/45DLJ_OVJCg/maxresdefault.jpg)](https://www.youtube.com/watch?v=45DLJ_OVJCg)


   - Checklist

    - [x]Criar o repositório no GitHub com a estrutura do Gitflow, ou seja, branches main e develop.
    - [x]Usar componentes de algum framework CSS (Bootstrap, Materialize ou outro)
    - [x]Apresentar as telas com layout responsivo usando ou não algum framework CSS.
    - [x]Construir páginas web com o conceito de componentes.
    - [x]Criar o layout da aplicação com componentes, ou seja, o cabeçalho e rodapé precisam ser componentes.
    - [x]Usar pelo menos dois tipos de data-binding (Interpolation, Property Binding, Event Binding e Two Way Data Binding).
    - [x]Passar dados via hierarquia de componentes, ou seja, usando @Input ou @Output.
    - [x]Mapear componentes à rotas no módulo de rotas.
    - [x]Criar navegação entre páginas por meio de rotas.
    - [x]Passar dados entre componentes que representam diferentes telas via parâmetros de rotas.
    - [x]Validar campos do formulário com REGEX e apresentar os erros.
    - [x]Desabilitar o botão de submit enquanto o formulário está inválido.
    - [x]Fazer requisições a API com tratamento da resposta com Promises ou Observables.
    - [x]Cadastrar uma entidade no JSON Server.
    - [x]Apresentar uma lista de dados com a diretiva estrutural ngFor.
    - [x]Usar a diretiva ngIf
    - [x]Formatar a apresentação de dados com Pipes.
    - [x]Build e deploy da aplicação.

# Tecnologia utilizada:

![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

## Tabela de Conteúdos

- [Instalação](#Instalação)
- [Uso](#Uso)
- [Contribuição](#Contribuição)

## Instalação

1. Clone o repositório ou baixe o arquivo .zip:

```bash
git clone https://github.com/alfecjo/controle-doencas-app.git
```
## Uso

1. **Configuração do Ambiente de Desenvolvimento:**
    - Execute o projeto na sua IDE de preferência, com preferência para o Visual Studio Code (VS Code).
    - Certifique-se de respeitar as orientações de versões indicadas no projeto.

2. **Obtenção do Código Mais Recente:**
    - Faça checkout para o branch 'develop' para acessar as modificações mais recentes do projeto.

3. **Abertura do Projeto no Visual Studio Code:**
    - Abra o projeto no editor Visual Studio Code (VS Code).

4. **Instalação de Dependências:**
    - Através do terminal do VS Code ou do terminal do seu Sistema Operacional, navegue até o diretório raiz do projeto.
    - Instale as dependências do projeto contidas no arquivo `package.json` utilizando o comando: `npm i`.

5. **Instalação do JSON Server (Opcional):**
    - (Opcional) Caso ainda não tenha o JSON Server instalado globalmente, você pode instalá-lo através do comando: `npm i -g json-server`. 
    - Nota: Essa etapa é opcional porque a dependência já está listada no arquivo `package.json`.

6. **Execução da API Fake (JSON Server):**
    - Execute a API Fake (JSON Server) com o seguinte comando:
      - Via Execução Explícita: `json-server --watch db.json`. Certifique-se de executar esse comando no diretório `/dados`, que contém o arquivo `db.json`.
      - Por padrão, a aplicação JSON Server executa no endereço `localhost:3000`.

7. **Execução do Projeto Angular:**
    - Abra um novo terminal no VS Code e execute o projeto Angular com o comando: `ng s -o`.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, abra um problema ou envie uma solicitação pull ao repositório.

Ao contribuir para este projeto, siga o estilo de código existente, [convenções de commit](https://www.conventionalcommits.org/en/v1.0.0/), e envie suas alterações em um branch separado.

Muito obrigado!!
