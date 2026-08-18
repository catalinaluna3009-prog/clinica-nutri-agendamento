![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License MIT](https://img.shields.io/badge/license-MIT-blue)

# ClinicaNutri - Sistema de Autoagendamento

**Status do Projeto:** 🟡 Em Desenvolvimento (Fase de Escopo)

---

## Índice
- [Descrição do Projeto](#descrição-do-projeto)
- [Funcionalidades Principais](#funcionalidades-principais)
- [Pré-requisitos](#pré-requisitos)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Documentação Complementar](#documentação-complementar)

---

## Descrição do Projeto
Plataforma web voltada para o autoagendamento de consultas em clínica de nutrição. O sistema reduz a taxa de faltas enviando lembretes automáticos 24h antes do atendimento e gerando alertas na tela da recepcionista para contato telefônico caso o paciente não responda.

## Funcionalidades Principais
- **Autoagendamento pelo Paciente:** Escolha de horários vagos em poucas etapas.
- **Lembrete Automático (24h):** Notificação com opção de confirmação ou cancelamento direto.
- **Painel de Alertas da Recepção:** Destaque visual dos pacientes pendentes de resposta.
- **Proteção de Dados:** Criptografia de contatos em conformidade com a LGPD.

## Pré-requisitos
- Node.js (v18+)
- Git

## Como Executar o Projeto
```bash
# 1. Clonar o repositório
git clone [https://github.com/seu-usuario/clinica-nutri-agendamento.git](https://github.com/seu-usuario/clinica-nutri-agendamento.git)

# 2. Entrar na pasta do projeto
cd clinica-nutri-agendamento

# 3. Instalar dependências
npm install

# 4. Iniciar a aplicação
npm run dev
