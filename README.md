# agendamentoprefeitura
Trabalho do curso de Gestão e Qualidade de Software 2025.2
# 🏥 Portal de Agendamento de Consultas da Prefeitura

## 🎯 Descrição do Projeto
O **Portal de Agendamento de Consultas da Prefeitura** é um sistema web desenvolvido com o objetivo de facilitar o acesso dos cidadãos aos serviços de saúde do município, permitindo o **cadastro**, **login seguro**, **agendamento**, **visualização** e **cancelamento de consultas médicas** em unidades públicas.

Esse projeto foi elaborado no contexto da disciplina **Gestão da Qualidade de Software**, abordando especificação de requisitos, correlação com modelos de referência (CMMI e ISO/IEC 25010), prototipação, testes automatizados e controle de versões via GitHub.

---

## 👩‍💻 Equipe de Desenvolvimento
| Integrante | RA | Responsabilidade |
|-------------|-------------|--------------------|
| **Aerlon Lucas de Oliveira Leite** | 1272315979 | Módulo de agendamento e testes relacionados |
| **João Batista Lopes Araújo** | 825161059 | Documentação e requisitos não funcionais |
| **Luan Erick dos Santos** | 12825136755 | Módulo de autenticação e controle de versões (GitHub) |
| **Lucca Shizuru da Costa** | 825233423 | Casos de uso, protótipos e relatório final |

---

## ⚙️ Funcionalidades Principais
- [x] Cadastro de cidadãos com validação de CPF  
- [x] Login seguro com autenticação  
- [x] Visualização de horários disponíveis por unidade  
- [x] Agendamento de consultas médicas  
- [x] Cancelamento de consultas  
- [x] Envio de notificações (e-mail/SMS)  
- [x] Painel administrativo para unidades de saúde  
- [x] Geração de relatórios gerenciais  

---

## 📋 Requisitos
### Funcionais
- **RF1** – Permitir o cadastro do cidadão com dados pessoais e CPF.  
- **RF2** – Realizar login seguro no sistema.  
- **RF4** – Permitir agendamento de consultas.  
- **RF5** – Permitir cancelamento de consultas.  
- **RF6** – Enviar notificações automatizadas de confirmação ou cancelamento.  

### Não Funcionais
- **RNF1** – Disponibilidade 24/7.  
- **RNF2** – Tempo de resposta inferior a 3 segundos.  
- **RNF3** – Comunicação via HTTPS.  
- **RNF5** – Suporte multiplataforma (desktop e mobile).  
- **RNF6** – Acessibilidade conforme WCAG 2.1.  

---

## 🧩 Correlação com Modelos de Referência e Normas
- **CMMI – Desenvolvimento de Requisitos (RD):** entendimento claro das necessidades dos usuários.  
- **CMMI – Gerenciamento de Requisitos (REQM):** rastreabilidade entre requisitos e testes.  
- **CMMI – Verificação (VER):** execução de testes automatizados com Selenium.  
- **CMMI – Validação (VAL):** garantia de que o sistema atende às necessidades reais dos cidadãos.  

### ISO/IEC 25010
| Característica | Subcaracterística | Aplicação |
|----------------|-------------------|------------|
| **Segurança** | Confidencialidade | Proteção de dados conforme a LGPD. |
| **Confiabilidade** | Disponibilidade | Serviço acessível 24/7. |
| **Usabilidade** | Acessibilidade | Interface conforme WCAG 2.1. |

---

## 🧪 Testes Automatizados
A ferramenta **Selenium WebDriver (Python)** foi utilizada para os testes automatizados dos principais fluxos do sistema.  

### Casos de Teste
- **CT01 – Login de Cidadão:** valida autenticação de usuário.  
- **CT02 – Agendamento de Consulta:** confirma agendamento e envio de notificação.  
- **CT03 – Cancelamento de Consulta:** verifica exclusão de consulta e atualização de horários disponíveis.  

Os testes foram executados em ambiente de desenvolvimento e apresentaram **100% de sucesso**, garantindo aderência às práticas de **Verificação (VER)** e **Validação (VAL)** do CMMI.

---

## 🔧 Ferramentas e Tecnologias
- **Frontend:** HTML5, CSS3, JavaScript  
- **Backend (prototipado):** Node.js ou Python Flask *(dependendo de escolha do grupo)*  
- **Banco de Dados:** MySQL (conceitual)  
- **Automação de Testes:** [Selenium](https://www.selenium.dev/)  
- **Gestão de Código e Versões:** [GitHub](https://github.com/)  

---
