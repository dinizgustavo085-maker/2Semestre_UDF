# 📱 Portal do Aluno — Mobile UX/UI Design
 
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![UI/UX](https://img.shields.io/badge/UX-Design-blueviolet?style=for-the-badge)
![ADS](https://img.shields.io/badge/ADS-Project-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Protótipo%20Concluído-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/Licença-MIT-yellow?style=for-the-badge)
 
---
 
## 📌 Objetivo
 
Projetar a experiência de usuário (UX) e a interface visual (UI) de um **Sistema de Gestão Acadêmica Mobile**, centralizando em um único aplicativo informações fragmentadas do cotidiano universitário — como calendário acadêmico, materiais de estudo e desempenho por disciplina.
 
O projeto visa entregar um protótipo de alta fidelidade, pronto para ser utilizado como base para implementação em **React Native**, com foco em usabilidade, acessibilidade e escalabilidade do design system.
 
---
 
## 🧭 Contexto
 
### Cenário de Uso — Educação & Rotina Acadêmica
 
> **Plataforma do Estudante:** Um estudante acessa um sistema acadêmico digital que centraliza informações sobre disciplinas, prazos, atividades e entregas.
 
| | |
| :--- | :--- |
| 🎯 **Tarefa Principal** | Descobrir quais atividades precisa entregar na semana e enviar uma delas |
| 👤 **Perfil do Usuário** | Universitário desorganizado, sobrecarregado e com pouco tempo disponível |
| ⚠️ **Desafio UX** | Organizar grandes volumes de informação com clareza, hierarquia e orientação à ação |
 
### Problema Real
 
Estudantes universitários frequentemente lidam com informações dispersas em diferentes plataformas: portais web lentos, grupos de WhatsApp, e-mails institucionais e planilhas pessoais. Essa fragmentação gera **perda de prazos**, dificuldade de acompanhar o desempenho acadêmico e sobrecarga cognitiva.
 
O **Portal do Aluno** nasce como resposta direta a esse problema, propondo uma interface mobile-first que consolida todas essas informações em uma experiência intuitiva, fluida e orientada à ação.
 
> **Contexto acadêmico:** Projeto desenvolvido no curso de **Análise e Desenvolvimento de Sistemas — UDF**, aplicando conceitos de User-Centered Design e boas práticas de UI para sistemas móveis.
 
---
 
## 🎯 Critérios de Sucesso
 
| Critério | Descrição |
| :--- | :--- |
| ✅ **Usabilidade** | Fluxos concluídos em no máximo 3 taps a partir do Dashboard |
| ✅ **Legibilidade** | Tipografia e contraste adequados para leitura em telas pequenas |
| ✅ **Consistência** | Design System aplicado com componentes reutilizáveis em todas as telas |
| ✅ **Alcançabilidade** | CTAs posicionados na zona de calor do polegar (thumb zone) |
| ✅ **Feedback Visual** | Estados de erro, sucesso e carregamento mapeados |
| ✅ **Escalabilidade** | Componentização que facilita a futura implementação em código |
| ✅ **Orientação à Ação** | Prazos e pendências sempre visíveis, com destaque para entregas urgentes |
 
---
 
## 🗂️ Formato Esperado — Entregáveis
 
```
📦 Portal do Aluno
 ┣ 🎨 Protótipo Interativo (Figma)
 ┃  ┣ Wireframes (Low-Fidelity)  — Frame 1
 ┃  ┣ Wireframes Intermediários  — Frame 2
 ┃  └ Protótipo Alta Fidelidade  — Frame 3+
 ┃
 ┣ 🧩 Design System
 ┃  ┣ Tokens de cor, tipografia e espaçamento
 ┃  ┣ Componentes: Botões, Inputs, Cards, Ícones
 ┃  └ Estados: Default, Hover, Error, Disabled
 ┃
 └ 📄 Documentação (este README)
```
 
---
 
## 📸 Visão Geral das Telas
 
> Todas as telas abaixo foram desenhadas no Figma, do wireframe de baixa fidelidade ao protótipo final de alta fidelidade.
 
<div align="center">
 
<img src="assets/screens.png" width="800"/>
 
</div>
 
### 🔍 Detalhamento por Fluxo
 
| Tela | Funcionalidade Principal | Componentes-Chave |
| :--- | :--- | :--- |
| **Login / Change Password** | Acesso seguro e recuperação de credenciais | Input, Button CTA, Feedback de erro |
| **Dashboard** | Boas-vindas, atalhos rápidos para todas as seções | Cards de acesso, Bottom Nav, Avatar |
| **Courses** | Lista de disciplinas matriculadas | Cards de matéria, Ícones por categoria |
| **Courses Detail** | Detalhe da disciplina: professor, conteúdo, frequência e notas | Tabs (Grades / Content / Attendance), Lista de materiais |
| **Notifications** | Central de avisos e comunicados da instituição | Lista de notificações, Badge, Timestamp |
| **Academic Calendar** | Grade mensal interativa para controle de prazos e provas | Calendário com marcadores coloridos por tipo de evento |
| **Activities by Subject** | Atividades pendentes e entregues por disciplina | Cards de tarefa, Status chip, Deadline |
| **New Task** | Criação e acompanhamento de novas tarefas | Form, Date picker, Dropdown de disciplina |
 
---
 
## 🏗️ Arquitetura de Informação
 
```
App
├── Autenticação
│   ├── Login
│   └── Change Password
│
└── Área do Aluno (autenticado)
    ├── Dashboard          → Resumo do dia + atalhos rápidos
    ├── Courses            → Lista de disciplinas matriculadas
    │   └── Course Detail  → Notas, conteúdo e frequência
    ├── Notifications      → Avisos institucionais
    ├── Calendar           → Grade mensal interativa
    └── Activities         → Tarefas por disciplina
        └── New Task       → Criar nova tarefa
```
 
---
 
## 🎨 Design System
 
### Processo de Design — 3 Fases
 
| Fase | Descrição |
| :--- | :--- |
| **Frame 1 — Low-Fidelity** | Wireframes em escala de cinza para validação de fluxo e arquitetura |
| **Frame 2 — Mid-Fidelity** | Estrutura com hierarquia visual, tipografia e grid definidos |
| **Frame 3+ — High-Fidelity** | Protótipo final com componentes, estados e interações completas |
 
### Boas Práticas de UX Aplicadas
 
- 👍 **Thumb Zone:** Botões de ação principal (CTAs) posicionados na zona de fácil alcance do polegar
- ⚡ **Feedback Imediato:** Estados visuais de erro, sucesso e loading mapeados em todos os formulários
- 🧹 **Hierarquia Clara:** Uso de tamanho, peso e cor para guiar o olhar sem sobrecarga cognitiva
- 📐 **Grid de 4 colunas** com margens de 16px para dispositivos móveis
- 🔁 **Componentização total:** Botões, inputs, ícones e cards reutilizáveis — espelhando a lógica do React Native
- 🚨 **Urgência visível:** Prazos próximos destacados com cor e badge para usuários com pouco tempo disponível
 
---
 
## 🛠️ Tecnologias e Ferramentas
 
| Ferramenta | Uso |
| :--- | :--- |
| **Figma** | Design, prototipagem e Design System |
| **React Native** *(planejado)* | Implementação do frontend mobile |
| **PostgreSQL** *(planejado)* | Banco de dados relacional para persistência |
 
---
 
## 🔗 Acesso ao Protótipo
 
Acesse o protótipo interativo completo diretamente no Figma:
 
[![Abrir no Figma](https://img.shields.io/badge/Abrir%20Protótipo%20no%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/3u0Ksusbyrhatyvk8Lxpc5/Sem-t%C3%ADtulo?node-id=0-1&t=OuG704Tm9ulBxClT-1)
 
> 💡 **Dica:** Use o modo de apresentação (`▶ Play`) no canto superior direito do Figma para navegar pelos fluxos interativos.
 
---
 
## 👤 Autor
 
**Gustavo Alves de Melo Diniz**
*Estudante de Análise e Desenvolvimento de Sistemas — UDF*
 
---
 
## 📄 Licença
 
Este projeto está sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
