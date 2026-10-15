<div align="center">
  <h1>SuS_ChatBot</h1>

  <p>
    <strong>Um ecossistema de Chatbot focado na gestão de dados através de um Painel de Controle robusto.</strong><br>
    <em>Pensamentos e Códigos para projeto pessoal</em>
  </p>

  <img src="https://img.shields.io/badge/Status-Em_Planejamento-orange?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Projeto-Pessoal-blue?style=for-the-badge" alt="Projeto Pessoal" />
  <img src="https://img.shields.io/badge/Linguagem_Principal-Java-red?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
</div>

<br>

> [!NOTE]  
> Este projeto encontra-se na sua fase inicial de ideação. Este repositório serve atualmente como um "Diário de Bordo" para o armazenamento de ideias, rascunhos de arquitetura e protótipos de código.

## Sobre o Projeto

O **SuS_ChatBot** nasce da necessidade de centralizar o atendimento e a gestão das informações. Diferente de sistemas convencionais onde o bot é o único foco, o "coração" deste projeto é o seu **Painel de Controle (Dashboard)**. É através do painel que todo o fluxo conversacional e os dados recolhidos pelo chatbot serão administrados, analisados e armazenados diretamente no Banco de Dados.

### Principais Recursos Planejados

*   **Painel Administrativo (Core):** Interface web para monitorizar métricas, gerir os dados e aceder ao histórico de interações.
*   **Integração com Banco de Dados:** Armazenamento centralizado, seguro e estruturado de todas as informações geradas.
*   **Chatbot Interativo:** Interface conversacional dinâmica para o utilizador final interagir com o sistema.
*   **Gestão de Fluxos:** Capacidade de adaptar e monitorizar o comportamento do bot diretamente através do painel.

---

## Arquitetura e Pensamentos Iniciais

Como este é um projeto em construção, este espaço é dedicado à organização do raciocínio e estruturação dos próximos passos lógicos:

### Base de Desenvolvimento
*   **Backend (API):** A espinha dorsal do projeto será desenvolvida em **Java**, servindo como a ponte segura e escalável entre o Painel, o Chatbot e o Banco de Dados. Será avaliada a utilização do framework *Spring Boot* para agilizar a criação de APIs REST.
*   **Frontend (Painel):** Necessário escolher um framework reativo (como *React* ou *Vue.js*) para consumir a API Java e criar um dashboard analítico interativo e rápido.
*   **Banco de Dados:** A infraestrutura precisa suportar alta capacidade de leitura/escrita devido ao volume de logs gerados pelo chat. Bancos relacionais robustos como *PostgreSQL* são os principais candidatos.

### Roadmap

- [x] Ideação e definição do escopo principal (Painel > DB > Bot).
- [x] Criação do repositório base e estruturação do README.
- [ ] Desenho do Diagrama de Entidade-Relacionamento (DER) do Banco de Dados.
- [ ] Construção do design e protótipo visual do Painel de Controle.
- [ ] Configuração do ambiente de desenvolvimento Java e repositório.
- [ ] Criação do projeto base (API) e conexão com o Banco de Dados escolhido.
- [ ] Desenvolvimento da interface do Painel e integração com a API.
- [ ] Desenvolvimento da lógica e motor do Chatbot.

---

## Stack Tecnológica Potencial

<div align="center">
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown" />
</div>

<br>

> [!TIP]
> Acompanhe os commits neste repositório para ver a evolução da arquitetura e as primeiras implementações de código.
