<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:2563EB&height=220&section=header&text=Jeff0327&fontSize=64&fontColor=FFFFFF&desc=AI%20Platform%20%C2%B7%20LLMOps%20%C2%B7%20Full-Stack%20Engineer&descSize=22&descAlignY=65&animation=fadeIn)

**LLM 서빙 · 에이전트 · MLOps 플랫폼을 "돌아간다고 믿는" 수준이 아니라 "돌아간다고 증명되는" 수준까지 만듭니다.**

</div>

## 👋 About

- 🧠 GPU 클러스터 위에 **vLLM 서빙 · RAG · 평가 · 관측** 계층을 GitOps로 구축하고 운영합니다.
- 🤖 **LangGraph 멀티 에이전트**(HITL 승인, 감사 원장, PII 마스킹)와 음성·채팅 상담 에이전트를 PoC부터 배포까지 만들었습니다.
- 🌐 **Next.js · FastAPI**로 AI 서비스의 웹 콘솔과 API를 직접 만듭니다. 자체 제품도 1인으로 기획부터 운영까지 해 왔습니다.
- 🔍 기록된 숫자를 그대로 믿지 않고 **다시 재봅니다.** 정답률 83.8%를 재측정해 78.0%로 정정한 적이 있습니다.

## 📈 해 온 일

| 영역 | 내용 |
|---|---|
| **Platform** | 수작업 설치 클러스터를 k3s + ArgoCD로 전면 GitOps 전환 (Application 28개 Synced·Healthy), CI 배포 게이트 8종 + 게이트 자기검증 36항목 |
| **LLM 서빙** | vLLM on KubeRay, 실측 근거로 모델 4회 교체, 모델 적재 221초 → 53초 (4.12배), 노드 간 이미지 전송 87초 → 1초 미만 |
| **RAG · 평가** | RAGFlow 기반 RAG, 골든셋 460문항 기준선, Langfuse 트레이스·점수, 서빙 모델과 분리한 전용 LLM judge |
| **Agent** | LangGraph Supervisor 라우팅, 도구 41종 전수 QA, MS Agent Framework 포팅 검증(26커밋) 후 프레임워크 채택 의사결정 |
| **Product** | AI 블로그 자동화 플랫폼, 딜러용 운영 웹 콘솔, 대용량 시계열 수집·서빙 파이프라인(1.9억 행) |

## 🛠 Tech Stack

**자주 쓰는 도구**

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/-ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

| 구분 | 스택 |
|---|---|
| **AI / LLM** | vLLM · LangGraph · MS Agent Framework · RAGFlow · BGE-M3 · Whisper · LiveKit · MCP · Langfuse · MLflow |
| **Platform** | Kubernetes(k3s) · ArgoCD · Helm · Kustomize · KubeRay · Kueue · Argo Workflows · Cilium · Docker |
| **Observability · CI** | Prometheus · Grafana · Loki · Alertmanager · GitLab CI · GitHub Actions · conftest(OPA) · pytest |
| **Backend · Data** | FastAPI · Node.js · PostgreSQL(pgvector) · Redis · Elasticsearch · MinIO · Supabase · Prisma |
| **Frontend** | Next.js · React · Tailwind CSS · React Native |
| **Cloud** | GCP(Vertex AI) · AWS(EC2/S3) · Vercel · Cloudflare · Nginx |

<details>
<summary>그 외 사용 경험</summary>

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
![GitLab](https://img.shields.io/badge/-GitLab-FCA121?style=flat-square&logo=gitlab&logoColor=white)

</details>

## 📊 GitHub

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Jeff0327&show_icons=true&theme=radical&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Jeff0327&layout=compact&theme=radical&hide_border=true&langs_count=6)

</div>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:2563EB&height=100&section=footer)
