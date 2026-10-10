<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:2563EB&height=200&section=header&text=AI%20Platform%20Engineer&fontSize=54&fontColor=FFFFFF&desc=LLMOps%20%C2%B7%20Agents%20%C2%B7%20Full-Stack&descSize=22&descAlignY=68&animation=fadeIn)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=60A5FA&center=true&vCenter=true&width=640&lines=LLM+serving+on+Kubernetes+(vLLM+%C2%B7+KubeRay);GitOps+platforms+with+ArgoCD+and+CI+gates;Multi-agent+systems+and+RAG+evaluation;Full-stack+with+Next.js+and+FastAPI)](https://git.io/typing-svg)

</div>

I build LLM serving, agent, and MLOps platforms, and I measure them until the numbers hold up.

- 🔭 Running **vLLM · RAG · evaluation · observability** on a GPU cluster, managed entirely through GitOps
- 🤖 Shipping **LangGraph multi-agent** systems with human-in-the-loop approval, audit trails, and PII masking
- 🌐 Building the web consoles and APIs around AI services with **Next.js** and **FastAPI**
- 🔍 Re-measuring recorded numbers before trusting them: a logged 83.8% accuracy turned out to be 78.0% once re-scored

## 👨‍💻 About Me

```typescript
const me = {
  role: "AI Platform Engineer",
  languages: ["Python", "TypeScript", "SQL", "Bash"],
  askMeAbout: [
    "LLM serving & GPU utilization",
    "GitOps for ML platforms (k3s + ArgoCD)",
    "RAG evaluation & LLM-as-a-judge",
    "Multi-agent orchestration (LangGraph)",
    "Next.js + FastAPI products",
  ],
  principles: [
    "Measure it again before you trust it.",
    "Test the test: feed the gate a bad value and see it fail.",
    "Make every risky change one commit away from rollback.",
  ],
};
```

## 📈 Highlights

| Area | What I did |
|---|---|
| **Platform** | Moved a hand-installed cluster to k3s + ArgoCD GitOps (28 Applications Synced & Healthy); 8 CI deploy gates plus a 36-item self-test of the gates themselves |
| **LLM serving** | vLLM on KubeRay; swapped models 4 times on measured evidence; model load time 221 s → 53 s (4.12×); node-to-node image transfer 87 s → under 1 s |
| **RAG & evaluation** | RAGFlow-based RAG, a 460-question golden set, Langfuse traces and scores, and a dedicated LLM judge separated from the serving model |
| **Agents** | LangGraph supervisor routing, full QA of 41 tools, and a framework port (26 commits) used to make an adoption decision |
| **Products** | AI blog-automation platform, operator web console, and a 190M-row time-series pipeline |

## 🛠 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/-ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

</div>

![AI](https://img.shields.io/badge/AI-vLLM-informational?style=flat&logoColor=white&color=2563EB)
![AI](https://img.shields.io/badge/AI-LangGraph-informational?style=flat&logo=langchain&logoColor=white&color=2563EB)
![AI](https://img.shields.io/badge/AI-MS_Agent_Framework-informational?style=flat&logoColor=white&color=2563EB)
![AI](https://img.shields.io/badge/AI-RAGFlow-informational?style=flat&logoColor=white&color=2563EB)
![AI](https://img.shields.io/badge/AI-Langfuse-informational?style=flat&logoColor=white&color=2563EB)
![AI](https://img.shields.io/badge/AI-MLflow-informational?style=flat&logo=mlflow&logoColor=white&color=2563EB)
![AI](https://img.shields.io/badge/AI-MCP-informational?style=flat&logoColor=white&color=2563EB)

![Platform](https://img.shields.io/badge/Platform-k3s-informational?style=flat&logo=k3s&logoColor=white&color=0F766E)
![Platform](https://img.shields.io/badge/Platform-Helm-informational?style=flat&logo=helm&logoColor=white&color=0F766E)
![Platform](https://img.shields.io/badge/Platform-KubeRay-informational?style=flat&logoColor=white&color=0F766E)
![Platform](https://img.shields.io/badge/Platform-Kueue-informational?style=flat&logoColor=white&color=0F766E)
![Platform](https://img.shields.io/badge/Platform-Argo_Workflows-informational?style=flat&logo=argo&logoColor=white&color=0F766E)
![Platform](https://img.shields.io/badge/Platform-Docker-informational?style=flat&logo=docker&logoColor=white&color=0F766E)

![Observability](https://img.shields.io/badge/Observability-Prometheus-informational?style=flat&logo=prometheus&logoColor=white&color=B45309)
![Observability](https://img.shields.io/badge/Observability-Grafana-informational?style=flat&logo=grafana&logoColor=white&color=B45309)
![Observability](https://img.shields.io/badge/Observability-Loki-informational?style=flat&logo=grafana&logoColor=white&color=B45309)
![CI](https://img.shields.io/badge/CI-GitLab_CI-informational?style=flat&logo=gitlab&logoColor=white&color=B45309)
![CI](https://img.shields.io/badge/CI-GitHub_Actions-informational?style=flat&logo=githubactions&logoColor=white&color=B45309)
![CI](https://img.shields.io/badge/CI-OPA_conftest-informational?style=flat&logo=openpolicyagent&logoColor=white&color=B45309)

![Data](https://img.shields.io/badge/Data-pgvector-informational?style=flat&logo=postgresql&logoColor=white&color=7C3AED)
![Data](https://img.shields.io/badge/Data-Elasticsearch-informational?style=flat&logo=elasticsearch&logoColor=white&color=7C3AED)
![Data](https://img.shields.io/badge/Data-MinIO-informational?style=flat&logo=minio&logoColor=white&color=7C3AED)
![Data](https://img.shields.io/badge/Data-Supabase-informational?style=flat&logo=supabase&logoColor=white&color=7C3AED)
![Data](https://img.shields.io/badge/Data-Prisma-informational?style=flat&logo=prisma&logoColor=white&color=7C3AED)

![Web](https://img.shields.io/badge/Web-React-informational?style=flat&logo=react&logoColor=white&color=2563EB)
![Web](https://img.shields.io/badge/Web-Tailwind_CSS-informational?style=flat&logo=tailwindcss&logoColor=white&color=2563EB)
![Web](https://img.shields.io/badge/Web-Node.js-informational?style=flat&logo=nodedotjs&logoColor=white&color=2563EB)
![Web](https://img.shields.io/badge/Web-React_Native-informational?style=flat&logo=react&logoColor=white&color=2563EB)

![Cloud](https://img.shields.io/badge/Cloud-Google_Cloud-informational?style=flat&logo=googlecloud&logoColor=white&color=0F766E)
![Cloud](https://img.shields.io/badge/Cloud-AWS-informational?style=flat&logoColor=white&color=0F766E)
![Cloud](https://img.shields.io/badge/Cloud-Vercel-informational?style=flat&logo=vercel&logoColor=white&color=0F766E)
![Cloud](https://img.shields.io/badge/Cloud-Cloudflare-informational?style=flat&logo=cloudflare&logoColor=white&color=0F766E)
![Cloud](https://img.shields.io/badge/Cloud-Nginx-informational?style=flat&logo=nginx&logoColor=white&color=0F766E)

<details>
<summary>Also used</summary>

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Google API](https://img.shields.io/badge/-Google_API-4285F4?style=flat-square&logo=google&logoColor=white)
![Google Analytics](https://img.shields.io/badge/-Google_Analytics-E37400?style=flat-square&logo=google-analytics&logoColor=white)
![VMware](https://img.shields.io/badge/-VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Kali Linux](https://img.shields.io/badge/-Kali_Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![WebStorm](https://img.shields.io/badge/-WebStorm-000000?style=flat-square&logo=webstorm&logoColor=white)

</details>

## 📊 GitHub Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Jeff0327&show_icons=true&hide_border=true&count_private=true&title_color=60A5FA&text_color=CBD5E1&icon_color=2563EB&bg_color=0F172A)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Jeff0327&layout=compact&hide_border=true&langs_count=6&title_color=60A5FA&text_color=CBD5E1&bg_color=0F172A)

</div>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:2563EB&height=100&section=footer)
