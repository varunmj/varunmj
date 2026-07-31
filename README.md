<div align="center">
  <img width="100%" src="https://raw.githubusercontent.com/varunmj/varunmj/output/github-snake-dark.svg" alt="Snake animation" />
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&fontColor=FF9900&text=VARUN%20MOHANKUMAR%20JAYASREE&fontSize=40&height=280&desc=Founder%20%40%20NewRun%20%7C%20Former%20Product%20%40%20AWS&descColor=E6EDF3&descSize=18&animation=fadeIn" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&color=FF9900&center=true&vCenter=true&width=840&lines=%24+whoami+%E2%86%92+Founder+%40+NewRun;%24+prev+%E2%86%92+Product+%40+Amazon+Web+Services;%24+lang+%E2%86%92+Python+%7C+TypeScript+%7C+SQL;%24+shipped+%E2%86%92+cloudwatch-janitor+on+PyPI;%24+status+%E2%86%92+Building+NewRun+%7C+newrun.club" />
</div>

<div align="center">

![Role](https://img.shields.io/badge/Founder-NewRun-FF9900?style=flat-square&logo=rocket&logoColor=0D1117)
![Education](https://img.shields.io/badge/M.S._Information_Systems_%26_Management-1F6FEB?style=flat-square&logo=googlescholar&logoColor=white)
![Location](https://img.shields.io/badge/Greater_Chicago_Area-3FB950?style=flat-square&logo=googlemaps&logoColor=white)

</div>

<div align="center">

[![NewRun](https://img.shields.io/badge/NewRun-newrun.club-FF9900?style=for-the-badge&logo=googlechrome&logoColor=0D1117)](https://newrun.club)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1F6FEB?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE/)
[![Email](https://img.shields.io/badge/Email-FF9900?style=for-the-badge&logo=gmail&logoColor=0D1117)](mailto:varunmj978@gmail.com)

</div>

---

## `> whoami`

Founder at **[NewRun](https://newrun.club)**, based in the Greater Chicago Area. Before this I was a Product Manager at **Amazon Web Services**. I build at the intersection of product and engineering — most of my current work ships in NewRun's private repos, and I open-source the tools I build along the way (most recently [`cloudwatch-janitor`](https://github.com/varunmj/cloudwatch-janitor), a read-only AWS cost-audit CLI on PyPI).

```bash
$ cat .profile

ROLE     =  Founder @ NewRun
PREV     =  Product @ Amazon Web Services
DOMAIN   =  Product Engineering  |  Data Engineering  |  Cloud / AWS
STACK    =  Python  |  TypeScript  |  SQL  |  AWS
EDU      =  M.S. Information Systems & Management (SWE / PM focus)
STATUS   =  Heads-down on NewRun — public work = tools I extract from it
```

---

## `> ls tech-stack/`

<div align="center">

**Languages**

![Languages](https://skillicons.dev/icons?i=py,ts,js,java,mysql,postgres)

**Cloud & Infrastructure**

![Cloud](https://skillicons.dev/icons?i=aws,docker,linux,git,github,vercel)

**Frameworks & Tools**

![Tools](https://skillicons.dev/icons?i=react,nextjs,nodejs,tailwind,flask,vscode)

**Data**

![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Redshift](https://img.shields.io/badge/Amazon_Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

</div>

---

## `> ls featured-projects/`

<details open>
<summary><b>&#9654; cloudwatch-janitor &mdash; Find the CloudWatch waste hiding in your AWS bill</b></summary>

A read-only CLI that audits an AWS account for CloudWatch waste — log groups with no retention policy, alarms watching deleted resources, dashboards nobody opens — and estimates monthly savings. Four read-only API calls; never modifies anything; output is safe to paste straight into Slack.

| Aspect | Detail |
| :-- | :-- |
| **Stack** | Python &middot; boto3 &middot; AWS CloudWatch APIs |
| **Distribution** | Published on [PyPI](https://pypi.org/project/cloudwatch-janitor/) &middot; CI on every push &middot; MIT license |
| **Design** | Read-only by construction &middot; no account IDs or IAM identities in output |
| **Repo** | [varunmj/cloudwatch-janitor](https://github.com/varunmj/cloudwatch-janitor) |

```bash
pip install cloudwatch-janitor && cloudwatch-janitor --profile prod
```

</details>

<details>
<summary><b>&#9654; NewRun &mdash; What I'm building full-time</b></summary>

Founder at NewRun — most of this work lives in private repos, which is why my public contribution graph doesn't tell the whole story. Public tools like `cloudwatch-janitor` are extracted from this work.

| Aspect | Detail |
| :-- | :-- |
| **Role** | Founder — product, engineering, and everything in between |
| **Live** | [newrun.club](https://newrun.club) |

</details>

<details>
<summary><b>&#9654; H1B Twitter Analyzer &mdash; Real-time sentiment dashboard</b></summary>

Two-part system analyzing sentiment of H1B-related tweets with Hugging Face transformers: a Python scraper + sentiment pipeline backed by PostgreSQL, and a React/Next.js dashboard visualizing sentiment in real time.

| Aspect | Detail |
| :-- | :-- |
| **Stack** | Python &middot; Hugging Face &middot; PostgreSQL &middot; React &middot; Next.js |
| **Deploy** | Frontend on Vercel &middot; backend on AWS EC2 |
| **Repo** | [varunmj/H1B_Twitter_Analyzer_Prod](https://github.com/varunmj/H1B_Twitter_Analyzer_Prod) |

</details>

<details>
<summary><b>&#9654; Reddit Data Pipeline &mdash; Airflow-orchestrated ETL on AWS</b></summary>

End-to-end data pipeline integrating Reddit, Apache Airflow, Celery, PostgreSQL, S3, AWS Glue, Athena, and Redshift — containerized with Docker.

| Aspect | Detail |
| :-- | :-- |
| **Stack** | Python &middot; Airflow &middot; Celery &middot; Docker &middot; S3 / Glue / Athena / Redshift |
| **Repo** | [varunmj/Reddit_Data_Pipeline_Engineering](https://github.com/varunmj/Reddit_Data_Pipeline_Engineering) |

</details>

<details>
<summary><b>&#9654; Zillow ETL on AWS &mdash; Real-estate data pipeline</b></summary>

End-to-end ETL pipeline extracting real-estate data from Zillow via RapidAPI, transforming it, and loading it into Amazon Redshift.

| Aspect | Detail |
| :-- | :-- |
| **Stack** | Python &middot; RapidAPI &middot; AWS &middot; Redshift |
| **Repo** | [varunmj/data-engineering-Zillow_ETL_AWS](https://github.com/varunmj/data-engineering-Zillow_ETL_AWS) |

</details>

---

## `> git log --experience`

**Founder** | NewRun | Greater Chicago Area
- Building NewRun end-to-end — product strategy, architecture, and shipping code
- Open-sourcing internal tooling along the way (`cloudwatch-janitor`)

**Product Manager** | Amazon Web Services
- Product management for AWS services — roadmap, customer discovery, and cross-team delivery

`Product` &middot; `AWS` &middot; `Python` &middot; `TypeScript` &middot; `Data Engineering`

---

## `> gh stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=varunmj&show_icons=true&hide_border=true&title_color=FF9900&icon_color=3FB950&text_color=E6EDF3&bg_color=0D1117&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varunmj&layout=compact&hide_border=true&title_color=FF9900&text_color=E6EDF3&bg_color=0D1117&langs_count=8" />

</div>

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=varunmj&bg_color=0D1117&color=FF9900&line=FF9900&point=3FB950&area=true&area_color=1F6FEB&hide_border=true)](https://github.com/varunmj)

</div>

---

## `> cat current-focus.yaml`

```yaml
building:
  - NewRun (newrun.club) — full-time
  - cloudwatch-janitor — AWS cost-audit CLI on PyPI

exploring:
  - AI-powered product workflows
  - FinOps and cloud cost tooling
  - Data pipelines that don't wake you up at 3am

open_to:
  - Collaborators and early users for NewRun
  - Feedback, issues, and PRs on cloudwatch-janitor
```

---

## `> cat connect.yaml`

<div align="center">

[![NewRun](https://img.shields.io/badge/NewRun-newrun.club-FF9900?style=for-the-badge&logo=googlechrome&logoColor=0D1117)](https://newrun.club)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1F6FEB?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE/)
[![Email](https://img.shields.io/badge/Email-FF9900?style=for-the-badge&logo=gmail&logoColor=0D1117)](mailto:varunmj978@gmail.com)

</div>

<div align="center">

> *"Ship the tool you wish existed — then open-source it."*

</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&fontColor=FF9900&height=120&section=footer&text=Thanks%20for%20visiting!&fontSize=22&descColor=E6EDF3" />
</div>
