# Sistema de Gestão Escolar 📚

**[Visite o Repositório](https://github.com/devmasterpt/sistema-de-gestao-escolar)**

## Visão Geral do Projeto

## Descrição

O **Sistema de Gestão Escolar SaaS** é uma plataforma desenvolvida para a gestão de instituições de ensino superior, como universidades, institutos politécnicos e faculdades. O objetivo principal é fornecer uma plataforma centralizada onde as instituições possam se cadastrar, gerenciar cursos, alunos, professores e turmas, além de facilitarem processos administrativos como matrícula, emissão de certificados e relatórios.

O projeto está sendo desenvolvido com uma stack moderna, utilizando **React**, **Node.js**, **Next.js**, **Tailwind CSS**, **TypeScript**, entre outras tecnologias. O foco inicial é a criação de uma versão mínima funcional (MVP), com funcionalidades essenciais de gestão, e expandir para novas funcionalidades avançadas nas próximas versões.

---

## Estrutura do Projeto

> A estrutura do projeto está sendo discutida e melhorada cada vez nais, será definida com a ajuda da comunidade. Se você tiver sugestões, contribua abrindo uma issue ou participando das nossas reuniões de desenvolvimento.

### Estrutura planejada:

- **Node.js** com **Express**: Para construção do backend.
- **Next.js**: Para desenvolvimento da interface do usuário.
- **SCSS**: Para estilos em CSS.
- **PostgreSQL**: Para gerenciamento do banco de dados.
- **Prisma**: Como ORM para interação com o banco de dados.
- **React Native** (usando **Expo**): Para desenvolvimento de aplicativos móveis.
- **TypeScript**: Para maior robustez e tipagem no código.
- **React**: Para construção de interfaces reativas.
- **Tailwind CSS** (opcional): Para estilos personalizados.


## Funcionalidades da Versão Inicial (MVP)

1. **Autenticação e Controle de Acesso**: 
   - Sistema de login e registro para diferentes perfis (Administrador, Professor, Aluno).
   - Recuperação de senha.
   - Proteção de rotas usando JWT (JSON Web Tokens).

2. **Gestão de Usuários** (Admins):
   - CRUD (Criar, Ler, Atualizar, Excluir) para usuários: professores, alunos e administradores.
   - Gerenciamento de permissões e níveis de acesso.

3. **Gestão de Turmas e Disciplinas**:
   - Criação e gerenciamento de turmas.
   - Atribuição de professores e alunos às disciplinas.

4. **Gestão de Notas e Frequência** (Professores):
   - Registro de notas por disciplina.
   - Registro de frequência dos alunos.

5. **Consulta de Notas e Frequência** (Alunos):
   - Alunos podem visualizar suas notas e presença por disciplina.

6. **Dashboard para Administradores e Professores**:
   - Visualização de métricas de alunos, turmas e disciplinas.
   - Relatórios básicos de desempenho.

---

## Funcionalidades Futuras

- **Mensagens Internas**: Comunicação entre alunos, professores e administradores.
- **Gerenciamento Financeiro**: Sistema para cobrar mensalidades e gerenciar pagamentos escolares.
- **Agenda de Eventos**: Integração com calendário para gerenciar eventos escolares.
- **Relatórios Avançados**: Gerar relatórios detalhados de desempenho acadêmico.
- **Integração com APIs Externas**: Ferramentas de notificação por SMS, plataformas de aprendizado online.
- **Gamificação**: Ranking e sistema de recompensas para alunos.
- **Suporte Multilíngue**: Interface em vários idiomas.
- **Funcionalidades Offline (Mobile)**: Utilização do app mobile sem conexão, com sincronização posterior.

---

## Tecnologias Utilizadas

- **Front-end**:
  -  React, Next.js
  - TailwindCSS para estilização
  - TypeScript para tipagem estática

- **Back-end**:
  - Node.js com Express
  - TypeScript para maior segurança e escalabilidade
  - PostgreSQL como banco de dados relacional
  - Autenticação JWT

- **Mobile**:
  - React Native com Expo para desenvolvimento de apps móveis
  - Integração com o back-end via API REST

---

## Como Contribuir 🚀

Estamos abertos a contribuições de desenvolvedores de todos os níveis de experiência! Veja como você pode começar:

### 1. Faça um Fork do Projeto

Crie uma cópia do repositório no seu GitHub clicando no botão **Fork**.

### 2. Clone o Repositório

Clone o repositório do seu fork localmente com o seguinte comando:

git clone https://github.com/sua-conta/sistema-de-gestao-escolar.git


---

### 4. Configure o Banco de Dados
Certifique-se de ter o PostgreSQL instalado e configure a conexão ao banco de dados criando um arquivo .env com as seguintes variáveis de ambiente:

DATABASE_URL="postgresql://postgres:sua_Senha@localhost:5432/sgedb?schema=public"

- ## JWT_SECRET=sua_chave_secreta.
- ## SMTP_USER=
- ## SMTP_PASS=
- ## SMTP_HOST=smtp.gmail.com



---

## 6.Para o app mobile, vá até a pasta do projeto mobile e execute:

expo start

## 6. Faça Suas Alterações e Submeta
  Após fazer suas alterações no código:
  
  1. Crie uma branch para sua funcionalidade:
     git checkout -b feature/minha-funcionalidade
     
2.  Adicione suas mudanças:
   git add .

3.Faça o commit das mudanças:
git commit -m "Adiciona funcionalidade X"

4. Envie para seu fork:
   git push origin feature/minha-funcionalidade

5. Abra um Pull Request no repositório original e descreva sua contribuição.

### Como Reportar Problemas 🐛
Se você encontrar bugs ou tiver sugestões de melhoria, abra uma issue no GitHub.

# Passos para abrir uma issue:
1. Vá até a seção de Issues.
2. Clique em New Issue.
3. Descreva o problema ou sugestão de forma clara, adicionando prints ou logs quando necessário.

## Código de Conduta
Por favor, leia o  [Código de Conduta](./CODE_OF_CONDUCT.md) para garantir que o ambiente de colaboração seja inclusivo e respeitoso para todos os participantes.


## Licença
Este projeto está licenciado sob a MIT License.

## Entre em Contato
Se você tiver dúvidas, sugestões ou quiser conversar sobre o projeto, fique à vontade para abrir uma issue ou entrar em contato diretamente.

Junte-se ao nosso time e ajude a construir um sistema de gestão escolar completo e open-source! 🚀

## Comunidade no Discord 

entre na nossa comunidade [no Discord](https://discord.gg/abhjuExh) lá postamos conteúdos e desáfios para você resolver e também descutimos projetos futuras e  presente.

Agradecimentos
Obrigado a todos os colaboradores que estão tornando esse projeto possível!
