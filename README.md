<h1 align="center">Juan Céspedes</h1>

<p align="center">Systems engineer in Barranquilla, Colombia. Full-stack development, data and automation.</p>

<p align="center">
  <a href="https://juancespedes.dev/en"><img src="https://img.shields.io/badge/Portfolio-juancespedes.dev-111111?style=for-the-badge&logo=astro&logoColor=white" alt="Portfolio: juancespedes.dev"></a>
  <a href="https://www.linkedin.com/in/juan-cespedesjc"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSIjZmZmIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij48cGF0aCBkPSJNMTE2IDNIMTJhOC45MSA4LjkxIDAgMDAtOSA4Ljh2MTA0LjQyYTguOTEgOC45MSAwIDAwOSA4Ljc4aDEwNGE4LjkzIDguOTMgMCAwMDktOC44MVYxMS43N0E4LjkzIDguOTMgMCAwMDExNiAzek0zOS4xNyAxMDdIMjEuMDZWNDguNzNoMTguMTF6bS05LTY2LjIxYTEwLjUgMTAuNSAwIDExMTAuNDktMTAuNSAxMC41IDEwLjUgMCAwMS0xMC41NCAxMC40OHpNMTA3IDEwN0g4OC44OVY3OC42NWMwLTYuNzUtLjEyLTE1LjQ0LTkuNDEtMTUuNDRzLTEwLjg3IDcuMzYtMTAuODcgMTVWMTA3SDUwLjUzVjQ4LjczaDE3LjM2djhoLjI0YzIuNDItNC41OCA4LjMyLTkuNDEgMTcuMTMtOS40MUMxMDMuNiA0Ny4yOCAxMDcgNTkuMzUgMTA3IDc1eiIvPjwvc3ZnPg%3D%3D" alt="LinkedIn"></a>
  <a href="mailto:juanpablocespedesj@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Barranquilla,_Colombia-FCD116?style=for-the-badge&logo=googlemaps&logoColor=black" alt="Barranquilla, Colombia">
</p>

## About

I'm a systems engineer at a power generation company in Colombia. Since 2024
I have built and put into production six web systems used by the operations,
communications, procurement and finance teams. On these projects I handle the
whole stack: databases and data pipelines, backend, frontend, Linux servers
and automated tests.

## Recent work

- **[Portfolio: juancespedes.dev](https://juancespedes.dev/en)**: my personal site, bilingual and
  built in public as a frontend work sample. Astro with React islands,
  TypeScript and Tailwind CSS on Cloudflare Workers, with a case study for each
  project below, 33 architecture decision records and performance and
  accessibility checks that block the merge.
- **[Corporate website](https://www.gecelca.com.co/es/)**: I led the rebuild
  of the bilingual site, 134 pages in Spanish and English on WordPress with a
  custom block theme. It meets WCAG 2.2 AA.
  ([case study](https://juancespedes.dev/en/projects/corporate-portal))
- **Operations logbook** for four power plants. It replaced the Excel
  files the operators used before. React, Node.js, WebSockets, SQL Server and
  Entra ID single sign-on, with more than 600 automated tests.
  ([case study](https://juancespedes.dev/en/projects/operations-logbook))
- **Metering point records**: the official 18-section life record of the
  metering system at each energy trading point. Every change is a draft that
  is reviewed and published as an immutable version with its official PDF and
  Word file. React, TypeScript, Express, Kysely, SQL Server and Entra ID, with
  more than 950 automated tests; in user testing.
  ([case study](https://juancespedes.dev/en/projects/metering-life-record))
- **Plant telemetry**: reads five energy meters over Modbus TCP every 2
  seconds (15 to 25 ms per read) and publishes the data to Microsoft Fabric
  and Power BI. ([case study](https://juancespedes.dev/en/projects/plant-telemetry))
- **Power BI reports in production**: four reports with 146 DAX measures in
  all, a [thermal generation scorecard](https://juancespedes.dev/en/projects/generation-scorecard)
  with IEEE reliability indicators, [rainfall monitoring](https://juancespedes.dev/en/projects/rainfall-monitoring),
  [budget execution](https://juancespedes.dev/en/projects/budget-execution) and the
  [finances of a solar energy program](https://juancespedes.dev/en/projects/solar-program-finance).
  They run on Microsoft Fabric: ETL pipelines and notebooks load the sources
  into bronze, silver and gold lakehouses (a medallion architecture), and a
  Fabric warehouse feeds each report's model. Each one has a live public
  replica with synthetic data.
- **Mine dashboard on Microsoft Fabric** (in progress): moving a coal mine's
  Excel dashboard to Power BI on a bronze, silver and gold model whose figures
  match the Excel ones (24 of 24 indicators, checked with Spark). The 10
  pipelines are generated from versioned T-SQL and deployed with the Fabric
  CLI and the Fabric MCP server.
  ([case study](https://juancespedes.dev/en/projects/mine-dashboard-fabric))
- **E-invoicing ETL**: I took over a legacy pipeline (Airflow, Selenium,
  Oracle, MongoDB) that was failing without raising any alert, and added 151
  tests and CI while it kept running in production.
  ([case study](https://juancespedes.dev/en/projects/invoice-etl-rescue))
- **[Event platform](https://cdp.gecelca.com.co/)** for a corporate forum
  with more than 160 guests: agenda and results, QR credentials, Microsoft
  Graph integration and 156 attendance certificates generated and checked by
  script. ([case study](https://juancespedes.dev/en/projects/event-platform))

The code for these projects belongs to my employer and is private, so each one
is told as a case study on [my portfolio](https://juancespedes.dev/en), with the problem, the
decisions, an architecture diagram and the results. My public repositories are
listed under Open source below.

## Tech stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-0078D4?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI0YyNTAyMiIgZD0iTTEgMWgxMHYxMEgxeiIvPjxwYXRoIGZpbGw9IiM3RkJBMDAiIGQ9Ik0xMyAxaDEwdjEwSDEzeiIvPjxwYXRoIGZpbGw9IiMwMEE0RUYiIGQ9Ik0xIDEzaDEwdjEwSDF6Ii8%2BPHBhdGggZmlsbD0iI0ZGQjkwMCIgZD0iTTEzIDEzaDEwdjEwSDEzeiIvPjwvc3ZnPg%3D%3D)

**Data and BI**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGVsbGlwc2UgY3g9IjEyIiBjeT0iNSIgcng9IjgiIHJ5PSIzIi8%2BPHBhdGggZD0iTTQgN3Y0YzAgMS43IDMuNiAzIDggM3M4LTEuMyA4LTNWN2MwIDEuNy0zLjYgMy04IDNTNCA4LjcgNCA3eiIvPjxwYXRoIGQ9Ik00IDEzdjRjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtM3YtNGMwIDEuNy0zLjYgMy04IDNzLTgtMS4zLTgtM3oiLz48L3N2Zz4%3D)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMiIgeT0iNiIgd2lkdGg9IjIwIiBoZWlnaHQ9IjEyIiByeD0iNiIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjMiLz48L3N2Zz4%3D)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iIzAwMCI%2BPHJlY3QgeD0iMTQiIHk9IjIiIHdpZHRoPSI2IiBoZWlnaHQ9IjIwIiByeD0iMS41Ii8%2BPHJlY3QgeD0iOC41IiB5PSI3IiB3aWR0aD0iNiIgaGVpZ2h0PSIxNSIgcng9IjEuNSIgb3BhY2l0eT0iLjgiLz48cmVjdCB4PSIzIiB5PSIxMiIgd2lkdGg9IjYiIGhlaWdodD0iMTAiIHJ4PSIxLjUiIG9wYWNpdHk9Ii42Ii8%2BPC9zdmc%2B)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-117865?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI0YyNTAyMiIgZD0iTTEgMWgxMHYxMEgxeiIvPjxwYXRoIGZpbGw9IiM3RkJBMDAiIGQ9Ik0xMyAxaDEwdjEwSDEzeiIvPjxwYXRoIGZpbGw9IiMwMEE0RUYiIGQ9Ik0xIDEzaDEwdjEwSDF6Ii8%2BPHBhdGggZmlsbD0iI0ZGQjkwMCIgZD0iTTEzIDEzaDEwdjEwSDEzeiIvPjwvc3ZnPg%3D%3D)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)

**Automation and AI**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZD0iTTIgNWMzLTEgNi0xIDkgMHY2YzAgNC0yIDctNC41IDdTMiAxNSAyIDExeiIvPjxwYXRoIGQ9Ik0xMyA3YzMtMSA2LTEgOSAwdjZjMCA0LTIgNy00LjUgN1MxMyAxNyAxMyAxM3oiIG9wYWNpdHk9Ii43NSIvPjwvc3ZnPg%3D%3D)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_servers-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![Modbus](https://img.shields.io/badge/Modbus_TCP-5C2D91?style=for-the-badge&logo=lightning&logoColor=white)

**DevOps and security**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI0YyNTAyMiIgZD0iTTEgMWgxMHYxMEgxeiIvPjxwYXRoIGZpbGw9IiM3RkJBMDAiIGQ9Ik0xMyAxaDEwdjEwSDEzeiIvPjxwYXRoIGZpbGw9IiMwMEE0RUYiIGQ9Ik0xIDEzaDEwdjEwSDF6Ii8%2BPHBhdGggZmlsbD0iI0ZGQjkwMCIgZD0iTTEzIDEzaDEwdjEwSDEzeiIvPjwvc3ZnPg%3D%3D)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

## Open source

- [**juancespedes.dev**](https://github.com/juanpacj-wq/juancespedes.dev): the
  source of [my portfolio](https://juancespedes.dev/en), built in public as a frontend work sample.
  Astro with React islands, TypeScript and Tailwind CSS on Cloudflare Workers,
  with 24 architecture decision records and performance and accessibility
  checks that block the merge.
- [**linkedin-mcp**](https://github.com/juanpacj-wq/linkedin-mcp): MCP
  server and CLI that operates LinkedIn through your own browser session
  (profile editing, networking and Easy Apply), built on Playwright. It applies
  rate limits and asks for confirmation before any action other people can see.
  ([case study](https://juancespedes.dev/en/projects/linkedin-pilot))
- [**speedrun-github-achievements**](https://github.com/juanpacj-wq/speedrun-github-achievements):
  a guide to GitHub achievements in Spanish, 14 chapters.

## Certifications

![Azure Fundamentals](https://img.shields.io/badge/Azure_Fundamentals-0078D4?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZD0iTTkuNSAyaDVMNyAyMkgyeiIvPjxwYXRoIGQ9Ik0xNCA4bDggMTRIOWw3LTN6Ii8%2BPC9zdmc%2B)
![Azure Data Fundamentals](https://img.shields.io/badge/Azure_Data_Fundamentals-0078D4?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZD0iTTkuNSAyaDVMNyAyMkgyeiIvPjxwYXRoIGQ9Ik0xNCA4bDggMTRIOWw3LTN6Ii8%2BPC9zdmc%2B)
![Cisco Junior Cybersecurity Analyst](https://img.shields.io/badge/Cisco_Junior_Cybersecurity_Analyst-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![EF SET C2](https://img.shields.io/badge/English-C2_(EF_SET)-2EA44F?style=flat-square)

