# 🧾 Admissão Digital — Norte Tech

## 📋 Sobre o Projeto

O **Admissão Digital** é o protótipo navegável de um portal de recrutamento e admissão para a **Norte Tech**. A ideia é tirar do papel e do WhatsApp todo o caminho do candidato: encontrar a vaga, se inscrever com um currículo virtual, acompanhar o status, receber a proposta e enviar os documentos de admissão.

Esta versão é o **front-end em HTML, CSS e JavaScript puro**, usado para validar fluxo, telas e identidade visual com o RH antes da implementação do backend. O sistema de recrutamento completo (ATS) evoluiu depois no [NorteTech-Site](https://github.com/LuizPitohui/NorteTech-Site), em Django.

## 🚀 Tecnologias Utilizadas

- **HTML5** semântico
- **CSS3** modular (um arquivo por área: base, navbar, formulários, home, vaga, status)
- **JavaScript** puro para interações (prévia e remoção de anexos, botões de ação)
- **Fonte:** Nunito (Google Fonts)
- Sem dependências nem etapa de build

---

## ✨ Telas (visão do candidato)

| Tela | Arquivo | O que faz |
|------|---------|-----------|
| 🏠 Portal de vagas | `index.html` | Busca e lista de vagas abertas |
| 📄 Detalhe da vaga | `vaga_detalhe.html` | Descrição, requisitos e botão de candidatura |
| 🔑 Login | `login.html` | Acesso à conta do candidato |
| 📝 Criar conta | `registrar.html` | Currículo virtual: dados pessoais, CPF, competências, upload do currículo (PDF/DOCX) e foto |
| 👤 Perfil | `perfil.html` | Edição dos dados e do currículo |
| 📌 Minhas inscrições | `minhas_vagas.html` | Status de cada candidatura |
| ✅ Confirmação | `confirmacao.html` | Retorno após se candidatar |
| 🔔 Notificações | `notificacoes.html` | Avisos sobre as candidaturas |
| 🤝 Proposta | `proposta.html` | Proposta recebida, com opção de aceitar ou recusar |

---

## 🔧 Como Rodar

Não precisa de instalação. Clone e abra o `index.html` no navegador:

```bash
git clone https://github.com/LuizPitohui/admiss-o-digital---norte-tech.git
cd admiss-o-digital---norte-tech
```

Ou sirva a pasta localmente para navegar entre as páginas:

```bash
python -m http.server 8080
# acesse http://localhost:8080
```

---

## 📂 Estrutura

```
admiss-o-digital---norte-tech/
├── index.html            # Portal de vagas
├── vaga_detalhe.html
├── login.html
├── registrar.html
├── perfil.html
├── minhas_vagas.html
├── confirmacao.html
├── notificacoes.html
├── proposta.html
└── css/
    ├── base.css          # Variáveis, tipografia e reset
    ├── navbar.css
    ├── forms.css
    ├── home.css
    ├── vaga.css
    ├── status.css
    └── style.css
```

---

## 🗺️ Próximos Passos

**Visão do candidato**
- Tela de anexo de documentos com introdução, observações importantes, prazo e status de cada anexo
- Notificações dentro do sistema em formato reduzido
- Vagas também divulgadas via WhatsApp
- Mensagem padrão de e-mail com resumo da candidatura

**Visão do RH/DP**
- Formulário de cadastro de processos seletivos
- Lista de processos em aberto com ações: ver candidaturas, editar e concluir processo

**Identidade visual:** mais cor, visual moderno e linguagem amigável.
