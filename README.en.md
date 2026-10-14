Versión en español: [README.md](README.md)

# Juan Luis León Rodríguez

### Financial controller and data analyst who builds AI systems for business

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jlleonrodriguez-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jlleonrodriguez/)
[![Portfolio](https://img.shields.io/badge/Portfolio-juanluisleon.vercel.app-111111?logo=vercel&logoColor=white)](https://juanluisleon.vercel.app)
[![CV](https://img.shields.io/badge/CV-view-2E7D32)](https://github.com/jleonceo/cv)
[![Email](https://img.shields.io/badge/jleonceo%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:jleonceo@gmail.com)

I have spent more than 25 years in accounting, training and running a business. I was an accounting and IT trainer
for twelve years and ran my own business for thirteen. After that I led operations and management control at a
hospitality company.

Since May 2026 I have been building, every day, an artificial intelligence system for a whole company. Its main
repository has over 6,000 commits. This is not using an assistant. It is agents that share the work with separate
permissions, automations that work and rules the system enforces on its own. No figure leaves it without matching
the database.

I live in Reus, Tarragona, Spain. I am looking for roles in management control, data analysis and BI, or AI
automation.

## What I have built with AI

### Agents and swarms

Five teams of agents: accounting, data analysis, marketing, audiences and software development. Each has its own
orchestrator. Above them, a router decides which team each task goes to. In total there are 55 Claude skills.

Accounting runs on five agents with separate permissions. The one that reads the invoice does not propose the
entry. The one that checks it cannot write. The only one that writes does so to a drafts table, and a person
approves the move to the ledger.

### Process automation

A 19-phase method decides whether a process gets automated, what the AI does, what the code does and who approves.
It was applied in full to supplier invoices arriving by email, with n8n. There are also three applications built
with a specification, tests and verification:

- a bank reconciler that matches the statement against the ledger and leaves a person only the doubtful items;
- a tool that protects the personal data in a table before the AI sees it, with a keyed code and a risk report;
- the cash count of a shop, shift by shift and from the till to the bank.

### AI governance

A rule written in a document is followed by nobody. Only a rule with a mechanism behind it gets followed. That is
why the system has guards that block on the spot: claiming something does not exist without searching for it,
publishing text with machine tics or touching the database without permission. Postponed decisions carry a date,
and a detector warns when they fall due.

### Verification and evaluation

695 test benches, all with cases that must fail. Mutation tests check that those benches really catch errors. Sums
and reconciliations are computed by tested code, never by the model. An in-house instrument even measures whether a
text sounds machine-written, against 23 works written by people.

### AI in finance

An in-house MCP server with six accounting tools. The AI connects with a database user that cannot delete. Below
it, accounts in MySQL with 6,399 entries balanced to the cent. Above it, a Power BI dashboard with 77 DAX measures
checked against SQL.

And a talk on AI skills at Codemarketers, on 26 June 2026.

## Repositories to see it

| Project | What it shows |
|---|---|
| [Accounting with AI agents](https://github.com/jleonceo/accounting-agent-swarm) | Four agents that turn invoices into checked entries: 97.7 % right decisions over 128 documents |
| [Skill governance](https://github.com/jleonceo/gobernanza-skills-analiticas) | The rules for changing an agent's instructions without breaking what already worked |
| [Verified guards](https://github.com/jleonceo/guardianes-verificados-ia) | Checks that an agent's guards really block what they detect, by breaking them on purpose |
| [Swarm orchestration](https://github.com/jleonceo/orquestacion-enjambres-ia) | How each request is routed to the right agent without breaking as the system grows |
| [Test set for an accounting AI](https://github.com/jleonceo/llm-eval-contable) | 50 cases and an automatic grader: the model went from 66 % to 100 % correct |
| [Personal-data gate](https://github.com/jleonceo/pii-output-gate) | Stops any text carrying a valid Spanish ID number or IBAN, checking its control digit |
| [Cash forecasting](https://github.com/jleonceo/tesoreria-forecast-ia) | An error of 4,334 € one month ahead, against 29,444 € for the usual method |
| [Accounting fraud detection](https://github.com/jleonceo/control-interno-fraude-ia) | Eight audit tests on the ledger, from split payments to Benford's law |
| [Context management](https://github.com/jleonceo/claude-code-context-management) | What gets loaded into each AI work session and what is lost when it is summarised, measured |

## Data analysis

| Project | What it shows |
|---|---|
| [Sales, from a raw file to a dashboard](https://github.com/jleonceo/de-datos-en-bruto-a-decisiones) | Cleaning, analysis and statistical testing of seven years of sales, explained on [a website](https://de-datos-en-bruto-a-decisiones.vercel.app) |
| [Lead scoring](https://github.com/jleonceo/lead-scoring-ml) | Calling the top-scored 20 % reaches half of the buyers |
| [Customer segmentation](https://github.com/jleonceo/RFM-Customer-Analytics) | Customers grouped by how recently, how often and how much they buy |
| [Accounting analysis](https://github.com/jleonceo/analisis-contable) | Income statement and cash for one financial year, checked by a second route |
| [Road accidents in Madrid](https://github.com/jleonceo/accident-intelligent-agent) | From the City Council's open data to MySQL, with analysis and a predictive model |

## Tools

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811)
![MySQL](https://img.shields.io/badge/SQL-MySQL-4479A1?logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-own%20servers-555555)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-MCAS-217346?logo=microsoftexcel&logoColor=white)
![Sage](https://img.shields.io/badge/Sage-00D639?logo=sage&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## Career

- 2024 – 2026 · Head of operations and management control, Nou Mestres 2022 SL. Operational reporting and variance
  control. Staff costs 21 % lower with full operations kept.
- 2011 – 2024 · Owner and manager, León Beach Club. Thirteen years running the business: staff, suppliers, banks and
  financial control. Turnover grew 90 % between 2012 and 2023.
- 1999 – 2011 · Accounting and IT trainer. Over 10,000 hours of training in accounting and computing for companies
  and public administration.

Currently studying: Bachelor's in Data Science (Universitat Carlemany) and Master's in Applied AI and Production
Process Optimisation (Visual Business School).
