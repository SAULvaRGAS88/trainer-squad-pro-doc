# 🏋️‍♂️ Trainer Squad Pro • Documentação Oficial
📌 *Sistema de gestão para Personal Trainers e Alunos*

---

👨‍💻 **Desenvolvido por:** Saul Vargas  
📘 **Propósito:** Documentação do projeto final da unidade curricular **Projeto de Desenvolvimento II**  
🎓 **Curso:** Análise e Desenvolvimento de Sistemas  
🏛️ **Instituição:** Centro Universitário Senac-RS — Unidade Porto Alegre  
📍 **Endereço:** Rua Coronel Genuino, 130 — Centro, Porto Alegre, RS

---

> Esta documentação tem como objetivo registrar o desenvolvimento, as decisões técnicas e as funcionalidades implementadas no projeto **Trainer Squad Pro**.

---

## 🎤 Pitch

👥 **Público-alvo:** Profissionais de Educação Física que atuam como Personal Trainers e seus respectivos alunos.

- **Desafios dos Personais:** organização da agenda, controle de treinos e recebimentos.  
- **Dificuldades dos Alunos:** agendamento de treinos, acompanhamento de pagamentos e comunicação com seu Personal.

💡 **Trainer Squad Pro** é um **web app responsivo** que simplifica a rotina do Personal Trainer e de seus alunos.

> Diferente das ferramentas atuais, com dados espalhados e desconectados, nosso produto centraliza todas as informações em um único lugar.  
> Facilitando o dia a dia do Personal, melhora o controle sobre seu trabalho e fortalece a conexão com seus alunos.

🤝 **Trainer Squad:** integração real entre Personal e aluno, caminhando juntos rumo aos resultados.

---

## 📌 Canvas MVP

### ✅ Proposta do MVP

Entregar um produto funcional e intuitivo que atenda tanto os **Personais** quanto os **Alunos**, com funcionalidades adaptadas para cada perfil de usuário.  
O objetivo é **centralizar tarefas do dia a dia**, facilitando o uso e aumentando a produtividade e o engajamento.

---

### 🎯 Personas

- 👤 **Personal Trainers** autônomos ou atuantes em academias.  
- 👥 **Alunos** que buscam praticidade para marcar treinos e acompanhar seus pagamentos.

---

### 🧭 Jornadas Atendidas

#### 🔸 Personal Trainer

- Cadastro e gerenciamento de alunos  
- Criação de treinos personalizados  
- Controle de agenda  
- Gestão financeira  

#### 🔸 Aluno

- Marcação e confirmação de treinos  
- Visualização do perfil e treinos  
- Acompanhamento de pagamentos  

---

### ⚙️ Funcionalidades do MVP

- Login com perfis distintos (Personal e Aluno)  
- Visualização e agendamento de treinos  
- Cadastro de treinos e controle financeiro  
- Histórico de treinos e pagamentos  
- Comunicação interativa entre Personal e Aluno (via atividades e registros)

---

### 🎯 Resultado Esperado

- Verificar se a solução **facilita a rotina dos Personais**  
- Avaliar a **facilidade de uso para os Alunos**  
- Medir o **interesse em continuar utilizando a plataforma**

---

### 💰 Custo & Cronograma

- ⏳ **Custo estimado:** 60h de design e desenvolvimento inicial  
- 📅 **Entrega do MVP:** 11/07/2025  
- 🧪 **Período de testes:** 1 semana após o lançamento  
- 📊 **Análise de decisão:** após o período de testes, os dados e feedbacks coletados serão utilizados para definir os próximos passos da plataforma.

---

## 🧰 Stacks Utilizadas

Este projeto foi desenvolvido utilizando um conjunto moderno de tecnologias tanto para o front-end quanto para o back-end, repositório e deploy:

| Categoria         | Tecnologias |
|------------------|-------------|
| **Back / Banco** | 🔥 [Firebase](https://firebase.google.com/) – Backend como serviço, utilizado para autenticação e banco de dados. |
| **Front-end**    | ⚡ [Vite](https://vitejs.dev/) – Bundler rápido e moderno.<br>⚛️ [React JS](https://react.dev/) – Biblioteca para construção da interface.<br>🎨 [Bootstrap 5](https://getbootstrap.com/) – Framework CSS para layout e responsividade. |
| **Repositório**  | 🐙 [GitHub](https://github.com/) – Hospedagem de código e controle de versão. |
| **Deploy**       | ▲ [Vercel](https://vercel.com/) – Plataforma de deploy contínuo para aplicações front-end. |
## 🛠️ Stack Tecnológica

<div align="center">

| Tecnologia       | Imagem |  
|------------------|--------|
| **Firebase**     | <img src="https://github.com/user-attachments/assets/766f4108-381d-41de-b9c2-1523b47955eb" width="120" alt="Logo Firebase"> |  
| **Vite**         | <img src="https://github.com/user-attachments/assets/ac84c588-d0cc-4a05-b593-e1e1d235a31d" width="120" alt="Logo Vite"> |  
| **GitHub**       | <img src="https://github.com/user-attachments/assets/726833b4-0896-4b5e-9a1f-ef4f2da99436" width="120" alt="Logo GitHub"> |  
| **Vercel**       | <img src="https://github.com/user-attachments/assets/ef6c43f8-582a-4e84-915f-9b4c658344be" width="120" alt="Logo Vercel"> |  
| **React.js**     | <img src="https://github.com/user-attachments/assets/1c227e25-1df4-4882-b6b4-a8e30c9ea5ec" width="120" alt="Logo React"> |  
| **Bootstrap**    | <img src="https://github.com/user-attachments/assets/5f2dc872-c7ff-471c-b9c6-70411c7ce854" width="120" alt="Logo Bootstrap"> |  
| **MUI Material** | <img src="https://github.com/user-attachments/assets/a38ba3a4-9f4a-43c1-b4bc-7bb6e97db284" width="120" alt="Logo Material UI"> |  

</div>

📌 *Todas as imagens são ilustrativas e representam as tecnologias utilizadas no projeto*

---

## 🔁 Fluxo de Uso do MVP

Abaixo, um diagrama de alto nível representando como os usuários interagem com a aplicação:

<div style="font-size: 24px; font-family: Arial, sans-serif;">

### 🔄 **Fluxo do Sistema**  
| **🎯 Personal Trainer**       | **👤 Aluno**                |
|-------------------------------|-----------------------------|
| 🔐 `Login`                    | 🔐 `Login`                  |
| ⬇️                            | ⬇️                          |
| 📊 `Agenda`                   | 🏋️ `Ver perfil`             |
| ⬇️                            | ⬇️                          |
| 👥 `Cadastrar Aluno`          | 📅 `Marcar Sessão`          |
| ⬇️                            | ⬇️                          |
| 📝 `Criar Treino`             | 💳 `Confirmar Pagamento`    |
| ⬇️                            |                             |
| 💰 `Acompanhar Pagamentos`    |                             |

</div>
---

# 🧑‍🏫 **Para Personais**  
- 📅 Gestão de agenda  
- 💸 Controle financeiro  
- 📊 Avaliações físicas  

# 🧑‍🎓 **Para Alunos**  
- 🏋️ Treinos personalizados  
- 🔔 Lembretes automáticos  
- 💬 Chat integrado

---

> "Ferramenta tudo-em-um para gestão de treinos, alunos e finanças com tecnologia de ponta."

---
## 🖼️ Protótipos de Interface - Perfil Personal

Prototipagem das principais telas desenvolvidas para o sistema:

### **📱 Tela Inicial (Dashboard)**
![Dashboard Personal](https://github.com/user-attachments/assets/61b661f6-1502-4b75-8e92-f1d74f06c0d6)  
*Visão geral do perfil do personal trainer com métricas e acesso rápido*

---

### **📅 Tela de Agenda**
![Agenda](https://github.com/user-attachments/assets/23a6e0aa-26eb-4841-bc51-b3a52fa2ec1c)  
*Controle de sessões agendadas com visualização por dia/semana/mês*

---

### **👥 Relação de Alunos**
![Alunos](https://github.com/user-attachments/assets/230d9065-1a36-468e-b2e8-bc66af00a3cd)  
*Listagem completa de alunos com filtros e status de treino*

---

### **💰 Gestão Financeira**
![Financeiro](https://github.com/user-attachments/assets/87495e60-9d16-4065-89a7-d84e38cf0804)  
*Controle de pagamentos, recebimentos e relatórios financeiros*

---

### **🏋️ Treino & Mensagens**
![Treino](https://github.com/user-attachments/assets/cf0a4b3d-64f3-4625-8fad-d75f97302c2a)  
*Editor de treinos e sistema de mensagens integrado*

---

## 👤 Protótipos - Perfil Aluno (Mobile Responsivo)

### **📱 Dashboard Aluno**  
![Dashboard Aluno](https://github.com/user-attachments/assets/0ba414f3-5e11-446b-9772-75e02cd62022)  
*Visão do aluno com:*  
- ✔️ Regras de uso do sistema  
- 🕒 Status de treinos  
- 📅 Módulo de agendamento integrado  

---

### **💬 Treino & Mensageria**  
<div style="display: flex; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/925cc1c1-04d7-4b45-b118-5942a23048f6" width="45%" alt="Tela de Treinos">
  <img src="https://github.com/user-attachments/assets/d9d2931a-ad8a-4ceb-b6cb-a3d8813dbdc5" width="45%" alt="Chat de Mensagens">
</div>  
*Fluxo completo:*  
1. 🏋️‍♂️ Visualização de treinos atribuídos  
2. ✉️ Comunicação direta com o personal trainer  

---

### **⏱️ Autoatendimento - Agendamento**  
![Agendamento Aluno](https://github.com/user-attachments/assets/5dac24a4-feb4-45dc-a85b-d1d1c18550d8)  
*Funcionalidades:*  
- 📆 Calendário interativo  
- 🎯 Seleção de horários disponíveis  
- 🔔 Notificações de confirmação  
</div>

---
# 🔒 Projeto Privado

Este é um projeto de acesso restrito. Para solicitar permissão ou mais informações, utilize os canais oficiais:

## 📬 Contatos para Acesso

<div style="font-family: Arial, sans-serif;">

| Ícone | Canal        | Contato/Link |
|-------|--------------|--------------|
| 📧    | **E-mail**   | <a href="mailto:saulvargascosta@hotmail.com" target="_blank">saulvargascosta@hotmail.com</a> |
| 💬    | **WhatsApp** | <a href="https://wa.me/5551985027412" target="_blank">(51) 98502-7412</a> |
| 🔗    | **LinkedIn** | <a href="https://www.linkedin.com/in/saul-vargas-68a97347/" target="_blank">Saul Vargas</a> |

</div>

---

### 📋 Processo de Solicitação:
1. Envie sua solicitação por um dos canais acima  
2. Especifique:  
   - 🏢 Sua instituição/organização  
   - 🎯 Objetivo do acesso  
3. Aguarde análise do time responsável  

---

⚠️ **Atenção**:  
- Todos os direitos reservados  
- Dados e materiais são confidenciais  
- Acesso sujeito a aprovação  
