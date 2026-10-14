English version: [README.en.md](README.en.md)

# Juan Luis León Rodríguez

### Controller financiero y analista de datos que construye sistemas de IA para la empresa

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jlleonrodriguez-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jlleonrodriguez/)
[![Portfolio](https://img.shields.io/badge/Portfolio-juanluisleon.vercel.app-111111?logo=vercel&logoColor=white)](https://juanluisleon.vercel.app)
[![CV](https://img.shields.io/badge/Currículum-ver-2E7D32)](https://github.com/jleonceo/cv)
[![Email](https://img.shields.io/badge/jleonceo%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:jleonceo@gmail.com)

Llevo más de 25 años entre contabilidad, formación y dirección de empresa. Fui formador técnico y contable durante
doce años y dirigí mi propio negocio durante trece. Después llevé las operaciones y el control de gestión de una
empresa de hostelería.

Desde mayo de 2026 construyo a diario un sistema de inteligencia artificial para una empresa completa. Su
repositorio principal pasa de 6.000 commits. No es usar un asistente. Son agentes que se reparten el trabajo con
permisos separados, automatizaciones que funcionan y reglas que el sistema hace cumplir solo. Ninguna cifra sale
de él sin cuadrar con la base de datos.

Vivo en Reus, Tarragona. Busco puestos de control de gestión, análisis de datos y BI o automatización con IA.

## Lo que he construido con IA

### Agentes y enjambres

Cinco equipos de agentes: contabilidad, análisis de datos, marketing, audiencias y programación. Cada uno tiene su
orquestador. Por encima, un enrutador decide a qué equipo va cada tarea. En total son 55 skills de Claude.

En contabilidad trabajan cinco agentes con permisos separados. El que lee la factura no propone el asiento. El que lo
verifica no puede escribir. El único que escribe lo hace en una tabla de borradores, y el paso al libro diario lo
aprueba una persona.

### Automatización de procesos

Un método de 19 fases decide si un proceso se automatiza, qué hace la IA, qué hace el código y quién aprueba. Se
aplicó entero a la entrada de facturas de proveedor por correo, con n8n. Además hay tres aplicaciones construidas
con especificación, pruebas y verificación:

- un conciliador bancario que cruza el extracto con el diario y deja a una persona solo las dudas;
- una herramienta que protege los datos personales de una tabla antes de que la vea la IA, con un código cifrado con
  clave y un informe del riesgo;
- el cuadre de caja de un comercio, turno a turno y del cajón al banco.

### Gobernanza de IA

Una regla escrita en un documento no la cumple nadie. Solo se cumple la que tiene un mecanismo detrás. Por eso el
sistema tiene guardianes que bloquean en el momento: afirmar que algo no existe sin buscarlo, publicar texto con
tics de máquina o tocar la base de datos sin permiso. Las decisiones aplazadas llevan fecha, y un detector avisa
cuando vencen.

### Verificación y evaluación

695 bancos de pruebas, todos con casos que tienen que fallar. Unas pruebas de mutación comprueban que esos bancos
detectan errores de verdad. Las sumas y los cuadres los calcula código probado, nunca el modelo. Un instrumento
propio mide incluso si un texto suena a máquina, contra 23 obras escritas por personas.

### IA en finanzas

Un servidor MCP propio con seis herramientas contables. La IA entra con un usuario de base de datos que no puede
borrar. Debajo, una contabilidad en MySQL con 6.399 asientos cuadrados al céntimo. Encima, un cuadro de mando en
Power BI con 77 medidas DAX contrastadas con SQL.

Y una charla sobre skills de IA en Codemarketers, el 26 de junio de 2026.

## Repositorios para verlo

| Proyecto | Qué demuestra |
|---|---|
| [Contabilidad con agentes de IA](https://github.com/jleonceo/accounting-agent-swarm) | Cuatro agentes que convierten facturas en asientos comprobados: 97,7 % de decisiones correctas sobre 128 documentos |
| [Gobernanza de skills](https://github.com/jleonceo/gobernanza-skills-analiticas) | Las reglas para cambiar las instrucciones de un agente sin estropear lo que ya funcionaba |
| [Guardianes verificados](https://github.com/jleonceo/guardianes-verificados-ia) | Comprueba que los guardianes de un agente bloquean de verdad lo que detectan, rompiéndolos a propósito |
| [Orquestación de enjambres](https://github.com/jleonceo/orquestacion-enjambres-ia) | Cómo se decide a qué agente va cada petición sin que falle al crecer |
| [Examen para una IA contable](https://github.com/jleonceo/llm-eval-contable) | 50 casos y un corrector automático: el modelo pasó del 66 % al 100 % de aciertos |
| [Portero de datos personales](https://github.com/jleonceo/pii-output-gate) | Impide que salga un texto con un DNI, un NIE o un IBAN válidos, comprobando su dígito de control |
| [Previsión de tesorería](https://github.com/jleonceo/tesoreria-forecast-ia) | Un error de 4.334 € a un mes, frente a 29.444 € del método habitual |
| [Detección de fraude contable](https://github.com/jleonceo/control-interno-fraude-ia) | Ocho pruebas de auditoría sobre el libro diario, de los pagos partidos a la ley de Benford |
| [Gestión del contexto](https://github.com/jleonceo/claude-code-context-management) | Qué se carga en cada sesión de trabajo con IA y qué se pierde al resumirla, medido |

## Análisis de datos

| Proyecto | Qué demuestra |
|---|---|
| [Ventas, de un fichero en bruto a un cuadro de mando](https://github.com/jleonceo/de-datos-en-bruto-a-decisiones) | Limpieza, análisis y contraste estadístico de siete años de ventas, explicado en [una web](https://de-datos-en-bruto-a-decisiones.vercel.app) |
| [Puntuación de clientes potenciales](https://github.com/jleonceo/lead-scoring-ml) | Llamando al 20 % mejor puntuado se llega a la mitad de los compradores |
| [Segmentación de clientes](https://github.com/jleonceo/RFM-Customer-Analytics) | Clientes agrupados por lo reciente, lo frecuente y lo mucho que compran |
| [Análisis contable](https://github.com/jleonceo/analisis-contable) | Cuenta de resultados y tesorería de un ejercicio, comprobadas por un segundo camino |
| [Accidentes de tráfico en Madrid](https://github.com/jleonceo/accident-intelligent-agent) | De los datos abiertos del Ayuntamiento a MySQL, con análisis y un modelo predictivo |

## Herramientas

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811)
![MySQL](https://img.shields.io/badge/SQL-MySQL-4479A1?logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-servidores%20propios-555555)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-MCAS-217346?logo=microsoftexcel&logoColor=white)
![Sage](https://img.shields.io/badge/Sage-00D639?logo=sage&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## Trayectoria

- 2024 – 2026 · Responsable de operaciones y control de gestión, Nou Mestres 2022 SL. Reporting operativo y
  control de desviaciones. Coste de personal un 21 % más bajo con la operativa completa.
- 2011 – 2024 · Propietario y gerente, León Beach Club. Trece años de dirección: equipo, proveedores, bancos y
  control económico. La facturación creció un 90 % entre 2012 y 2023.
- 1999 – 2011 · Formador técnico y contable. Más de 10.000 horas de formación en contabilidad e informática
  para empresas y administración pública.

Formación en curso: Grado en Ciencia de Datos (Universitat Carlemany) y Máster en IA Aplicada y Optimización de
Procesos Productivos (Visual Business School).
