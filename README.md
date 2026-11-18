<img src="header.svg" alt="Vatsal Mittal — Full-stack development and applied AI" width="100%" />

<p align="center">
<a href="#about">About</a> &nbsp; / &nbsp;
<a href="#technologies">Technologies</a> &nbsp; / &nbsp;
<a href="#selected-work">Selected work</a> &nbsp; / &nbsp;
<a href="https://github.com/vatsal-mittal-7904?tab=repositories">All repositories</a>
</p>

## About

<table>
<tr>
<td width="72%" valign="top">
<p>I build web applications with <b>TypeScript and Python</b>, bringing together interfaces, backend APIs, relational databases, and applied AI.</p>
<p>My work spans conversational commerce, retail operations, multi-agent systems, and planning tools. I focus on the workflows behind the interface: validating inputs, managing transactions, streaming updates, and keeping people involved in AI-assisted decisions.</p>
<p><b>Across my projects</b></p>
<ul>
<li>Full-stack applications with React, Next.js, and FastAPI.</li>
<li>Data workflows with PostgreSQL, Prisma, and structured validation.</li>
<li>AI integration through document recognition and agent orchestration.</li>
</ul>
</td>
<td width="28%" align="center" valign="middle">
<img src="assets/portrait.jpg" alt="Portrait of Vatsal Mittal" width="180" />
</td>
</tr>
</table>

## Technologies

<p><b>Languages</b></p>
<p><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-18222f?style=for-the-badge&logo=typescript&logoColor=6CB9FF" height="28" />
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-18222f?style=for-the-badge&logo=javascript&logoColor=F7DF1E" height="28" />
<img alt="Python" src="https://img.shields.io/badge/Python-18222f?style=for-the-badge&logo=python&logoColor=8DBFE3" height="28" /></p>
<p><b>Frontend & APIs</b></p>
<p><img alt="React" src="https://img.shields.io/badge/React-18222f?style=for-the-badge&logo=react&logoColor=61DAFB" height="28" />
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-18222f?style=for-the-badge&logo=nextdotjs&logoColor=FFFFFF" height="28" />
<img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind%20CSS-18222f?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8" height="28" />
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-18222f?style=for-the-badge&logo=fastapi&logoColor=5ED9BF" height="28" /></p>
<p><b>Data & applied AI</b></p>
<p><img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-18222f?style=for-the-badge&logo=postgresql&logoColor=8DBFE3" height="28" />
<img alt="Prisma" src="https://img.shields.io/badge/Prisma-18222f?style=for-the-badge&logo=prisma&logoColor=FFFFFF" height="28" />
<img alt="Gemini" src="https://img.shields.io/badge/Gemini-18222f?style=for-the-badge&logo=googlegemini&logoColor=C4B5FD" height="28" />
<img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-18222f?style=for-the-badge&logo=langgraph&logoColor=80D7B1" height="28" />
<img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-18222f?style=for-the-badge&logo=scikitlearn&logoColor=F4B67B" height="28" /></p>

## Selected work

<table>
<tr>
<td width="50%" valign="top">
<p><sub>COMMERCE & PAYMENTS</sub></p>
<h3><a href="https://github.com/vatsal-mittal-7904/razorPay_Project">MerchantOS</a></h3>
<p>AI-assisted product discovery connected to Razorpay checkout, with server-side payment and spending rules.</p>
<ul><li>Customer-approved offers and order creation.</li><li>Verified webhooks, reconciliation, and inventory updates.</li></ul>
<p><sub>Next.js · TypeScript · PostgreSQL · Prisma</sub></p>
<details>
<summary>Architecture &amp; implementation</summary>
<ul><li>Server-side discount, margin, and spending limits constrain checkout actions.</li><li>Payment verification and reconciliation connect provider state to order settlement.</li><li>Merchant analytics and campaign workflows include human approval.</li></ul>
<p><sub>Built for the Razorpay Agentic Commerce Hackathon.</sub></p>
</details>
</td><td width="50%" valign="top">
<p><sub>RETAIL OPERATIONS</sub></p>
<h3><a href="https://github.com/vatsal-mittal-7904/vatsal-bath-gallery">Vatsal Bath Gallery</a></h3>
<p>A retail management application connecting handwritten orders, product catalogues, billing, and inventory.</p>
<ul><li>Hindi and Hinglish slip recognition with staff review.</li><li>Estimates, invoices, payments, and profit reporting.</li></ul>
<p><sub>Next.js · TypeScript · PostgreSQL · Gemini</sub></p>
<details>
<summary>Architecture &amp; implementation</summary>
<ul><li>Gemini extracts order lines; fuzzy matching proposes catalogue candidates for review.</li><li>Catalogue variants, estimates, and GST invoice calculations support counter operations.</li><li>Transactional stock movements and role-based access separate staff work from owner-only costs and margins.</li></ul>

</details>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><sub>MULTI-AGENT SYSTEMS</sub></p>
<h3><a href="https://github.com/vatsal-mittal-7904/Neural_Arbiter.">Neural Arbiter</a></h3>
<p>Opposing AI agents debate a topic while a separate model returns structured evaluations and summaries.</p>
<ul><li>Stateful debate rounds and human participation.</li><li>Live transcripts, argument graphs, and evaluation charts.</li></ul>
<p><sub>Python · FastAPI · LangGraph · React</sub></p>
<details>
<summary>Architecture &amp; implementation</summary>
<ul><li>LangGraph manages shared debate state and pauses for human participation.</li><li>FastAPI streams updates over WebSockets to a React dashboard.</li><li>Pydantic structures model evaluations; fallback handling and offline mocks support development.</li></ul>

</details>
</td><td width="50%" valign="top">
<p><sub>PLANNING & OPTIMIZATION</sub></p>
<h3><a href="https://github.com/vatsal-mittal-7904/form-flow-ai">Formwork Optimization</a></h3>
<p>A Streamlit simulation of a formwork planning workflow, from geometry inputs to material quantities.</p>
<ul><li>Geometry analysis, clustering, and genetic scheduling.</li><li>Material kitting, quantities, and a feedback stage.</li></ul>
<p><sub>Python · Streamlit · scikit-learn · OR-Tools</sub></p>
<details>
<summary>Architecture &amp; implementation</summary>
<ul><li>Simulates data ingestion and geometry analysis before optimization.</li><li>Explores clustering and genetic scheduling with planning libraries.</li><li>Includes automated kitting, bill-of-quantities generation, and a digital-twin feedback stage.</li></ul>

</details>
</td>
</tr>
</table>

<details>
<summary><b>Additional tools used across these projects</b></summary>

| Area | Tools & techniques |
| :--- | :--- |
| Validation & testing | Zod, Pydantic, Vitest, offline mock workflows |
| Real-time applications | WebSockets, streaming transcripts, interactive charts |
| Analytics & planning | pandas, NumPy, PyGAD, OR-Tools, Plotly |
| Application workflows | Access control, payment verification, transactional inventory, audit records |

</details>

---

<p align="center"><a href="https://github.com/vatsal-mittal-7904?tab=repositories"><b>Explore all repositories</b></a></p>
