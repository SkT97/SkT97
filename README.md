[![An abstract illustration of code, data and connected systems](assets/profile-banner.svg)](#)

<table>
<tbody>
<tr>
<td valign="middle">

# Hi, I'm Stiv 👋

I like figuring out how things work. These days, that means building AI applications, trying new tools, and checking whether they actually help.

- **Agents and text-to-SQL:** LangGraph, FastAPI, query validation
- **Retrieval:** hybrid search, embeddings, reranking
- **Evaluation:** RAGAS, LLM-as-judge, reproducible benchmarks
- **LLMOps:** vLLM, LiteLLM, Langfuse, Google Cloud
- **MCP security:** token audiences, delegated identity, tenant isolation

</td>
<td align="center" valign="middle" width="420">

[![SkT97: a donut of ones and zeros and a cone inside it, turning in opposite directions](assets/skt97-ascii.svg)](#)

</td>
</tr>
<tr>
<td colspan="2" align="center">

[![Rotating one-line statements about my work](assets/typing.svg)](#)

</td>
</tr>
</tbody>
</table>

[AI work](#ai-work) · [Projects](#personal-projects) · [Tools](#toolbox) · [Beyond code](#beyond-code) · [LinkedIn](https://www.linkedin.com/in/stiven-velkov/)

## AI work

<details open>
<summary><strong>Agents, RAG and text-to-SQL</strong></summary>

- Document assistants and text-to-SQL agents built with **LangGraph, FastAPI and React**, including query validation.
- **Hybrid search, embeddings and reranking**, with tenant isolation for document retrieval.
- Fine-tuning of a **compact reranker** for a specific retrieval task.

</details>

<details>
<summary><strong>Evaluation and benchmarks</strong></summary>

- **RAGAS, LLM-as-judge evaluations and user feedback** to assess application quality.
- Comparisons of **DuckDB and ClickHouse** for analytical workloads.
- Analysis of coding-agent runs, documenting which runs are included and how results are calculated.

</details>

<details>
<summary><strong>Open models and LLMOps</strong></summary>

- Model selection and serving capacity assessments for the available hardware.
- **vLLM** for serving, **LiteLLM** as a gateway, and **Langfuse** for tracing and feedback.
- Application delivery with **Google Cloud, Docker and CI/CD**.

</details>

<details>
<summary><strong>MCP and authentication</strong></summary>

- Research on **MCP authorization, token audiences and delegated identity**, starting from the specifications.
- Reference implementations and tests using **OAuth/OIDC, Keycloak, tenant isolation and token exchange**.
- Verification of access boundaries when connecting AI applications to tools.

</details>

## Personal projects

| Project | What it does |
| --- | --- |
| **mcp-secure-server** | MCP authentication and tenant isolation, with a runnable Keycloak example |
| **hx** | Run a local coding agent, verify its output, and review changes before applying them |
| **harness-lab** | Analyze recorded agent runs and generate reproducible reports |

<details>
<summary><strong>A note on experiments</strong></summary>

I document the task, data, model and measurement conditions behind a result. For coding-agent comparisons, I also record which runs were excluded and why.

</details>

[![Wave divider](assets/wave.svg)](#)

## Toolbox

| Area | Tools and topics |
| --- | --- |
| **Languages** | [![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logoColor=white&logo=python)](https://www.python.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logoColor=white&logo=typescript)](https://www.typescriptlang.org/) [![Java](https://img.shields.io/badge/Java-E76F00?style=flat&logoColor=white&logo=openjdk)](https://openjdk.org/) [![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat&logoColor=white)](https://www.postgresql.org/docs/current/sql.html) |
| **Applications** | [![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logoColor=white&logo=fastapi)](https://fastapi.tiangolo.com/) [![React](https://img.shields.io/badge/React-149ECA?style=flat&logoColor=white&logo=react)](https://react.dev/) [![Next.js](https://img.shields.io/badge/Next.js-171717?style=flat&logoColor=white&logo=nextdotjs)](https://nextjs.org/) [![LangGraph](https://img.shields.io/badge/LangGraph-176B56?style=flat&logoColor=white&logo=langgraph)](https://docs.langchain.com/oss/python/langgraph/overview) [![DSPy](https://img.shields.io/badge/DSPy-6857CE?style=flat&logoColor=white)](https://dspy.ai/) |
| **AI and RAG** | [![LLMs](https://img.shields.io/badge/LLMs-7C3AED?style=flat&logoColor=white)](#ai-work) [![RAG](https://img.shields.io/badge/RAG-009E73?style=flat&logoColor=white)](#ai-work) [![Text-to-SQL](https://img.shields.io/badge/Text--to--SQL-2563EB?style=flat&logoColor=white)](#ai-work) [![Embeddings](https://img.shields.io/badge/Embeddings-8860D0?style=flat&logoColor=white)](#ai-work) [![Reranking](https://img.shields.io/badge/Reranking-B64883?style=flat&logoColor=white)](#ai-work) [![Fine-tuning](https://img.shields.io/badge/Fine--tuning-BD5A25?style=flat&logoColor=white)](#ai-work) [![MCP](https://img.shields.io/badge/MCP-343B4A?style=flat&logoColor=white&logo=modelcontextprotocol)](https://modelcontextprotocol.io/) [![FlashRank](https://img.shields.io/badge/FlashRank-A84372?style=flat&logoColor=white)](https://github.com/PrithivirajDamodaran/FlashRank) |
| **Evaluation and LLMOps** | [![RAGAS](https://img.shields.io/badge/RAGAS-168A72?style=flat&logoColor=white)](https://docs.ragas.io/) [![LLM-as-judge](https://img.shields.io/badge/LLM--as--judge-6554C0?style=flat&logoColor=white)](#ai-work) [![vLLM](https://img.shields.io/badge/vLLM-A65D08?style=flat&logoColor=white)](https://docs.vllm.ai/) [![LiteLLM](https://img.shields.io/badge/LiteLLM-246A9B?style=flat&logoColor=white)](https://docs.litellm.ai/) [![Langfuse](https://img.shields.io/badge/Langfuse-1D704B?style=flat&logoColor=white&logo=langfuse)](https://langfuse.com/docs) |
| **Databases and retrieval** | [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169A1?style=flat&logoColor=white&logo=postgresql)](https://www.postgresql.org/) [![SQL Server](https://img.shields.io/badge/SQL%20Server-A52627?style=flat&logoColor=white)](https://learn.microsoft.com/sql/sql-server/) [![DuckDB](https://img.shields.io/badge/DuckDB-665600?style=flat&logoColor=white&logo=duckdb)](https://duckdb.org/) [![ClickHouse](https://img.shields.io/badge/ClickHouse-655B00?style=flat&logoColor=white&logo=clickhouse)](https://clickhouse.com/docs) [![Redis](https://img.shields.io/badge/Redis-C92E25?style=flat&logoColor=white&logo=redis)](https://redis.io/) [![Qdrant](https://img.shields.io/badge/Qdrant-C62951?style=flat&logoColor=white&logo=qdrant)](https://qdrant.tech/) [![Vertica](https://img.shields.io/badge/Vertica-12538A?style=flat&logoColor=white)](https://www.vertica.com/) |
| **Cloud and delivery** | [![Docker](https://img.shields.io/badge/Docker-166FC2?style=flat&logoColor=white&logo=docker)](https://www.docker.com/) [![Google Cloud](https://img.shields.io/badge/Google%20Cloud-356AC3?style=flat&logoColor=white&logo=googlecloud)](https://cloud.google.com/) [![Terraform](https://img.shields.io/badge/Terraform-7447D7?style=flat&logoColor=white&logo=terraform)](https://github.com/hashicorp/terraform) [![Git](https://img.shields.io/badge/Git-D7482D?style=flat&logoColor=white&logo=git)](https://git-scm.com/) [![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2368BC?style=flat&logoColor=white&logo=githubactions)](https://docs.github.com/actions) [![Jenkins](https://img.shields.io/badge/Jenkins-A92C32?style=flat&logoColor=white&logo=jenkins)](https://www.jenkins.io/) [![Cloud Run](https://img.shields.io/badge/Cloud%20Run-256BC2?style=flat&logoColor=white&logo=googlecloud)](https://cloud.google.com/run/docs) [![Cloud Build](https://img.shields.io/badge/Cloud%20Build-316BAE?style=flat&logoColor=white&logo=googlecloud)](https://cloud.google.com/build/docs) |
| **Authentication** | [![Keycloak](https://img.shields.io/badge/Keycloak-286575?style=flat&logoColor=white&logo=keycloak)](https://www.keycloak.org/) [![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-18675B?style=flat&logoColor=white)](https://oauth.net/2/) [![OpenID Connect](https://img.shields.io/badge/OpenID%20Connect-B86613?style=flat&logoColor=white&logo=openid)](https://openid.net/developers/how-connect-works/) |

[![Wave divider](assets/wave.svg)](#)

## Beyond code

I'm a **national karate champion**, a **1st-dan black belt**, and an instructor. I've won numerous competitions and coached students who won at national level. I enjoy teaching younger students and helping them develop discipline.

<details>
<summary><strong>A bit more about me</strong></summary>

My curiosity started with the family desktop: setting up our home Wi-Fi, figuring out how things worked, and looking for free alternatives to the tools I used.

I care about healthy living. I'd like to travel the world, learn about different cultures, and work on my own projects along the way.

I believe knowledge should be accessible to everyone. That's one reason I want to share what I learn. I hope AI can give us more time to live, learn and understand ourselves.

</details>

[LinkedIn](https://www.linkedin.com/in/stiven-velkov/) · [GitHub](https://github.com/SkT97)

[![Think deep, don't sink. If you don't know how, observe the phenomena of nature, they will give you clear answers and inspiration.](assets/quote.svg)](#)
