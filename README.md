<div align="center">
  <img src="./assets/profile-banner.svg" alt="Davi Silva Soares — desenvolvedor full stack" width="100%" />

  <br />

  <a href="https://github.com/dsoares22"><img src="https://img.shields.io/badge/GitHub-dsoares22-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub: dsoares22" /></a>
  <a href="https://www.linkedin.com/in/davi-silva-soares-469b9235b/"><img src="https://img.shields.io/badge/LinkedIn-Davi%20Silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn de Davi Silva" /></a>
  <a href="mailto:davisilvasoares1@gmail.com"><img src="https://img.shields.io/badge/Email-Fale%20comigo-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Enviar e-mail para Davi" /></a>
</div>

## Olá, eu sou Davi Silva Soares

Desenvolvedor **full stack** e estudante de **Engenharia de Software** em Teresina, Piauí. Gosto de transformar uma necessidade real em uma aplicação que funcione de ponta a ponta: da regra de negócio no backend até a tela que a pessoa vai usar.

- ☕ Construo APIs REST com **Java e Spring Boot**
- 🎨 Crio interfaces com **Vue 3**, HTML, CSS e JavaScript
- 🗄️ Modelo e consulto dados em **PostgreSQL**, incluindo o Supabase
- 🔐 Já implementei **autenticação com JWT**, rotas protegidas e isolamento de dados por empresa
- 🤝 Desenvolvo sites e sistemas para clientes reais, como a WS Assessoria Comercial
- 🌱 Estudando agora: **Python e Django**

## 🧰 Tecnologias

| Área | Ferramentas |
| --- | --- |
| **Backend** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| **Frontend** | ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logo=vuedotjs&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) |
| **Dados e autenticação** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| **Ferramentas e deploy** | ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white) |

## 🚀 Projetos em destaque

### 📦 [EstoqueFácil](https://github.com/dsoares22/Estoquefacil)

Aplicação multiempresa para controlar produtos e movimentações de estoque. Cada empresa tem seus próprios produtos, usuários e histórico, identificados por um `tenant_id`.

- Login com senha protegida por **BCrypt** e **JWT** válido por 24 horas
- Cadastro e busca de produtos por nome ou SKU, com filtros de estoque baixo ou zerado
- Entradas e saídas atualizam o saldo na mesma transação, e saídas acima do saldo são bloqueadas
- Histórico de movimentações por empresa, da mais recente para a mais antiga

`Java 17` · `Spring Boot` · `Spring Security` · `Spring Data JPA` · `PostgreSQL` · `Vue 3`

**[Explorar o projeto →](https://github.com/dsoares22/Estoquefacil)**

---

### 📅 [WS Agenda Online](https://github.com/dsoares22/ws_agenda)

Sistema de agendamento de visitas para a **WS Consultoria**, desenvolvido em equipe na disciplina de Programação Web. Colaboradores autenticados cadastram, editam e excluem atendimentos e acompanham os números em um dashboard.

- Login e logout com **Supabase Auth**, sessão gerenciada com Pinia
- Rotas protegidas com redirecionamento automático para o login
- CRUD completo de atendimentos, com status colorido e confirmação antes de excluir
- Dashboard com indicadores de atendimentos (hoje, semana e por responsável), calculados por uma view SQL
- API REST própria em Express

`Vue 3` · `Pinia` · `Vue Router` · `Bootstrap` · `Node.js` · `Express` · `Supabase/PostgreSQL`

**[Explorar o projeto →](https://github.com/dsoares22/ws_agenda)**

---

### ⚽ [API de Jogadores](https://github.com/dsoares22/api_jogadores)

Aplicação full stack para cadastrar, consultar e analisar jogadores de futebol. O backend aplica regras de negócio e a interface em Vue permite navegar e editar os dados.

- Um jogador só pode ser titular se estiver ativo e tiver pelo menos 5 partidas
- Desempenho classificado automaticamente pela média de gols por partida: Excelente, Bom ou Regular
- Validação de entrada (`400`) e tratamento de registros inexistentes (`404`)
- Acesso ao banco com Spring JDBC

`Java 17` · `Spring Boot` · `Spring JDBC` · `PostgreSQL` · `Vue 3` · `Vite`

**[Explorar o projeto →](https://github.com/dsoares22/api_jogadores)**

---

### 🌐 [Site WS Assessoria Comercial](https://github.com/dsoares22/Site-Wsconsultoria)

Landing page publicada para uma empresa de consultoria imobiliária e assessoria documental, com atuação em Timon e Teresina. Projeto real, no ar.

- Layout responsivo para computador, tablet e celular
- Formulário de contato por e-mail, botões de WhatsApp e Instagram e mapa com a localização da empresa
- Seções HTML separadas e carregadas por JavaScript, o que facilita a manutenção
- Publicação contínua na Netlify

`HTML5` · `CSS3` · `JavaScript` · `Netlify`

**[Ver o código →](https://github.com/dsoares22/Site-Wsconsultoria)** · **[Acessar o site →](https://wsassessoriacomercial.netlify.app/)**

---
<div align="center">
  <a href="mailto:davisilvasoares1@gmail.com">📧 E-mail</a> ·
  <a href="https://www.linkedin.com/in/davi-silva-soares-469b9235b/">💼 LinkedIn</a>
</div>
