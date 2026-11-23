# 👨‍💻 Marcio Henare

### Suporte de TI & Infraestrutura | Cybersecurity | Python | IA & Automação

Profissional de TI com experiência em **suporte, infraestrutura, Windows, Microsoft 365 e redes**, hoje focado em **Cybersecurity, Pentest, Python e Inteligência Artificial**.

Aprendo construindo: **laboratórios, ferramentas e projetos reais**, documentados aqui no GitHub.

---

## 🚀 Projetos em destaque

### 🗣️ English Speaking Coach

Agente de IA para **treinar inglês falado por voz, em tempo real** (speech-to-speech). A ideia é simples: ajudar o aluno brasileiro (A2–B1) a **perder a vergonha de falar**, conversando com um coach que acompanha o assunto dele de forma natural.

- 🎙️ Conversa por voz direto no navegador, sem digitar
- 🇺🇸 Tutor 100% em inglês, com respostas curtas e naturais
- 📝 Transcrição em tempo real da fala do aluno e do coach
- 🗄️ Histórico de sessões salvo em SQLite
- 💸 Pensado para ser gratuito e, no futuro, rodar no Android

```text
Navegador (microfone)
        │  áudio PCM
        ▼
Servidor FastAPI (WebSocket)
        │
        ▼
Gemini Live API ──► áudio + transcrição ──► navegador
        │
        ▼
     SQLite (sessões e mensagens)
```

**Stack:** Python · FastAPI · WebSocket · Gemini Live API · SQLite · JavaScript

**Status:** voz funcionando no navegador. Em evolução: naturalidade das respostas, correções durante a conversa e versão mobile.

---

### 🔴 LAB-PENTEST

Laboratório autorizado de **Cybersecurity e Pentest** com ambientes Windows e Linux, cobrindo o ciclo ofensivo completo: reconhecimento, enumeração, Active Directory, análise de vulnerabilidades, exploração controlada, pós-exploração e documentação técnica.

| Máquina | Função |
|---|---|
| Kali Linux | Estação de pentest |
| Windows Server 2025 | Active Directory |
| Windows 7 | Exploração |
| Metasploitable2 | Alvo vulnerável |

**Stack:** Kali Linux · Nmap · Metasploit · Active Directory · Hyper-V · SSH

🔗 [github.com/HenareMarcio/LAB-PENTEST](https://github.com/HenareMarcio/LAB-PENTEST)

---

## 🧪 Outros projetos

| Projeto | Descrição | Stack |
|---|---|---|
| [CHAT_BOOT_2](https://github.com/HenareMarcio/CHAT_BOOT_2) | Chatbot com RAG e busca semântica local | Python, Chainlit, ChromaDB, OpenRouter |
| [Sho-AI](https://github.com/HenareMarcio/Sho-AI) | Interface web integrada a modelos de IA | Python, Streamlit |
| [dio-lab-open-source](https://github.com/HenareMarcio/dio-lab-open-source) | Git, GitHub e colaboração Open Source (DIO) | Git, GitHub |

---

## 🛠️ Tecnologias

**🔐 Segurança:** Kali Linux · Nmap · Metasploit · Active Directory · Vulnerability Assessment

**🐍 Desenvolvimento & IA:** Python · FastAPI · APIs · RAG · LLMs · Streamlit · Chainlit

**🖥️ Infraestrutura:** Windows · Windows Server · Linux · Redes · Microsoft 365 · Hyper-V

**🔧 Ferramentas:** Git · GitHub · VS Code · PowerShell · Bash

---

## 📫 Contato

🌐 [GitHub](https://github.com/HenareMarcio) · 💼 [LinkedIn](https://www.linkedin.com/in/marcio-henare-079320160)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=HenareMarcio&show_icons=true&hide_border=true&theme=transparent)

> *"Aprender, construir, documentar e evoluir todos os dias."*
