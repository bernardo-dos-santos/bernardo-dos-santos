<h1 align="center">Bernardo dos Santos Ferreira</h1>

<p align="center">
  Estudante de Ciência da Computação · Automação de processos e IA aplicada<br>
  Lages, Santa Catarina, Brasil
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bernardo-dos-santos-ferreira-221603356">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Bernardo_dos_Santos_Ferreira-0A66C2?style=flat&logo=linkedin&logoColor=white">
  </a>
</p>

---

## Sobre

Curso Ciência da Computação no **IFSC (Campus Lages)** e atuo como estagiário de **automação de processos na Prefeitura Municipal de Lages**. Meu foco é reduzir trabalho manual: integrar APIs, bancos de dados, planilhas e modelos de IA em fluxos que rodam sozinhos e que outras pessoas conseguem usar no dia a dia.

Inglês avançado.

## Competências técnicas

| Área | Tecnologias |
| --- | --- |
| Linguagens | Python · C# · Java · SQL |
| Automação e dados | Google Apps Script · Google Sheets · Looker Studio |
| Bancos de dados | PostgreSQL · SQLite |
| Integrações | APIs REST · WhatsApp Cloud API · Google Gemini |
| Back-end | Flask · Gunicorn · APScheduler |
| Qualidade | pytest · Git e GitHub |

## Projeto em destaque

### [OptiScan](https://github.com/bernardo-dos-santos/OptiScan) — controle de estoque pelo WhatsApp com leitura por IA

O usuário envia a foto de uma etiqueta ou o PDF de uma NF-e. O sistema extrai os dados com visão computacional (Gemini), atualiza o saldo no PostgreSQL e sincroniza a planilha do Google Sheets nos dois sentidos.

- **Multi-cliente:** cada empresa tem planilha, números autorizados e contexto de IA próprios.
- **Leitura de notas fiscais:** cruza o CNPJ do cliente com emitente e destinatário para classificar entrada ou saída e calcular o custo unitário.
- **Rotinas agendadas:** resumo diário de itens abaixo do estoque mínimo e análise semanal que sugere novo estoque mínimo.
- **Segurança:** valida a assinatura HMAC dos webhooks da Meta e recusa requisições sem assinatura.
- **Testes:** cobertura com pytest das funções de validação e de conversão numérica.

`Python` `Flask` `Gemini` `PostgreSQL` `Google Sheets` `WhatsApp Cloud API`

## Outros projetos

- **[e-Agenda](https://github.com/bernardo-dos-santos/e-Agenda)**, **[ClubeDaLeitura](https://github.com/bernardo-dos-santos/ClubeDaLeitura)** e **[GestaoDeEquipamentos](https://github.com/bernardo-dos-santos/GestaoDeEquipamentos)** — aplicações em C# desenvolvidas na graduação, evoluindo de console para arquitetura em camadas.

## Disponibilidade

Procuro estágio em **automação, IA aplicada e processos**, com preferência por trabalho remoto no período da tarde.

---

<p align="center">
  <a href="https://www.linkedin.com/in/bernardo-dos-santos-ferreira-221603356">Vamos conversar no LinkedIn</a>
</p>
