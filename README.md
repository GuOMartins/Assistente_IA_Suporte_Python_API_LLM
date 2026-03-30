#  Assistente de Programação Python – Estudo de Caso DSA AI Coder

[![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Groq](https://img.shields.io/badge/Groq-API-00C7B7)](https://console.groq.com/)
[![Licença MIT](https://img.shields.io/badge/Licença-MIT-green.svg)](LICENSE)

##  Descrição

Projeto de um assistente virtual especializado em responder dúvidas sobre a linguagem Python, utilizando um modelo de linguagem (LLM) via API da **Groq**. Desenvolvido como parte do curso **DSA AI Coder**, com interface interativa construída em **Streamlit**. O assistente mantém contexto da conversa e fornece explicações e exemplos de código.

##  Tecnologias utilizadas

- **Python 3.13** – linguagem principal
- **Streamlit** – interface web interativa
- **Groq API** – modelo de linguagem de alta performance
- **python-dotenv** – gerenciamento de variáveis de ambiente
- **Conda** (opcional) – gerenciamento de ambientes virtuais

##  Funcionalidades

- Respostas automatizadas sobre sintaxe, conceitos e exemplos em Python
- Interface web amigável e responsiva
- Manutenção do histórico da conversa durante a sessão
- Tratamento de erros (API offline, chave inválida, etc.)
- Configuração segura da chave de API via arquivo `.env`
- Código modular e pronto para personalização

---

##  Instalação e execução

### 1️ Pré‑requisitos

Antes de começar, certifique‑se de ter instalado:

- **Python 3.13** ou superior – [Download](https://www.python.org/downloads/)
- **Git** (opcional, para clonar o repositório) – [Download](https://git-scm.com/)
- Uma conta na **Groq** e uma **API Key** – [console.groq.com](https://console.groq.com/)

### 2️ Obter o código

**Opção A – Clone com Git:**

```bash
git clone https://github.com/GuOMartins/Assistente_IA_Suporte_Python_API_LLM.git
cd Assistente_IA_Suporte_Python_API_LLM
