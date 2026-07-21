# Juan Luis León

**Data Analyst · Business Intelligence · Entrenamiento de AI Skills**

Tarragona / Barcelona · jleonceo@gmail.com · [LinkedIn](https://www.linkedin.com/in/jlleonrodriguez/)

[Español](#español) · [English](#english)

---

## Español

### Sobre mí

Analista de datos con visión de negocio y trayectoria en control de gestión. Trabajo en Business Intelligence, modelado de datos (MySQL, Star Schema) y entrenamiento de **AI Skills** a medida para el análisis recurrente.

Construyo el puente entre el dato y la decisión. Traduzco necesidades de negocio en modelos de datos fiables, dashboards accionables y procesos automatizados.

**Lo que he construido.** Un sistema de contabilidad asistida por IA, de principio a fin. Entra un documento en bruto (una factura, una nómina, un extracto) y sale un asiento contabilizado. Corre sobre TechAcces SL, una empresa simulada con realismo.

Lo llevan **51 AI Skills** repartidas en enjambres por dominio: contabilidad, análisis, tesorería, control interno y marketing. Debajo, MySQL, Power BI, Python, n8n y Claude. El enjambre propone y una persona decide.

**Cómo se mide, con las cifras reales.** Cada versión pasa por un banco de 129 casos antes de producción: golden sets, simulaciones a ciegas y puertas de no-regresión. La medición del 27/06 cerró en **94,2/100 sin ningún falso positivo**. La del 20/07, sobre un banco más duro, bajó a **80,1** y sacó dos. Los dos se diagnosticaron y se corrigieron el 21/07, y la medición completa está pendiente de repetir. Publico las tres cifras porque la que importa no es la mejor, es la última.

Debajo de la IA hay una capa que no lo es: **código determinista que recomprueba el estado por pura aritmética**, inmune al cambio de modelo. Es lo que impide que un sistema de agentes se crea sus propias cifras.

Esa arquitectura se transfiere. La porté a analítica de audiencias reutilizando cerca del 70% del enjambre contable, y de ahí salieron herramientas de previsión de caja y de detección de fraude.

El método y su evidencia están abiertos en los repositorios de abajo. La contabilidad es el primer caso de uso. **El activo es el sistema, no el dominio.**

### Stack técnico

**Business Intelligence**
`Power BI` · `DAX avanzado` · `Modelado dimensional` · `Star Schema`

**Bases de datos**
`SQL avanzado` · `MySQL` · `Modelado relacional`

**Programación y ML**
`Python` · `Pandas` · `Scikit-learn` · `XGBoost` · `Jupyter`

**Sistemas de agentes IA**
`Claude Code` · `Enjambres multi-agente` · `AI Skills a medida` · `RAG` · `MCP` · `Prompt engineering`

**Evaluación de sistemas LLM**
`Eval-driven development` · `Golden sets` · `Simulaciones` · `Puertas de no-regresión` · `Datos sintéticos de test`

**Automatización**
`n8n` · `Claude API` · `Hooks y workflows`

---

### Sistemas de IA: una serie para construir y evaluar (N0 → N3)

Estos repos cuentan, en orden, cómo construir sistemas con varios agentes de IA en los que se puede confiar. Cada uno enlaza a los demás. Se pueden leer como un recorrido.

- **N0 · [tu-primer-asistente-ia-web](https://github.com/jleonceo/tu-primer-asistente-ia-web):** qué es un asistente de IA y cómo se le instruye, sin tecnicismos.
- **N1 · [llm-eval-contable](https://github.com/jleonceo/llm-eval-contable):** evaluar una skill como se examina a un alumno, de 66% a 100% medido.
- **N2 · [accounting-agent-swarm](https://github.com/jleonceo/accounting-agent-swarm):** un enjambre de cuatro agentes contables de principio a fin, con sus caídas explicadas.
- **N2 · [orquestacion-enjambres-ia](https://github.com/jleonceo/orquestacion-enjambres-ia):** el enrutado multi-agente, a qué agente va cada petición sin romper al crecer.
- **N3 · [gobernanza-skills-analiticas](https://github.com/jleonceo/gobernanza-skills-analiticas):** las cinco reglas para gobernar skills, cada una con su cicatriz real.
- **N3 · [verificacion-determinista-ia](https://github.com/jleonceo/verificacion-determinista-ia):** comprobar la coherencia del estado por pura aritmética, sin IA.
- **N3 · [agent-memory-governance](https://github.com/jleonceo/agent-memory-governance):** que la memoria del agente no se convierta en un vertedero.
- **N3 · [claude-code-context-management](https://github.com/jleonceo/claude-code-context-management):** mantener pequeños y al día los ficheros de contexto de Claude Code, sin saturar la ventana.

Y el mismo método portado a otro dominio: **[audience-analyst-swarm](https://github.com/jleonceo/audience-analyst-swarm)**, analítica de audiencias reutilizando cerca del 70% del enjambre contable.

Y el vertical financiero llevado a herramienta: **[tesoreria-forecast-ia](https://github.com/jleonceo/tesoreria-forecast-ia)**, previsión de caja con backtesting, ratios y aging (determinista, sin dependencias).

Y el control interno como herramienta forense: **[control-interno-fraude-ia](https://github.com/jleonceo/control-interno-fraude-ia)**, detección de fraude contable con aritmética dentro de un marco COSO-lite (determinista, sin dependencias).

---

### Datos y machine learning

| Proyecto | Descripción | Stack |
|---|---|---|
| **[analisis-contable](https://github.com/jleonceo/analisis-contable)** | Análisis financiero de principio a fin: cuenta de resultados, tesorería y simulador de escenarios sobre TechAcces SL | Python · MySQL · Pandas |
| **[lead-scoring-ml](https://github.com/jleonceo/lead-scoring-ml)** | Modelo predictivo para priorizar leads comerciales (XGBoost, AUC 0.92 verificado con script de réplica) | Python · ML · Jupyter |
| **[RFM-Customer-Analytics](https://github.com/jleonceo/RFM-Customer-Analytics)** | Segmentación de clientes por Recencia, Frecuencia y Valor monetario, con estrategias de negocio asociadas | Python · Pandas |
| **[accident-intelligent-agent](https://github.com/jleonceo/accident-intelligent-agent)** | Predicción de gravedad de accidentes de tráfico en Madrid: ETL, EDA y modelado predictivo | Python · ML · ETL |

Todo junto, explicado y desplegado, en **[portfolio-juan-luis](https://github.com/jleonceo/portfolio-juan-luis)** ([juanluisleon.vercel.app](https://juanluisleon.vercel.app)).

---

### En qué estoy ahora

- **Máster en IA y Automatización**, Visual Business School (2026)
- **Grado en Ciencia de Datos**, Universitat Carlemany (2º año)
- Construyendo un sistema completo de **automatización contable**: MySQL + Power BI + n8n + Claude
- Evolucionando **enjambres de AI Skills** con evaluación continua: golden sets, simulaciones y puertas de no-regresión

---

### Filosofía

> *Las skills bien entrenadas permanecen. Los modelos cambian y las herramientas se actualizan, pero el criterio construido capa a capa se queda.*

---

Abierto a oportunidades en **Data Analytics** y **Business Intelligence** en **Tarragona y Barcelona** (presencial e híbrido).

---

## English

### About me

Data analyst with a business perspective and a background in management control. I work in Business Intelligence, data modelling (MySQL, Star Schema) and training custom **AI Skills** for recurring analysis.

I build the bridge between data and decision. I turn business needs into reliable data models, actionable dashboards and automated processes.

**What I've built.** An AI-assisted accounting system, end to end. A raw document goes in (an invoice, a payslip, a bank statement) and a booked entry comes out. It runs on TechAcces SL, a realistically simulated company.

**51 custom AI Skills** do the work, grouped into swarms by domain: accounting, analytics, treasury, internal control and marketing. Underneath sit MySQL, Power BI, Python, n8n and Claude. The swarm proposes and a person decides.

**How it is measured, with the real numbers.** Every version faces a 129-case bank before production: golden sets, blind simulations and no-regression gates. The 27 June run closed at **94.2/100 with zero false positives**. The 20 July run, against a harder bank, dropped to **80.1** and produced two. Both were diagnosed and fixed on 21 July, and the full re-measurement is still pending. I publish all three figures because the one that matters is the latest, not the best.

Below the AI sits a layer that is not AI: **deterministic code that re-checks the state by pure arithmetic**, immune to model changes. It is what stops an agent system from believing its own numbers.

That architecture travels. I ported it to audience analytics reusing about 70% of the accounting swarm, and from there came cash-flow forecasting and fraud-detection tools.

The method and its evidence are open in the repositories below. Accounting is the first use case. **The asset is the system, not the domain.**

### Tech stack

**Business Intelligence:** `Power BI` · `Advanced DAX` · `Dimensional modelling` · `Star Schema`
**Databases:** `Advanced SQL` · `MySQL` · `Relational modelling`
**Programming & ML:** `Python` · `Pandas` · `Scikit-learn` · `XGBoost` · `Jupyter`
**AI agent systems:** `Claude Code` · `Multi-agent swarms` · `Custom AI Skills` · `RAG` · `MCP` · `Prompt engineering`
**LLM evaluation:** `Eval-driven development` · `Golden sets` · `Simulations` · `No-regression gates` · `Synthetic test data`
**Automation:** `n8n` · `Claude API` · `Hooks & workflows`

### AI systems: a series to build and evaluate (N0 → N3)

These repos tell, in order, how to build multi-agent AI systems you can trust. Each links to the others, so they read as one path.

- **N0 · [tu-primer-asistente-ia-web](https://github.com/jleonceo/tu-primer-asistente-ia-web):** what an AI assistant is and how you instruct it, for beginners.
- **N1 · [llm-eval-contable](https://github.com/jleonceo/llm-eval-contable):** evaluating a skill the way you examine a student, 66% to 100% measured.
- **N2 · [accounting-agent-swarm](https://github.com/jleonceo/accounting-agent-swarm):** a four-agent accounting swarm end to end, with its drops explained.
- **N2 · [orquestacion-enjambres-ia](https://github.com/jleonceo/orquestacion-enjambres-ia):** multi-agent routing, which agent handles each request without breaking as it grows.
- **N3 · [gobernanza-skills-analiticas](https://github.com/jleonceo/gobernanza-skills-analiticas):** five rules for governing skills, each with its real scar.
- **N3 · [verificacion-determinista-ia](https://github.com/jleonceo/verificacion-determinista-ia):** checking state coherence by pure arithmetic, without AI.
- **N3 · [agent-memory-governance](https://github.com/jleonceo/agent-memory-governance):** keeping the agent's memory from turning into a junkyard.
- **N3 · [claude-code-context-management](https://github.com/jleonceo/claude-code-context-management):** keeping Claude Code's context files small and current, without flooding the window.

The same method ported to another domain: **[audience-analyst-swarm](https://github.com/jleonceo/audience-analyst-swarm)**, audience analytics reusing about 70% of the accounting swarm.

The financial vertical turned into a tool: **[tesoreria-forecast-ia](https://github.com/jleonceo/tesoreria-forecast-ia)**, cash-flow forecasting with backtesting, ratios and aging (deterministic, no dependencies).

Internal control as a forensic tool: **[control-interno-fraude-ia](https://github.com/jleonceo/control-interno-fraude-ia)**, accounting fraud detection with arithmetic inside a COSO-lite framework (deterministic, no dependencies).

### Data & machine learning

| Project | Description | Stack |
|---|---|---|
| **[analisis-contable](https://github.com/jleonceo/analisis-contable)** | End-to-end financial analysis: P&L, cash flow and scenario simulator over TechAcces SL | Python · MySQL · Pandas |
| **[lead-scoring-ml](https://github.com/jleonceo/lead-scoring-ml)** | Predictive model to prioritise sales leads (XGBoost, AUC 0.92 verified with a replication script) | Python · ML · Jupyter |
| **[RFM-Customer-Analytics](https://github.com/jleonceo/RFM-Customer-Analytics)** | Customer segmentation by Recency, Frequency and Monetary value, with associated business strategies | Python · Pandas |
| **[accident-intelligent-agent](https://github.com/jleonceo/accident-intelligent-agent)** | Traffic-accident severity prediction in Madrid: ETL, EDA and predictive modelling | Python · ML · ETL |

All together, explained and deployed, in **[portfolio-juan-luis](https://github.com/jleonceo/portfolio-juan-luis)** ([juanluisleon.vercel.app](https://juanluisleon.vercel.app)).

### What I'm working on now

- **Master's in AI and Automation**, Visual Business School (2026)
- **Bachelor's in Data Science**, Universitat Carlemany (2nd year)
- Building a complete **accounting automation** system: MySQL + Power BI + n8n + Claude
- Evolving **AI Skill swarms** with continuous evaluation: golden sets, simulations and no-regression gates

### Philosophy

> *Well-trained skills endure. Models change and tools get updated, but the judgment built layer by layer stays.*

---

Open to **Data Analytics** and **Business Intelligence** roles in **Tarragona and Barcelona** (on-site and hybrid).
